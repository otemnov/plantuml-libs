# Task


```text
simpleicons-14/T/Task
```

```text
include('simpleicons-14/T/Task')
```



| Illustration | Task |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-14/T/Task.png) | ![illustration for Task](../../simpleicons-14/T/Task.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$TaskXs>`
- `<$TaskSm>`
- `<$TaskMd>`
- `<$TaskLg>`





## Task

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-14/bootstrap')

' loads the Item which embeds the element Task
include('simpleicons-14/T/Task')

' renders the element
Task('Task', 'Task', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Task
include('simpleicons-14/T/Task')

' renders the element
Task('Task', 'Task', 'an optional tech label', 'an optional description')
@enduml
```

