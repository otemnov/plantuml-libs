# Geeksforgeeks


```text
simpleicons-14/G/Geeksforgeeks
```

```text
include('simpleicons-14/G/Geeksforgeeks')
```



| Illustration | Geeksforgeeks |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-14/G/Geeksforgeeks.png) | ![illustration for Geeksforgeeks](../../simpleicons-14/G/Geeksforgeeks.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$GeeksforgeeksXs>`
- `<$GeeksforgeeksSm>`
- `<$GeeksforgeeksMd>`
- `<$GeeksforgeeksLg>`





## Geeksforgeeks

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-14/bootstrap')

' loads the Item which embeds the element Geeksforgeeks
include('simpleicons-14/G/Geeksforgeeks')

' renders the element
Geeksforgeeks('Geeksforgeeks', 'Geeksforgeeks', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Geeksforgeeks
include('simpleicons-14/G/Geeksforgeeks')

' renders the element
Geeksforgeeks('Geeksforgeeks', 'Geeksforgeeks', 'an optional tech label', 'an optional description')
@enduml
```

