# Microsoftazure


```text
simpleicons-14/M/Microsoftazure
```

```text
include('simpleicons-14/M/Microsoftazure')
```



| Illustration | Microsoftazure |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-14/M/Microsoftazure.png) | ![illustration for Microsoftazure](../../simpleicons-14/M/Microsoftazure.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$MicrosoftazureXs>`
- `<$MicrosoftazureSm>`
- `<$MicrosoftazureMd>`
- `<$MicrosoftazureLg>`





## Microsoftazure

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-14/bootstrap')

' loads the Item which embeds the element Microsoftazure
include('simpleicons-14/M/Microsoftazure')

' renders the element
Microsoftazure('Microsoftazure', 'Microsoftazure', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Microsoftazure
include('simpleicons-14/M/Microsoftazure')

' renders the element
Microsoftazure('Microsoftazure', 'Microsoftazure', 'an optional tech label', 'an optional description')
@enduml
```

