# Axios


```text
simpleicons-14/A/Axios
```

```text
include('simpleicons-14/A/Axios')
```



| Illustration | Axios |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-14/A/Axios.png) | ![illustration for Axios](../../simpleicons-14/A/Axios.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$AxiosXs>`
- `<$AxiosSm>`
- `<$AxiosMd>`
- `<$AxiosLg>`





## Axios

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-14/bootstrap')

' loads the Item which embeds the element Axios
include('simpleicons-14/A/Axios')

' renders the element
Axios('Axios', 'Axios', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Axios
include('simpleicons-14/A/Axios')

' renders the element
Axios('Axios', 'Axios', 'an optional tech label', 'an optional description')
@enduml
```

