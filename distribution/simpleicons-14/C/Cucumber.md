# Cucumber


```text
simpleicons-14/C/Cucumber
```

```text
include('simpleicons-14/C/Cucumber')
```



| Illustration | Cucumber |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-14/C/Cucumber.png) | ![illustration for Cucumber](../../simpleicons-14/C/Cucumber.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$CucumberXs>`
- `<$CucumberSm>`
- `<$CucumberMd>`
- `<$CucumberLg>`





## Cucumber

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-14/bootstrap')

' loads the Item which embeds the element Cucumber
include('simpleicons-14/C/Cucumber')

' renders the element
Cucumber('Cucumber', 'Cucumber', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Cucumber
include('simpleicons-14/C/Cucumber')

' renders the element
Cucumber('Cucumber', 'Cucumber', 'an optional tech label', 'an optional description')
@enduml
```

