# Ducati


```text
simpleicons-14/D/Ducati
```

```text
include('simpleicons-14/D/Ducati')
```



| Illustration | Ducati |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-14/D/Ducati.png) | ![illustration for Ducati](../../simpleicons-14/D/Ducati.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$DucatiXs>`
- `<$DucatiSm>`
- `<$DucatiMd>`
- `<$DucatiLg>`





## Ducati

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-14/bootstrap')

' loads the Item which embeds the element Ducati
include('simpleicons-14/D/Ducati')

' renders the element
Ducati('Ducati', 'Ducati', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Ducati
include('simpleicons-14/D/Ducati')

' renders the element
Ducati('Ducati', 'Ducati', 'an optional tech label', 'an optional description')
@enduml
```

