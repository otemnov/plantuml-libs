# Semanticscholar


```text
simpleicons-14/S/Semanticscholar
```

```text
include('simpleicons-14/S/Semanticscholar')
```



| Illustration | Semanticscholar |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-14/S/Semanticscholar.png) | ![illustration for Semanticscholar](../../simpleicons-14/S/Semanticscholar.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$SemanticscholarXs>`
- `<$SemanticscholarSm>`
- `<$SemanticscholarMd>`
- `<$SemanticscholarLg>`





## Semanticscholar

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-14/bootstrap')

' loads the Item which embeds the element Semanticscholar
include('simpleicons-14/S/Semanticscholar')

' renders the element
Semanticscholar('Semanticscholar', 'Semanticscholar', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Semanticscholar
include('simpleicons-14/S/Semanticscholar')

' renders the element
Semanticscholar('Semanticscholar', 'Semanticscholar', 'an optional tech label', 'an optional description')
@enduml
```

