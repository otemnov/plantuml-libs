# Welcometothejungle


```text
simpleicons-14/W/Welcometothejungle
```

```text
include('simpleicons-14/W/Welcometothejungle')
```



| Illustration | Welcometothejungle |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-14/W/Welcometothejungle.png) | ![illustration for Welcometothejungle](../../simpleicons-14/W/Welcometothejungle.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$WelcometothejungleXs>`
- `<$WelcometothejungleSm>`
- `<$WelcometothejungleMd>`
- `<$WelcometothejungleLg>`





## Welcometothejungle

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-14/bootstrap')

' loads the Item which embeds the element Welcometothejungle
include('simpleicons-14/W/Welcometothejungle')

' renders the element
Welcometothejungle('Welcometothejungle', 'Welcometothejungle', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Welcometothejungle
include('simpleicons-14/W/Welcometothejungle')

' renders the element
Welcometothejungle('Welcometothejungle', 'Welcometothejungle', 'an optional tech label', 'an optional description')
@enduml
```

