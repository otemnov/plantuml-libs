# Suse


```text
simpleicons-14/S/Suse
```

```text
include('simpleicons-14/S/Suse')
```



| Illustration | Suse |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-14/S/Suse.png) | ![illustration for Suse](../../simpleicons-14/S/Suse.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$SuseXs>`
- `<$SuseSm>`
- `<$SuseMd>`
- `<$SuseLg>`





## Suse

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-14/bootstrap')

' loads the Item which embeds the element Suse
include('simpleicons-14/S/Suse')

' renders the element
Suse('Suse', 'Suse', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Suse
include('simpleicons-14/S/Suse')

' renders the element
Suse('Suse', 'Suse', 'an optional tech label', 'an optional description')
@enduml
```

