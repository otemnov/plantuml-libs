# Letterboxd


```text
simpleicons-14/L/Letterboxd
```

```text
include('simpleicons-14/L/Letterboxd')
```



| Illustration | Letterboxd |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-14/L/Letterboxd.png) | ![illustration for Letterboxd](../../simpleicons-14/L/Letterboxd.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$LetterboxdXs>`
- `<$LetterboxdSm>`
- `<$LetterboxdMd>`
- `<$LetterboxdLg>`





## Letterboxd

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-14/bootstrap')

' loads the Item which embeds the element Letterboxd
include('simpleicons-14/L/Letterboxd')

' renders the element
Letterboxd('Letterboxd', 'Letterboxd', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Letterboxd
include('simpleicons-14/L/Letterboxd')

' renders the element
Letterboxd('Letterboxd', 'Letterboxd', 'an optional tech label', 'an optional description')
@enduml
```

