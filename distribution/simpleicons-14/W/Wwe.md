# Wwe


```text
simpleicons-14/W/Wwe
```

```text
include('simpleicons-14/W/Wwe')
```



| Illustration | Wwe |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-14/W/Wwe.png) | ![illustration for Wwe](../../simpleicons-14/W/Wwe.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$WweXs>`
- `<$WweSm>`
- `<$WweMd>`
- `<$WweLg>`





## Wwe

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-14/bootstrap')

' loads the Item which embeds the element Wwe
include('simpleicons-14/W/Wwe')

' renders the element
Wwe('Wwe', 'Wwe', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Wwe
include('simpleicons-14/W/Wwe')

' renders the element
Wwe('Wwe', 'Wwe', 'an optional tech label', 'an optional description')
@enduml
```

