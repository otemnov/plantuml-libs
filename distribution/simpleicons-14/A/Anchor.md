# Anchor


```text
simpleicons-14/A/Anchor
```

```text
include('simpleicons-14/A/Anchor')
```



| Illustration | Anchor |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-14/A/Anchor.png) | ![illustration for Anchor](../../simpleicons-14/A/Anchor.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$AnchorXs>`
- `<$AnchorSm>`
- `<$AnchorMd>`
- `<$AnchorLg>`





## Anchor

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-14/bootstrap')

' loads the Item which embeds the element Anchor
include('simpleicons-14/A/Anchor')

' renders the element
Anchor('Anchor', 'Anchor', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Anchor
include('simpleicons-14/A/Anchor')

' renders the element
Anchor('Anchor', 'Anchor', 'an optional tech label', 'an optional description')
@enduml
```

