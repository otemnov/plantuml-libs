# Subversion


```text
simpleicons-14/S/Subversion
```

```text
include('simpleicons-14/S/Subversion')
```



| Illustration | Subversion |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-14/S/Subversion.png) | ![illustration for Subversion](../../simpleicons-14/S/Subversion.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$SubversionXs>`
- `<$SubversionSm>`
- `<$SubversionMd>`
- `<$SubversionLg>`





## Subversion

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-14/bootstrap')

' loads the Item which embeds the element Subversion
include('simpleicons-14/S/Subversion')

' renders the element
Subversion('Subversion', 'Subversion', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Subversion
include('simpleicons-14/S/Subversion')

' renders the element
Subversion('Subversion', 'Subversion', 'an optional tech label', 'an optional description')
@enduml
```

