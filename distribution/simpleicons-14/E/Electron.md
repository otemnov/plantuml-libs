# Electron


```text
simpleicons-14/E/Electron
```

```text
include('simpleicons-14/E/Electron')
```



| Illustration | Electron |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-14/E/Electron.png) | ![illustration for Electron](../../simpleicons-14/E/Electron.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$ElectronXs>`
- `<$ElectronSm>`
- `<$ElectronMd>`
- `<$ElectronLg>`





## Electron

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-14/bootstrap')

' loads the Item which embeds the element Electron
include('simpleicons-14/E/Electron')

' renders the element
Electron('Electron', 'Electron', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Electron
include('simpleicons-14/E/Electron')

' renders the element
Electron('Electron', 'Electron', 'an optional tech label', 'an optional description')
@enduml
```

