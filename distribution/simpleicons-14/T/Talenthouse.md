# Talenthouse


```text
simpleicons-14/T/Talenthouse
```

```text
include('simpleicons-14/T/Talenthouse')
```



| Illustration | Talenthouse |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-14/T/Talenthouse.png) | ![illustration for Talenthouse](../../simpleicons-14/T/Talenthouse.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$TalenthouseXs>`
- `<$TalenthouseSm>`
- `<$TalenthouseMd>`
- `<$TalenthouseLg>`





## Talenthouse

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-14/bootstrap')

' loads the Item which embeds the element Talenthouse
include('simpleicons-14/T/Talenthouse')

' renders the element
Talenthouse('Talenthouse', 'Talenthouse', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Talenthouse
include('simpleicons-14/T/Talenthouse')

' renders the element
Talenthouse('Talenthouse', 'Talenthouse', 'an optional tech label', 'an optional description')
@enduml
```

