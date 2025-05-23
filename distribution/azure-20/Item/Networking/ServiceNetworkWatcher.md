# ServiceNetworkWatcher


```text
azure-20/Item/Networking/ServiceNetworkWatcher
```

```text
include('azure-20/Item/Networking/ServiceNetworkWatcher')
```



| Illustration | ServiceNetworkWatcher | ServiceNetworkWatcherCard | ServiceNetworkWatcherGroup |
| :---: | :---: | :---: | :---: |
| ![illustration for Illustration](../../../azure-20/Item/Networking/ServiceNetworkWatcher.png) | ![illustration for ServiceNetworkWatcher](../../../azure-20/Item/Networking/ServiceNetworkWatcher.Local.png) | ![illustration for ServiceNetworkWatcherCard](../../../azure-20/Item/Networking/ServiceNetworkWatcherCard.Local.png) | ![illustration for ServiceNetworkWatcherGroup](../../../azure-20/Item/Networking/ServiceNetworkWatcherGroup.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$ServiceNetworkWatcherXs>`
- `<$ServiceNetworkWatcherSm>`
- `<$ServiceNetworkWatcherMd>`
- `<$ServiceNetworkWatcherLg>`





## ServiceNetworkWatcher

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('azure-20/bootstrap')

' loads the Item which embeds the element ServiceNetworkWatcher
include('azure-20/Item/Networking/ServiceNetworkWatcher')

' renders the element
ServiceNetworkWatcher('ServiceNetworkWatcher', 'Service Network Watcher', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element ServiceNetworkWatcher
include('azure-20/Item/Networking/ServiceNetworkWatcher')

' renders the element
ServiceNetworkWatcher('ServiceNetworkWatcher', 'Service Network Watcher', 'an optional tech label', 'an optional description')
@enduml
```

## ServiceNetworkWatcherCard

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('azure-20/bootstrap')

' loads the Item which embeds the element ServiceNetworkWatcherCard
include('azure-20/Item/Networking/ServiceNetworkWatcher')

' renders the element
ServiceNetworkWatcherCard('ServiceNetworkWatcherCard', 'Service Network Watcher Card', 'an optional description')
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

' loads the Item which embeds the element ServiceNetworkWatcherCard
include('azure-20/Item/Networking/ServiceNetworkWatcher')

' renders the element
ServiceNetworkWatcherCard('ServiceNetworkWatcherCard', 'Service Network Watcher Card', 'an optional description')
@enduml
```

## ServiceNetworkWatcherGroup

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('azure-20/bootstrap')

' loads the Item which embeds the element ServiceNetworkWatcherGroup
include('azure-20/Item/Networking/ServiceNetworkWatcher')

' renders the element
ServiceNetworkWatcherGroup('ServiceNetworkWatcherGroup', 'Service Network Watcher Group', 'an optional tech label') {
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

' loads the Item which embeds the element ServiceNetworkWatcherGroup
include('azure-20/Item/Networking/ServiceNetworkWatcher')

' renders the element
ServiceNetworkWatcherGroup('ServiceNetworkWatcherGroup', 'Service Network Watcher Group', 'an optional tech label') {
    note as note
        the content of the group
    end note
}
@enduml
```

