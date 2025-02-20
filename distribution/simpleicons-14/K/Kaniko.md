# Kaniko


```text
simpleicons-14/K/Kaniko
```

```text
include('simpleicons-14/K/Kaniko')
```



| Illustration | Kaniko |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-14/K/Kaniko.png) | ![illustration for Kaniko](../../simpleicons-14/K/Kaniko.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$KanikoXs>`
- `<$KanikoSm>`
- `<$KanikoMd>`
- `<$KanikoLg>`





## Kaniko

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-14/bootstrap')

' loads the Item which embeds the element Kaniko
include('simpleicons-14/K/Kaniko')

' renders the element
Kaniko('Kaniko', 'Kaniko', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Kaniko
include('simpleicons-14/K/Kaniko')

' renders the element
Kaniko('Kaniko', 'Kaniko', 'an optional tech label', 'an optional description')
@enduml
```

