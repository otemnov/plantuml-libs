# Phpstorm


```text
simpleicons-14/P/Phpstorm
```

```text
include('simpleicons-14/P/Phpstorm')
```



| Illustration | Phpstorm |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-14/P/Phpstorm.png) | ![illustration for Phpstorm](../../simpleicons-14/P/Phpstorm.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$PhpstormXs>`
- `<$PhpstormSm>`
- `<$PhpstormMd>`
- `<$PhpstormLg>`





## Phpstorm

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-14/bootstrap')

' loads the Item which embeds the element Phpstorm
include('simpleicons-14/P/Phpstorm')

' renders the element
Phpstorm('Phpstorm', 'Phpstorm', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Phpstorm
include('simpleicons-14/P/Phpstorm')

' renders the element
Phpstorm('Phpstorm', 'Phpstorm', 'an optional tech label', 'an optional description')
@enduml
```

