# Wprocket


```text
simpleicons-14/W/Wprocket
```

```text
include('simpleicons-14/W/Wprocket')
```



| Illustration | Wprocket |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-14/W/Wprocket.png) | ![illustration for Wprocket](../../simpleicons-14/W/Wprocket.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$WprocketXs>`
- `<$WprocketSm>`
- `<$WprocketMd>`
- `<$WprocketLg>`





## Wprocket

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-14/bootstrap')

' loads the Item which embeds the element Wprocket
include('simpleicons-14/W/Wprocket')

' renders the element
Wprocket('Wprocket', 'Wprocket', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Wprocket
include('simpleicons-14/W/Wprocket')

' renders the element
Wprocket('Wprocket', 'Wprocket', 'an optional tech label', 'an optional description')
@enduml
```

