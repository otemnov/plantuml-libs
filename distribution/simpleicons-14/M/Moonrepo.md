# Moonrepo


```text
simpleicons-14/M/Moonrepo
```

```text
include('simpleicons-14/M/Moonrepo')
```



| Illustration | Moonrepo |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-14/M/Moonrepo.png) | ![illustration for Moonrepo](../../simpleicons-14/M/Moonrepo.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$MoonrepoXs>`
- `<$MoonrepoSm>`
- `<$MoonrepoMd>`
- `<$MoonrepoLg>`





## Moonrepo

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-14/bootstrap')

' loads the Item which embeds the element Moonrepo
include('simpleicons-14/M/Moonrepo')

' renders the element
Moonrepo('Moonrepo', 'Moonrepo', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Moonrepo
include('simpleicons-14/M/Moonrepo')

' renders the element
Moonrepo('Moonrepo', 'Moonrepo', 'an optional tech label', 'an optional description')
@enduml
```

