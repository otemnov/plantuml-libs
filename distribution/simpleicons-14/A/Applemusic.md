# Applemusic


```text
simpleicons-14/A/Applemusic
```

```text
include('simpleicons-14/A/Applemusic')
```



| Illustration | Applemusic |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-14/A/Applemusic.png) | ![illustration for Applemusic](../../simpleicons-14/A/Applemusic.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$ApplemusicXs>`
- `<$ApplemusicSm>`
- `<$ApplemusicMd>`
- `<$ApplemusicLg>`





## Applemusic

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-14/bootstrap')

' loads the Item which embeds the element Applemusic
include('simpleicons-14/A/Applemusic')

' renders the element
Applemusic('Applemusic', 'Applemusic', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Applemusic
include('simpleicons-14/A/Applemusic')

' renders the element
Applemusic('Applemusic', 'Applemusic', 'an optional tech label', 'an optional description')
@enduml
```

