# Roots


```text
simpleicons-14/R/Roots
```

```text
include('simpleicons-14/R/Roots')
```



| Illustration | Roots |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-14/R/Roots.png) | ![illustration for Roots](../../simpleicons-14/R/Roots.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$RootsXs>`
- `<$RootsSm>`
- `<$RootsMd>`
- `<$RootsLg>`





## Roots

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-14/bootstrap')

' loads the Item which embeds the element Roots
include('simpleicons-14/R/Roots')

' renders the element
Roots('Roots', 'Roots', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Roots
include('simpleicons-14/R/Roots')

' renders the element
Roots('Roots', 'Roots', 'an optional tech label', 'an optional description')
@enduml
```

