# Scrutinizerci


```text
simpleicons-14/S/Scrutinizerci
```

```text
include('simpleicons-14/S/Scrutinizerci')
```



| Illustration | Scrutinizerci |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-14/S/Scrutinizerci.png) | ![illustration for Scrutinizerci](../../simpleicons-14/S/Scrutinizerci.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$ScrutinizerciXs>`
- `<$ScrutinizerciSm>`
- `<$ScrutinizerciMd>`
- `<$ScrutinizerciLg>`





## Scrutinizerci

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-14/bootstrap')

' loads the Item which embeds the element Scrutinizerci
include('simpleicons-14/S/Scrutinizerci')

' renders the element
Scrutinizerci('Scrutinizerci', 'Scrutinizerci', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Scrutinizerci
include('simpleicons-14/S/Scrutinizerci')

' renders the element
Scrutinizerci('Scrutinizerci', 'Scrutinizerci', 'an optional tech label', 'an optional description')
@enduml
```

