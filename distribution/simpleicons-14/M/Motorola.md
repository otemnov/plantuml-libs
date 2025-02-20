# Motorola


```text
simpleicons-14/M/Motorola
```

```text
include('simpleicons-14/M/Motorola')
```



| Illustration | Motorola |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-14/M/Motorola.png) | ![illustration for Motorola](../../simpleicons-14/M/Motorola.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$MotorolaXs>`
- `<$MotorolaSm>`
- `<$MotorolaMd>`
- `<$MotorolaLg>`





## Motorola

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-14/bootstrap')

' loads the Item which embeds the element Motorola
include('simpleicons-14/M/Motorola')

' renders the element
Motorola('Motorola', 'Motorola', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Motorola
include('simpleicons-14/M/Motorola')

' renders the element
Motorola('Motorola', 'Motorola', 'an optional tech label', 'an optional description')
@enduml
```

