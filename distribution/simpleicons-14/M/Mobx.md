# Mobx


```text
simpleicons-14/M/Mobx
```

```text
include('simpleicons-14/M/Mobx')
```



| Illustration | Mobx |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-14/M/Mobx.png) | ![illustration for Mobx](../../simpleicons-14/M/Mobx.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$MobxXs>`
- `<$MobxSm>`
- `<$MobxMd>`
- `<$MobxLg>`





## Mobx

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-14/bootstrap')

' loads the Item which embeds the element Mobx
include('simpleicons-14/M/Mobx')

' renders the element
Mobx('Mobx', 'Mobx', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Mobx
include('simpleicons-14/M/Mobx')

' renders the element
Mobx('Mobx', 'Mobx', 'an optional tech label', 'an optional description')
@enduml
```

