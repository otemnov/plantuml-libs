# Icloud


```text
simpleicons-14/I/Icloud
```

```text
include('simpleicons-14/I/Icloud')
```



| Illustration | Icloud |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-14/I/Icloud.png) | ![illustration for Icloud](../../simpleicons-14/I/Icloud.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$IcloudXs>`
- `<$IcloudSm>`
- `<$IcloudMd>`
- `<$IcloudLg>`





## Icloud

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-14/bootstrap')

' loads the Item which embeds the element Icloud
include('simpleicons-14/I/Icloud')

' renders the element
Icloud('Icloud', 'Icloud', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Icloud
include('simpleicons-14/I/Icloud')

' renders the element
Icloud('Icloud', 'Icloud', 'an optional tech label', 'an optional description')
@enduml
```

