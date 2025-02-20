# Airbus


```text
simpleicons-14/A/Airbus
```

```text
include('simpleicons-14/A/Airbus')
```



| Illustration | Airbus |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-14/A/Airbus.png) | ![illustration for Airbus](../../simpleicons-14/A/Airbus.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$AirbusXs>`
- `<$AirbusSm>`
- `<$AirbusMd>`
- `<$AirbusLg>`





## Airbus

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-14/bootstrap')

' loads the Item which embeds the element Airbus
include('simpleicons-14/A/Airbus')

' renders the element
Airbus('Airbus', 'Airbus', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Airbus
include('simpleicons-14/A/Airbus')

' renders the element
Airbus('Airbus', 'Airbus', 'an optional tech label', 'an optional description')
@enduml
```

