# Zwave


```text
simpleicons-14/Z/Zwave
```

```text
include('simpleicons-14/Z/Zwave')
```



| Illustration | Zwave |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-14/Z/Zwave.png) | ![illustration for Zwave](../../simpleicons-14/Z/Zwave.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$ZwaveXs>`
- `<$ZwaveSm>`
- `<$ZwaveMd>`
- `<$ZwaveLg>`





## Zwave

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-14/bootstrap')

' loads the Item which embeds the element Zwave
include('simpleicons-14/Z/Zwave')

' renders the element
Zwave('Zwave', 'Zwave', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Zwave
include('simpleicons-14/Z/Zwave')

' renders the element
Zwave('Zwave', 'Zwave', 'an optional tech label', 'an optional description')
@enduml
```

