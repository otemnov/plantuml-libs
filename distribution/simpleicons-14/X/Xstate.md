# Xstate


```text
simpleicons-14/X/Xstate
```

```text
include('simpleicons-14/X/Xstate')
```



| Illustration | Xstate |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-14/X/Xstate.png) | ![illustration for Xstate](../../simpleicons-14/X/Xstate.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$XstateXs>`
- `<$XstateSm>`
- `<$XstateMd>`
- `<$XstateLg>`





## Xstate

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-14/bootstrap')

' loads the Item which embeds the element Xstate
include('simpleicons-14/X/Xstate')

' renders the element
Xstate('Xstate', 'Xstate', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Xstate
include('simpleicons-14/X/Xstate')

' renders the element
Xstate('Xstate', 'Xstate', 'an optional tech label', 'an optional description')
@enduml
```

