# Ibeacon


```text
simpleicons-14/I/Ibeacon
```

```text
include('simpleicons-14/I/Ibeacon')
```



| Illustration | Ibeacon |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-14/I/Ibeacon.png) | ![illustration for Ibeacon](../../simpleicons-14/I/Ibeacon.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$IbeaconXs>`
- `<$IbeaconSm>`
- `<$IbeaconMd>`
- `<$IbeaconLg>`





## Ibeacon

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-14/bootstrap')

' loads the Item which embeds the element Ibeacon
include('simpleicons-14/I/Ibeacon')

' renders the element
Ibeacon('Ibeacon', 'Ibeacon', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Ibeacon
include('simpleicons-14/I/Ibeacon')

' renders the element
Ibeacon('Ibeacon', 'Ibeacon', 'an optional tech label', 'an optional description')
@enduml
```

