# Openzeppelin


```text
simpleicons-14/O/Openzeppelin
```

```text
include('simpleicons-14/O/Openzeppelin')
```



| Illustration | Openzeppelin |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-14/O/Openzeppelin.png) | ![illustration for Openzeppelin](../../simpleicons-14/O/Openzeppelin.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$OpenzeppelinXs>`
- `<$OpenzeppelinSm>`
- `<$OpenzeppelinMd>`
- `<$OpenzeppelinLg>`





## Openzeppelin

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-14/bootstrap')

' loads the Item which embeds the element Openzeppelin
include('simpleicons-14/O/Openzeppelin')

' renders the element
Openzeppelin('Openzeppelin', 'Openzeppelin', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Openzeppelin
include('simpleicons-14/O/Openzeppelin')

' renders the element
Openzeppelin('Openzeppelin', 'Openzeppelin', 'an optional tech label', 'an optional description')
@enduml
```

