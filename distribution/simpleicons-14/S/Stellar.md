# Stellar


```text
simpleicons-14/S/Stellar
```

```text
include('simpleicons-14/S/Stellar')
```



| Illustration | Stellar |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-14/S/Stellar.png) | ![illustration for Stellar](../../simpleicons-14/S/Stellar.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$StellarXs>`
- `<$StellarSm>`
- `<$StellarMd>`
- `<$StellarLg>`





## Stellar

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-14/bootstrap')

' loads the Item which embeds the element Stellar
include('simpleicons-14/S/Stellar')

' renders the element
Stellar('Stellar', 'Stellar', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Stellar
include('simpleicons-14/S/Stellar')

' renders the element
Stellar('Stellar', 'Stellar', 'an optional tech label', 'an optional description')
@enduml
```

