# Schneiderelectric


```text
simpleicons-14/S/Schneiderelectric
```

```text
include('simpleicons-14/S/Schneiderelectric')
```



| Illustration | Schneiderelectric |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-14/S/Schneiderelectric.png) | ![illustration for Schneiderelectric](../../simpleicons-14/S/Schneiderelectric.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$SchneiderelectricXs>`
- `<$SchneiderelectricSm>`
- `<$SchneiderelectricMd>`
- `<$SchneiderelectricLg>`





## Schneiderelectric

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-14/bootstrap')

' loads the Item which embeds the element Schneiderelectric
include('simpleicons-14/S/Schneiderelectric')

' renders the element
Schneiderelectric('Schneiderelectric', 'Schneiderelectric', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Schneiderelectric
include('simpleicons-14/S/Schneiderelectric')

' renders the element
Schneiderelectric('Schneiderelectric', 'Schneiderelectric', 'an optional tech label', 'an optional description')
@enduml
```

