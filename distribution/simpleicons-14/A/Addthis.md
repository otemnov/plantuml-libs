# Addthis


```text
simpleicons-14/A/Addthis
```

```text
include('simpleicons-14/A/Addthis')
```



| Illustration | Addthis |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-14/A/Addthis.png) | ![illustration for Addthis](../../simpleicons-14/A/Addthis.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$AddthisXs>`
- `<$AddthisSm>`
- `<$AddthisMd>`
- `<$AddthisLg>`





## Addthis

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-14/bootstrap')

' loads the Item which embeds the element Addthis
include('simpleicons-14/A/Addthis')

' renders the element
Addthis('Addthis', 'Addthis', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Addthis
include('simpleicons-14/A/Addthis')

' renders the element
Addthis('Addthis', 'Addthis', 'an optional tech label', 'an optional description')
@enduml
```

