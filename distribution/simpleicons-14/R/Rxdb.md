# Rxdb


```text
simpleicons-14/R/Rxdb
```

```text
include('simpleicons-14/R/Rxdb')
```



| Illustration | Rxdb |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-14/R/Rxdb.png) | ![illustration for Rxdb](../../simpleicons-14/R/Rxdb.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$RxdbXs>`
- `<$RxdbSm>`
- `<$RxdbMd>`
- `<$RxdbLg>`





## Rxdb

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-14/bootstrap')

' loads the Item which embeds the element Rxdb
include('simpleicons-14/R/Rxdb')

' renders the element
Rxdb('Rxdb', 'Rxdb', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Rxdb
include('simpleicons-14/R/Rxdb')

' renders the element
Rxdb('Rxdb', 'Rxdb', 'an optional tech label', 'an optional description')
@enduml
```

