# Androidstudio


```text
simpleicons-14/A/Androidstudio
```

```text
include('simpleicons-14/A/Androidstudio')
```



| Illustration | Androidstudio |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-14/A/Androidstudio.png) | ![illustration for Androidstudio](../../simpleicons-14/A/Androidstudio.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$AndroidstudioXs>`
- `<$AndroidstudioSm>`
- `<$AndroidstudioMd>`
- `<$AndroidstudioLg>`





## Androidstudio

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-14/bootstrap')

' loads the Item which embeds the element Androidstudio
include('simpleicons-14/A/Androidstudio')

' renders the element
Androidstudio('Androidstudio', 'Androidstudio', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Androidstudio
include('simpleicons-14/A/Androidstudio')

' renders the element
Androidstudio('Androidstudio', 'Androidstudio', 'an optional tech label', 'an optional description')
@enduml
```

