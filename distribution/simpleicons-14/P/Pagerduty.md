# Pagerduty


```text
simpleicons-14/P/Pagerduty
```

```text
include('simpleicons-14/P/Pagerduty')
```



| Illustration | Pagerduty |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-14/P/Pagerduty.png) | ![illustration for Pagerduty](../../simpleicons-14/P/Pagerduty.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$PagerdutyXs>`
- `<$PagerdutySm>`
- `<$PagerdutyMd>`
- `<$PagerdutyLg>`





## Pagerduty

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-14/bootstrap')

' loads the Item which embeds the element Pagerduty
include('simpleicons-14/P/Pagerduty')

' renders the element
Pagerduty('Pagerduty', 'Pagerduty', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Pagerduty
include('simpleicons-14/P/Pagerduty')

' renders the element
Pagerduty('Pagerduty', 'Pagerduty', 'an optional tech label', 'an optional description')
@enduml
```

