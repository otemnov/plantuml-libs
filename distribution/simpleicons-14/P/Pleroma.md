# Pleroma


```text
simpleicons-14/P/Pleroma
```

```text
include('simpleicons-14/P/Pleroma')
```



| Illustration | Pleroma |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-14/P/Pleroma.png) | ![illustration for Pleroma](../../simpleicons-14/P/Pleroma.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$PleromaXs>`
- `<$PleromaSm>`
- `<$PleromaMd>`
- `<$PleromaLg>`





## Pleroma

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-14/bootstrap')

' loads the Item which embeds the element Pleroma
include('simpleicons-14/P/Pleroma')

' renders the element
Pleroma('Pleroma', 'Pleroma', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Pleroma
include('simpleicons-14/P/Pleroma')

' renders the element
Pleroma('Pleroma', 'Pleroma', 'an optional tech label', 'an optional description')
@enduml
```

