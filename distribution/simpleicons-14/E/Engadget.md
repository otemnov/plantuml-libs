# Engadget


```text
simpleicons-14/E/Engadget
```

```text
include('simpleicons-14/E/Engadget')
```



| Illustration | Engadget |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-14/E/Engadget.png) | ![illustration for Engadget](../../simpleicons-14/E/Engadget.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$EngadgetXs>`
- `<$EngadgetSm>`
- `<$EngadgetMd>`
- `<$EngadgetLg>`





## Engadget

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-14/bootstrap')

' loads the Item which embeds the element Engadget
include('simpleicons-14/E/Engadget')

' renders the element
Engadget('Engadget', 'Engadget', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Engadget
include('simpleicons-14/E/Engadget')

' renders the element
Engadget('Engadget', 'Engadget', 'an optional tech label', 'an optional description')
@enduml
```

