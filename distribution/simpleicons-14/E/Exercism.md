# Exercism


```text
simpleicons-14/E/Exercism
```

```text
include('simpleicons-14/E/Exercism')
```



| Illustration | Exercism |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-14/E/Exercism.png) | ![illustration for Exercism](../../simpleicons-14/E/Exercism.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$ExercismXs>`
- `<$ExercismSm>`
- `<$ExercismMd>`
- `<$ExercismLg>`





## Exercism

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-14/bootstrap')

' loads the Item which embeds the element Exercism
include('simpleicons-14/E/Exercism')

' renders the element
Exercism('Exercism', 'Exercism', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Exercism
include('simpleicons-14/E/Exercism')

' renders the element
Exercism('Exercism', 'Exercism', 'an optional tech label', 'an optional description')
@enduml
```

