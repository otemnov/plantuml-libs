# Hoppscotch


```text
simpleicons-14/H/Hoppscotch
```

```text
include('simpleicons-14/H/Hoppscotch')
```



| Illustration | Hoppscotch |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-14/H/Hoppscotch.png) | ![illustration for Hoppscotch](../../simpleicons-14/H/Hoppscotch.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$HoppscotchXs>`
- `<$HoppscotchSm>`
- `<$HoppscotchMd>`
- `<$HoppscotchLg>`





## Hoppscotch

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-14/bootstrap')

' loads the Item which embeds the element Hoppscotch
include('simpleicons-14/H/Hoppscotch')

' renders the element
Hoppscotch('Hoppscotch', 'Hoppscotch', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Hoppscotch
include('simpleicons-14/H/Hoppscotch')

' renders the element
Hoppscotch('Hoppscotch', 'Hoppscotch', 'an optional tech label', 'an optional description')
@enduml
```

