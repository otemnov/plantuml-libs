# Canva


```text
simpleicons-14/C/Canva
```

```text
include('simpleicons-14/C/Canva')
```



| Illustration | Canva |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-14/C/Canva.png) | ![illustration for Canva](../../simpleicons-14/C/Canva.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$CanvaXs>`
- `<$CanvaSm>`
- `<$CanvaMd>`
- `<$CanvaLg>`





## Canva

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-14/bootstrap')

' loads the Item which embeds the element Canva
include('simpleicons-14/C/Canva')

' renders the element
Canva('Canva', 'Canva', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Canva
include('simpleicons-14/C/Canva')

' renders the element
Canva('Canva', 'Canva', 'an optional tech label', 'an optional description')
@enduml
```

