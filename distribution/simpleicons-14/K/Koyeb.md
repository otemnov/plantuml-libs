# Koyeb


```text
simpleicons-14/K/Koyeb
```

```text
include('simpleicons-14/K/Koyeb')
```



| Illustration | Koyeb |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-14/K/Koyeb.png) | ![illustration for Koyeb](../../simpleicons-14/K/Koyeb.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$KoyebXs>`
- `<$KoyebSm>`
- `<$KoyebMd>`
- `<$KoyebLg>`





## Koyeb

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-14/bootstrap')

' loads the Item which embeds the element Koyeb
include('simpleicons-14/K/Koyeb')

' renders the element
Koyeb('Koyeb', 'Koyeb', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Koyeb
include('simpleicons-14/K/Koyeb')

' renders the element
Koyeb('Koyeb', 'Koyeb', 'an optional tech label', 'an optional description')
@enduml
```

