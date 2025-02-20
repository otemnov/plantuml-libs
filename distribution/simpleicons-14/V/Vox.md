# Vox


```text
simpleicons-14/V/Vox
```

```text
include('simpleicons-14/V/Vox')
```



| Illustration | Vox |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-14/V/Vox.png) | ![illustration for Vox](../../simpleicons-14/V/Vox.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$VoxXs>`
- `<$VoxSm>`
- `<$VoxMd>`
- `<$VoxLg>`





## Vox

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-14/bootstrap')

' loads the Item which embeds the element Vox
include('simpleicons-14/V/Vox')

' renders the element
Vox('Vox', 'Vox', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Vox
include('simpleicons-14/V/Vox')

' renders the element
Vox('Vox', 'Vox', 'an optional tech label', 'an optional description')
@enduml
```

