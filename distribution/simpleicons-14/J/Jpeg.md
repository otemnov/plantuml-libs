# Jpeg


```text
simpleicons-14/J/Jpeg
```

```text
include('simpleicons-14/J/Jpeg')
```



| Illustration | Jpeg |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-14/J/Jpeg.png) | ![illustration for Jpeg](../../simpleicons-14/J/Jpeg.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$JpegXs>`
- `<$JpegSm>`
- `<$JpegMd>`
- `<$JpegLg>`





## Jpeg

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-14/bootstrap')

' loads the Item which embeds the element Jpeg
include('simpleicons-14/J/Jpeg')

' renders the element
Jpeg('Jpeg', 'Jpeg', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Jpeg
include('simpleicons-14/J/Jpeg')

' renders the element
Jpeg('Jpeg', 'Jpeg', 'an optional tech label', 'an optional description')
@enduml
```

