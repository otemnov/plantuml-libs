# Springboot


```text
simpleicons-14/S/Springboot
```

```text
include('simpleicons-14/S/Springboot')
```



| Illustration | Springboot |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-14/S/Springboot.png) | ![illustration for Springboot](../../simpleicons-14/S/Springboot.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$SpringbootXs>`
- `<$SpringbootSm>`
- `<$SpringbootMd>`
- `<$SpringbootLg>`





## Springboot

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-14/bootstrap')

' loads the Item which embeds the element Springboot
include('simpleicons-14/S/Springboot')

' renders the element
Springboot('Springboot', 'Springboot', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Springboot
include('simpleicons-14/S/Springboot')

' renders the element
Springboot('Springboot', 'Springboot', 'an optional tech label', 'an optional description')
@enduml
```

