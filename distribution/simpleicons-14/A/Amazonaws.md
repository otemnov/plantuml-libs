# Amazonaws


```text
simpleicons-14/A/Amazonaws
```

```text
include('simpleicons-14/A/Amazonaws')
```



| Illustration | Amazonaws |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-14/A/Amazonaws.png) | ![illustration for Amazonaws](../../simpleicons-14/A/Amazonaws.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$AmazonawsXs>`
- `<$AmazonawsSm>`
- `<$AmazonawsMd>`
- `<$AmazonawsLg>`





## Amazonaws

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-14/bootstrap')

' loads the Item which embeds the element Amazonaws
include('simpleicons-14/A/Amazonaws')

' renders the element
Amazonaws('Amazonaws', 'Amazonaws', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Amazonaws
include('simpleicons-14/A/Amazonaws')

' renders the element
Amazonaws('Amazonaws', 'Amazonaws', 'an optional tech label', 'an optional description')
@enduml
```

