# Convertio


```text
simpleicons-14/C/Convertio
```

```text
include('simpleicons-14/C/Convertio')
```



| Illustration | Convertio |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-14/C/Convertio.png) | ![illustration for Convertio](../../simpleicons-14/C/Convertio.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$ConvertioXs>`
- `<$ConvertioSm>`
- `<$ConvertioMd>`
- `<$ConvertioLg>`





## Convertio

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-14/bootstrap')

' loads the Item which embeds the element Convertio
include('simpleicons-14/C/Convertio')

' renders the element
Convertio('Convertio', 'Convertio', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Convertio
include('simpleicons-14/C/Convertio')

' renders the element
Convertio('Convertio', 'Convertio', 'an optional tech label', 'an optional description')
@enduml
```

