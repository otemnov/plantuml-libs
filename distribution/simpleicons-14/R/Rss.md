# Rss


```text
simpleicons-14/R/Rss
```

```text
include('simpleicons-14/R/Rss')
```



| Illustration | Rss |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-14/R/Rss.png) | ![illustration for Rss](../../simpleicons-14/R/Rss.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$RssXs>`
- `<$RssSm>`
- `<$RssMd>`
- `<$RssLg>`





## Rss

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-14/bootstrap')

' loads the Item which embeds the element Rss
include('simpleicons-14/R/Rss')

' renders the element
Rss('Rss', 'Rss', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Rss
include('simpleicons-14/R/Rss')

' renders the element
Rss('Rss', 'Rss', 'an optional tech label', 'an optional description')
@enduml
```

