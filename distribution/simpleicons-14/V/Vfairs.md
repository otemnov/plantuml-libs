# Vfairs


```text
simpleicons-14/V/Vfairs
```

```text
include('simpleicons-14/V/Vfairs')
```



| Illustration | Vfairs |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-14/V/Vfairs.png) | ![illustration for Vfairs](../../simpleicons-14/V/Vfairs.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$VfairsXs>`
- `<$VfairsSm>`
- `<$VfairsMd>`
- `<$VfairsLg>`





## Vfairs

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-14/bootstrap')

' loads the Item which embeds the element Vfairs
include('simpleicons-14/V/Vfairs')

' renders the element
Vfairs('Vfairs', 'Vfairs', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Vfairs
include('simpleicons-14/V/Vfairs')

' renders the element
Vfairs('Vfairs', 'Vfairs', 'an optional tech label', 'an optional description')
@enduml
```

