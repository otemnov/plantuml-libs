# Cloudflare


```text
simpleicons-14/C/Cloudflare
```

```text
include('simpleicons-14/C/Cloudflare')
```



| Illustration | Cloudflare |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-14/C/Cloudflare.png) | ![illustration for Cloudflare](../../simpleicons-14/C/Cloudflare.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$CloudflareXs>`
- `<$CloudflareSm>`
- `<$CloudflareMd>`
- `<$CloudflareLg>`





## Cloudflare

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-14/bootstrap')

' loads the Item which embeds the element Cloudflare
include('simpleicons-14/C/Cloudflare')

' renders the element
Cloudflare('Cloudflare', 'Cloudflare', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Cloudflare
include('simpleicons-14/C/Cloudflare')

' renders the element
Cloudflare('Cloudflare', 'Cloudflare', 'an optional tech label', 'an optional description')
@enduml
```

