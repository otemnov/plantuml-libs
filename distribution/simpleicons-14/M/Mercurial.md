# Mercurial


```text
simpleicons-14/M/Mercurial
```

```text
include('simpleicons-14/M/Mercurial')
```



| Illustration | Mercurial |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-14/M/Mercurial.png) | ![illustration for Mercurial](../../simpleicons-14/M/Mercurial.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$MercurialXs>`
- `<$MercurialSm>`
- `<$MercurialMd>`
- `<$MercurialLg>`





## Mercurial

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-14/bootstrap')

' loads the Item which embeds the element Mercurial
include('simpleicons-14/M/Mercurial')

' renders the element
Mercurial('Mercurial', 'Mercurial', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Mercurial
include('simpleicons-14/M/Mercurial')

' renders the element
Mercurial('Mercurial', 'Mercurial', 'an optional tech label', 'an optional description')
@enduml
```

