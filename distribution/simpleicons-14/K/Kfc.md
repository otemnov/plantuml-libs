# Kfc


```text
simpleicons-14/K/Kfc
```

```text
include('simpleicons-14/K/Kfc')
```



| Illustration | Kfc |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-14/K/Kfc.png) | ![illustration for Kfc](../../simpleicons-14/K/Kfc.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$KfcXs>`
- `<$KfcSm>`
- `<$KfcMd>`
- `<$KfcLg>`





## Kfc

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-14/bootstrap')

' loads the Item which embeds the element Kfc
include('simpleicons-14/K/Kfc')

' renders the element
Kfc('Kfc', 'Kfc', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Kfc
include('simpleicons-14/K/Kfc')

' renders the element
Kfc('Kfc', 'Kfc', 'an optional tech label', 'an optional description')
@enduml
```

