# Line


```text
simpleicons-14/L/Line
```

```text
include('simpleicons-14/L/Line')
```



| Illustration | Line |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-14/L/Line.png) | ![illustration for Line](../../simpleicons-14/L/Line.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$LineXs>`
- `<$LineSm>`
- `<$LineMd>`
- `<$LineLg>`





## Line

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-14/bootstrap')

' loads the Item which embeds the element Line
include('simpleicons-14/L/Line')

' renders the element
Line('Line', 'Line', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Line
include('simpleicons-14/L/Line')

' renders the element
Line('Line', 'Line', 'an optional tech label', 'an optional description')
@enduml
```

