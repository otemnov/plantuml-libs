# Mysql


```text
simpleicons-14/M/Mysql
```

```text
include('simpleicons-14/M/Mysql')
```



| Illustration | Mysql |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-14/M/Mysql.png) | ![illustration for Mysql](../../simpleicons-14/M/Mysql.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$MysqlXs>`
- `<$MysqlSm>`
- `<$MysqlMd>`
- `<$MysqlLg>`





## Mysql

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-14/bootstrap')

' loads the Item which embeds the element Mysql
include('simpleicons-14/M/Mysql')

' renders the element
Mysql('Mysql', 'Mysql', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Mysql
include('simpleicons-14/M/Mysql')

' renders the element
Mysql('Mysql', 'Mysql', 'an optional tech label', 'an optional description')
@enduml
```

