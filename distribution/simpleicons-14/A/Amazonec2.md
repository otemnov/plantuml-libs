# Amazonec2


```text
simpleicons-14/A/Amazonec2
```

```text
include('simpleicons-14/A/Amazonec2')
```



| Illustration | Amazonec2 |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-14/A/Amazonec2.png) | ![illustration for Amazonec2](../../simpleicons-14/A/Amazonec2.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$Amazonec2Xs>`
- `<$Amazonec2Sm>`
- `<$Amazonec2Md>`
- `<$Amazonec2Lg>`





## Amazonec2

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-14/bootstrap')

' loads the Item which embeds the element Amazonec2
include('simpleicons-14/A/Amazonec2')

' renders the element
Amazonec2('Amazonec2', 'Amazonec2', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Amazonec2
include('simpleicons-14/A/Amazonec2')

' renders the element
Amazonec2('Amazonec2', 'Amazonec2', 'an optional tech label', 'an optional description')
@enduml
```

