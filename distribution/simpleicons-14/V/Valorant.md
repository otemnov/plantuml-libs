# Valorant


```text
simpleicons-14/V/Valorant
```

```text
include('simpleicons-14/V/Valorant')
```



| Illustration | Valorant |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-14/V/Valorant.png) | ![illustration for Valorant](../../simpleicons-14/V/Valorant.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$ValorantXs>`
- `<$ValorantSm>`
- `<$ValorantMd>`
- `<$ValorantLg>`





## Valorant

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-14/bootstrap')

' loads the Item which embeds the element Valorant
include('simpleicons-14/V/Valorant')

' renders the element
Valorant('Valorant', 'Valorant', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Valorant
include('simpleicons-14/V/Valorant')

' renders the element
Valorant('Valorant', 'Valorant', 'an optional tech label', 'an optional description')
@enduml
```

