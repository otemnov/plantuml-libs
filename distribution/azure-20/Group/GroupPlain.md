# GroupPlain


```text
azure-20/Group/GroupPlain
```

```text
include('azure-20/Group/GroupPlain')
```



| GroupPlain |
| :---: |
| ![illustration for GroupPlain](../../azure-20/Group/GroupPlain.Local.png) |







## GroupPlain

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('azure-20/bootstrap')

' loads the Item which embeds the element GroupPlain
include('azure-20/Group/GroupPlain')

GroupPlain('GroupPlain', 'Group Plain', 'an optional tech label') {
  note as note
  the content of the boundary
  end note
}
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
include('azure-20/bootstrap')

' loads the Item which embeds the element GroupPlain
include('azure-20/Group/GroupPlain')

GroupPlain('GroupPlain', 'Group Plain', 'an optional tech label') {
  note as note
  the content of the boundary
  end note
}
@enduml
```

