# Foodpanda


```text
simpleicons-14/F/Foodpanda
```

```text
include('simpleicons-14/F/Foodpanda')
```



| Illustration | Foodpanda |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-14/F/Foodpanda.png) | ![illustration for Foodpanda](../../simpleicons-14/F/Foodpanda.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$FoodpandaXs>`
- `<$FoodpandaSm>`
- `<$FoodpandaMd>`
- `<$FoodpandaLg>`





## Foodpanda

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-14/bootstrap')

' loads the Item which embeds the element Foodpanda
include('simpleicons-14/F/Foodpanda')

' renders the element
Foodpanda('Foodpanda', 'Foodpanda', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Foodpanda
include('simpleicons-14/F/Foodpanda')

' renders the element
Foodpanda('Foodpanda', 'Foodpanda', 'an optional tech label', 'an optional description')
@enduml
```

