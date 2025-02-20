# Suckless


```text
simpleicons-14/S/Suckless
```

```text
include('simpleicons-14/S/Suckless')
```



| Illustration | Suckless |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-14/S/Suckless.png) | ![illustration for Suckless](../../simpleicons-14/S/Suckless.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$SucklessXs>`
- `<$SucklessSm>`
- `<$SucklessMd>`
- `<$SucklessLg>`





## Suckless

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-14/bootstrap')

' loads the Item which embeds the element Suckless
include('simpleicons-14/S/Suckless')

' renders the element
Suckless('Suckless', 'Suckless', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Suckless
include('simpleicons-14/S/Suckless')

' renders the element
Suckless('Suckless', 'Suckless', 'an optional tech label', 'an optional description')
@enduml
```

