# Apostrophe


```text
simpleicons-14/A/Apostrophe
```

```text
include('simpleicons-14/A/Apostrophe')
```



| Illustration | Apostrophe |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-14/A/Apostrophe.png) | ![illustration for Apostrophe](../../simpleicons-14/A/Apostrophe.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$ApostropheXs>`
- `<$ApostropheSm>`
- `<$ApostropheMd>`
- `<$ApostropheLg>`





## Apostrophe

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-14/bootstrap')

' loads the Item which embeds the element Apostrophe
include('simpleicons-14/A/Apostrophe')

' renders the element
Apostrophe('Apostrophe', 'Apostrophe', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Apostrophe
include('simpleicons-14/A/Apostrophe')

' renders the element
Apostrophe('Apostrophe', 'Apostrophe', 'an optional tech label', 'an optional description')
@enduml
```

