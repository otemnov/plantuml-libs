# Openid


```text
simpleicons-14/O/Openid
```

```text
include('simpleicons-14/O/Openid')
```



| Illustration | Openid |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-14/O/Openid.png) | ![illustration for Openid](../../simpleicons-14/O/Openid.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$OpenidXs>`
- `<$OpenidSm>`
- `<$OpenidMd>`
- `<$OpenidLg>`





## Openid

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-14/bootstrap')

' loads the Item which embeds the element Openid
include('simpleicons-14/O/Openid')

' renders the element
Openid('Openid', 'Openid', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Openid
include('simpleicons-14/O/Openid')

' renders the element
Openid('Openid', 'Openid', 'an optional tech label', 'an optional description')
@enduml
```

