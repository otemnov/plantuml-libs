# Preact


```text
simpleicons-14/P/Preact
```

```text
include('simpleicons-14/P/Preact')
```



| Illustration | Preact |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-14/P/Preact.png) | ![illustration for Preact](../../simpleicons-14/P/Preact.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$PreactXs>`
- `<$PreactSm>`
- `<$PreactMd>`
- `<$PreactLg>`





## Preact

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-14/bootstrap')

' loads the Item which embeds the element Preact
include('simpleicons-14/P/Preact')

' renders the element
Preact('Preact', 'Preact', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Preact
include('simpleicons-14/P/Preact')

' renders the element
Preact('Preact', 'Preact', 'an optional tech label', 'an optional description')
@enduml
```

