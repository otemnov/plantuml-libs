# Argo


```text
simpleicons-14/A/Argo
```

```text
include('simpleicons-14/A/Argo')
```



| Illustration | Argo |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-14/A/Argo.png) | ![illustration for Argo](../../simpleicons-14/A/Argo.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$ArgoXs>`
- `<$ArgoSm>`
- `<$ArgoMd>`
- `<$ArgoLg>`





## Argo

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-14/bootstrap')

' loads the Item which embeds the element Argo
include('simpleicons-14/A/Argo')

' renders the element
Argo('Argo', 'Argo', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Argo
include('simpleicons-14/A/Argo')

' renders the element
Argo('Argo', 'Argo', 'an optional tech label', 'an optional description')
@enduml
```

