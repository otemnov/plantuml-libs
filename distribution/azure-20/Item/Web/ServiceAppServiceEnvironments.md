# ServiceAppServiceEnvironments


```text
azure-20/Item/Web/ServiceAppServiceEnvironments
```

```text
include('azure-20/Item/Web/ServiceAppServiceEnvironments')
```



| Illustration | ServiceAppServiceEnvironments | ServiceAppServiceEnvironmentsCard | ServiceAppServiceEnvironmentsGroup |
| :---: | :---: | :---: | :---: |
| ![illustration for Illustration](../../../azure-20/Item/Web/ServiceAppServiceEnvironments.png) | ![illustration for ServiceAppServiceEnvironments](../../../azure-20/Item/Web/ServiceAppServiceEnvironments.Local.png) | ![illustration for ServiceAppServiceEnvironmentsCard](../../../azure-20/Item/Web/ServiceAppServiceEnvironmentsCard.Local.png) | ![illustration for ServiceAppServiceEnvironmentsGroup](../../../azure-20/Item/Web/ServiceAppServiceEnvironmentsGroup.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$ServiceAppServiceEnvironmentsXs>`
- `<$ServiceAppServiceEnvironmentsSm>`
- `<$ServiceAppServiceEnvironmentsMd>`
- `<$ServiceAppServiceEnvironmentsLg>`





## ServiceAppServiceEnvironments

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('azure-20/bootstrap')

' loads the Item which embeds the element ServiceAppServiceEnvironments
include('azure-20/Item/Web/ServiceAppServiceEnvironments')

' renders the element
ServiceAppServiceEnvironments('ServiceAppServiceEnvironments', 'Service App Service Environments', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element ServiceAppServiceEnvironments
include('azure-20/Item/Web/ServiceAppServiceEnvironments')

' renders the element
ServiceAppServiceEnvironments('ServiceAppServiceEnvironments', 'Service App Service Environments', 'an optional tech label', 'an optional description')
@enduml
```

## ServiceAppServiceEnvironmentsCard

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('azure-20/bootstrap')

' loads the Item which embeds the element ServiceAppServiceEnvironmentsCard
include('azure-20/Item/Web/ServiceAppServiceEnvironments')

' renders the element
ServiceAppServiceEnvironmentsCard('ServiceAppServiceEnvironmentsCard', 'Service App Service Environments Card', 'an optional description')
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

' loads the Item which embeds the element ServiceAppServiceEnvironmentsCard
include('azure-20/Item/Web/ServiceAppServiceEnvironments')

' renders the element
ServiceAppServiceEnvironmentsCard('ServiceAppServiceEnvironmentsCard', 'Service App Service Environments Card', 'an optional description')
@enduml
```

## ServiceAppServiceEnvironmentsGroup

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('azure-20/bootstrap')

' loads the Item which embeds the element ServiceAppServiceEnvironmentsGroup
include('azure-20/Item/Web/ServiceAppServiceEnvironments')

' renders the element
ServiceAppServiceEnvironmentsGroup('ServiceAppServiceEnvironmentsGroup', 'Service App Service Environments Group', 'an optional tech label') {
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

' loads the Item which embeds the element ServiceAppServiceEnvironmentsGroup
include('azure-20/Item/Web/ServiceAppServiceEnvironments')

' renders the element
ServiceAppServiceEnvironmentsGroup('ServiceAppServiceEnvironmentsGroup', 'Service App Service Environments Group', 'an optional tech label') {
    note as note
        the content of the group
    end note
}
@enduml
```

