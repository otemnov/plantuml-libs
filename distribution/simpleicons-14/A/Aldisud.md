# Aldisud


```text
simpleicons-14/A/Aldisud
```

```text
include('simpleicons-14/A/Aldisud')
```



| Illustration | Aldisud |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-14/A/Aldisud.png) | ![illustration for Aldisud](../../simpleicons-14/A/Aldisud.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$AldisudXs>`
- `<$AldisudSm>`
- `<$AldisudMd>`
- `<$AldisudLg>`





## Aldisud

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-14/bootstrap')

' loads the Item which embeds the element Aldisud
include('simpleicons-14/A/Aldisud')

' renders the element
Aldisud('Aldisud', 'Aldisud', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Aldisud
include('simpleicons-14/A/Aldisud')

' renders the element
Aldisud('Aldisud', 'Aldisud', 'an optional tech label', 'an optional description')
@enduml
```

