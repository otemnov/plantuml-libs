# Patreon


```text
simpleicons-14/P/Patreon
```

```text
include('simpleicons-14/P/Patreon')
```



| Illustration | Patreon |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-14/P/Patreon.png) | ![illustration for Patreon](../../simpleicons-14/P/Patreon.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$PatreonXs>`
- `<$PatreonSm>`
- `<$PatreonMd>`
- `<$PatreonLg>`





## Patreon

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-14/bootstrap')

' loads the Item which embeds the element Patreon
include('simpleicons-14/P/Patreon')

' renders the element
Patreon('Patreon', 'Patreon', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Patreon
include('simpleicons-14/P/Patreon')

' renders the element
Patreon('Patreon', 'Patreon', 'an optional tech label', 'an optional description')
@enduml
```

