# Socketdotio


```text
simpleicons-14/S/Socketdotio
```

```text
include('simpleicons-14/S/Socketdotio')
```



| Illustration | Socketdotio |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-14/S/Socketdotio.png) | ![illustration for Socketdotio](../../simpleicons-14/S/Socketdotio.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$SocketdotioXs>`
- `<$SocketdotioSm>`
- `<$SocketdotioMd>`
- `<$SocketdotioLg>`





## Socketdotio

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-14/bootstrap')

' loads the Item which embeds the element Socketdotio
include('simpleicons-14/S/Socketdotio')

' renders the element
Socketdotio('Socketdotio', 'Socketdotio', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Socketdotio
include('simpleicons-14/S/Socketdotio')

' renders the element
Socketdotio('Socketdotio', 'Socketdotio', 'an optional tech label', 'an optional description')
@enduml
```

