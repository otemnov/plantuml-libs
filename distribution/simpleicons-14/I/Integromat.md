# Integromat


```text
simpleicons-14/I/Integromat
```

```text
include('simpleicons-14/I/Integromat')
```



| Illustration | Integromat |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-14/I/Integromat.png) | ![illustration for Integromat](../../simpleicons-14/I/Integromat.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$IntegromatXs>`
- `<$IntegromatSm>`
- `<$IntegromatMd>`
- `<$IntegromatLg>`





## Integromat

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-14/bootstrap')

' loads the Item which embeds the element Integromat
include('simpleicons-14/I/Integromat')

' renders the element
Integromat('Integromat', 'Integromat', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Integromat
include('simpleicons-14/I/Integromat')

' renders the element
Integromat('Integromat', 'Integromat', 'an optional tech label', 'an optional description')
@enduml
```

