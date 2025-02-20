# ServiceApplens


```text
azure-20/Item/AzureEcosystem/ServiceApplens
```

```text
include('azure-20/Item/AzureEcosystem/ServiceApplens')
```



| Illustration | ServiceApplens | ServiceApplensCard | ServiceApplensGroup |
| :---: | :---: | :---: | :---: |
| ![illustration for Illustration](../../../azure-20/Item/AzureEcosystem/ServiceApplens.png) | ![illustration for ServiceApplens](../../../azure-20/Item/AzureEcosystem/ServiceApplens.Local.png) | ![illustration for ServiceApplensCard](../../../azure-20/Item/AzureEcosystem/ServiceApplensCard.Local.png) | ![illustration for ServiceApplensGroup](../../../azure-20/Item/AzureEcosystem/ServiceApplensGroup.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$ServiceApplensXs>`
- `<$ServiceApplensSm>`
- `<$ServiceApplensMd>`
- `<$ServiceApplensLg>`





## ServiceApplens

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('azure-20/bootstrap')

' loads the Item which embeds the element ServiceApplens
include('azure-20/Item/AzureEcosystem/ServiceApplens')

' renders the element
ServiceApplens('ServiceApplens', 'Service Applens', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element ServiceApplens
include('azure-20/Item/AzureEcosystem/ServiceApplens')

' renders the element
ServiceApplens('ServiceApplens', 'Service Applens', 'an optional tech label', 'an optional description')
@enduml
```

## ServiceApplensCard

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('azure-20/bootstrap')

' loads the Item which embeds the element ServiceApplensCard
include('azure-20/Item/AzureEcosystem/ServiceApplens')

' renders the element
ServiceApplensCard('ServiceApplensCard', 'Service Applens Card', 'an optional description')
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

' loads the Item which embeds the element ServiceApplensCard
include('azure-20/Item/AzureEcosystem/ServiceApplens')

' renders the element
ServiceApplensCard('ServiceApplensCard', 'Service Applens Card', 'an optional description')
@enduml
```

## ServiceApplensGroup

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('azure-20/bootstrap')

' loads the Item which embeds the element ServiceApplensGroup
include('azure-20/Item/AzureEcosystem/ServiceApplens')

' renders the element
ServiceApplensGroup('ServiceApplensGroup', 'Service Applens Group', 'an optional tech label') {
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

' loads the Item which embeds the element ServiceApplensGroup
include('azure-20/Item/AzureEcosystem/ServiceApplens')

' renders the element
ServiceApplensGroup('ServiceApplensGroup', 'Service Applens Group', 'an optional tech label') {
    note as note
        the content of the group
    end note
}
@enduml
```

