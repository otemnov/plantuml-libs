# Heroku


```text
simpleicons-14/H/Heroku
```

```text
include('simpleicons-14/H/Heroku')
```



| Illustration | Heroku |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-14/H/Heroku.png) | ![illustration for Heroku](../../simpleicons-14/H/Heroku.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$HerokuXs>`
- `<$HerokuSm>`
- `<$HerokuMd>`
- `<$HerokuLg>`





## Heroku

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-14/bootstrap')

' loads the Item which embeds the element Heroku
include('simpleicons-14/H/Heroku')

' renders the element
Heroku('Heroku', 'Heroku', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Heroku
include('simpleicons-14/H/Heroku')

' renders the element
Heroku('Heroku', 'Heroku', 'an optional tech label', 'an optional description')
@enduml
```

