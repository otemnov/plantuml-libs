# Harbor


```text
simpleicons-14/H/Harbor
```

```text
include('simpleicons-14/H/Harbor')
```



| Illustration | Harbor |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-14/H/Harbor.png) | ![illustration for Harbor](../../simpleicons-14/H/Harbor.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$HarborXs>`
- `<$HarborSm>`
- `<$HarborMd>`
- `<$HarborLg>`





## Harbor

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-14/bootstrap')

' loads the Item which embeds the element Harbor
include('simpleicons-14/H/Harbor')

' renders the element
Harbor('Harbor', 'Harbor', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Harbor
include('simpleicons-14/H/Harbor')

' renders the element
Harbor('Harbor', 'Harbor', 'an optional tech label', 'an optional description')
@enduml
```

