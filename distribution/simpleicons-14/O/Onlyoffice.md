# Onlyoffice


```text
simpleicons-14/O/Onlyoffice
```

```text
include('simpleicons-14/O/Onlyoffice')
```



| Illustration | Onlyoffice |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-14/O/Onlyoffice.png) | ![illustration for Onlyoffice](../../simpleicons-14/O/Onlyoffice.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$OnlyofficeXs>`
- `<$OnlyofficeSm>`
- `<$OnlyofficeMd>`
- `<$OnlyofficeLg>`





## Onlyoffice

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-14/bootstrap')

' loads the Item which embeds the element Onlyoffice
include('simpleicons-14/O/Onlyoffice')

' renders the element
Onlyoffice('Onlyoffice', 'Onlyoffice', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Onlyoffice
include('simpleicons-14/O/Onlyoffice')

' renders the element
Onlyoffice('Onlyoffice', 'Onlyoffice', 'an optional tech label', 'an optional description')
@enduml
```

