# Onnx


```text
simpleicons-14/O/Onnx
```

```text
include('simpleicons-14/O/Onnx')
```



| Illustration | Onnx |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-14/O/Onnx.png) | ![illustration for Onnx](../../simpleicons-14/O/Onnx.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$OnnxXs>`
- `<$OnnxSm>`
- `<$OnnxMd>`
- `<$OnnxLg>`





## Onnx

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-14/bootstrap')

' loads the Item which embeds the element Onnx
include('simpleicons-14/O/Onnx')

' renders the element
Onnx('Onnx', 'Onnx', 'an optional tech label', 'an optional description')
@enduml
```

### Load locally
```plantuml
@startuml
' configures the library
!global $INCLUSION_MODE="local"
!global $LIB_BASE_LOCATION="../.."

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-14/bootstrap')

' loads the Item which embeds the element Onnx
include('simpleicons-14/O/Onnx')

' renders the element
Onnx('Onnx', 'Onnx', 'an optional tech label', 'an optional description')
@enduml
```

