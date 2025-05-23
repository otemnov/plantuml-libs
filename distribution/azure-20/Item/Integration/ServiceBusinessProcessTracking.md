# ServiceBusinessProcessTracking


```text
azure-20/Item/Integration/ServiceBusinessProcessTracking
```

```text
include('azure-20/Item/Integration/ServiceBusinessProcessTracking')
```



| Illustration | ServiceBusinessProcessTracking | ServiceBusinessProcessTrackingCard | ServiceBusinessProcessTrackingGroup |
| :---: | :---: | :---: | :---: |
| ![illustration for Illustration](../../../azure-20/Item/Integration/ServiceBusinessProcessTracking.png) | ![illustration for ServiceBusinessProcessTracking](../../../azure-20/Item/Integration/ServiceBusinessProcessTracking.Local.png) | ![illustration for ServiceBusinessProcessTrackingCard](../../../azure-20/Item/Integration/ServiceBusinessProcessTrackingCard.Local.png) | ![illustration for ServiceBusinessProcessTrackingGroup](../../../azure-20/Item/Integration/ServiceBusinessProcessTrackingGroup.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$ServiceBusinessProcessTrackingXs>`
- `<$ServiceBusinessProcessTrackingSm>`
- `<$ServiceBusinessProcessTrackingMd>`
- `<$ServiceBusinessProcessTrackingLg>`





## ServiceBusinessProcessTracking

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('azure-20/bootstrap')

' loads the Item which embeds the element ServiceBusinessProcessTracking
include('azure-20/Item/Integration/ServiceBusinessProcessTracking')

' renders the element
ServiceBusinessProcessTracking('ServiceBusinessProcessTracking', 'Service Business Process Tracking', 'an optional tech label', 'an optional description')
@enduml
```

### Load locally
```plantuml
@startuml
' configures the library
!global $INCLUSION_MODE="local"
!global $LIB_BASE_LOCATION="../../.."

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('azure-20/bootstrap')

' loads the Item which embeds the element ServiceBusinessProcessTracking
include('azure-20/Item/Integration/ServiceBusinessProcessTracking')

' renders the element
ServiceBusinessProcessTracking('ServiceBusinessProcessTracking', 'Service Business Process Tracking', 'an optional tech label', 'an optional description')
@enduml
```

## ServiceBusinessProcessTrackingCard

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('azure-20/bootstrap')

' loads the Item which embeds the element ServiceBusinessProcessTrackingCard
include('azure-20/Item/Integration/ServiceBusinessProcessTracking')

' renders the element
ServiceBusinessProcessTrackingCard('ServiceBusinessProcessTrackingCard', 'Service Business Process Tracking Card', 'an optional description')
@enduml
```

### Load locally
```plantuml
@startuml
' configures the library
!global $INCLUSION_MODE="local"
!global $LIB_BASE_LOCATION="../../.."

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('azure-20/bootstrap')

' loads the Item which embeds the element ServiceBusinessProcessTrackingCard
include('azure-20/Item/Integration/ServiceBusinessProcessTracking')

' renders the element
ServiceBusinessProcessTrackingCard('ServiceBusinessProcessTrackingCard', 'Service Business Process Tracking Card', 'an optional description')
@enduml
```

## ServiceBusinessProcessTrackingGroup

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('azure-20/bootstrap')

' loads the Item which embeds the element ServiceBusinessProcessTrackingGroup
include('azure-20/Item/Integration/ServiceBusinessProcessTracking')

' renders the element
ServiceBusinessProcessTrackingGroup('ServiceBusinessProcessTrackingGroup', 'Service Business Process Tracking Group', 'an optional tech label') {
    note as note
        the content of the group
    end note
}
@enduml
```

### Load locally
```plantuml
@startuml
' configures the library
!global $INCLUSION_MODE="local"
!global $LIB_BASE_LOCATION="../../.."

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('azure-20/bootstrap')

' loads the Item which embeds the element ServiceBusinessProcessTrackingGroup
include('azure-20/Item/Integration/ServiceBusinessProcessTracking')

' renders the element
ServiceBusinessProcessTrackingGroup('ServiceBusinessProcessTrackingGroup', 'Service Business Process Tracking Group', 'an optional tech label') {
    note as note
        the content of the group
    end note
}
@enduml
```

