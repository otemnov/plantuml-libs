# Pocket


```text
simpleicons-14/P/Pocket
```

```text
include('simpleicons-14/P/Pocket')
```



| Illustration | Pocket |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-14/P/Pocket.png) | ![illustration for Pocket](../../simpleicons-14/P/Pocket.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$PocketXs>`
- `<$PocketSm>`
- `<$PocketMd>`
- `<$PocketLg>`





## Pocket

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-14/bootstrap')

' loads the Item which embeds the element Pocket
include('simpleicons-14/P/Pocket')

' renders the element
Pocket('Pocket', 'Pocket', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Pocket
include('simpleicons-14/P/Pocket')

' renders the element
Pocket('Pocket', 'Pocket', 'an optional tech label', 'an optional description')
@enduml
```

