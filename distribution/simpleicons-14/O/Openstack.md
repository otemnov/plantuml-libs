# Openstack


```text
simpleicons-14/O/Openstack
```

```text
include('simpleicons-14/O/Openstack')
```



| Illustration | Openstack |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-14/O/Openstack.png) | ![illustration for Openstack](../../simpleicons-14/O/Openstack.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$OpenstackXs>`
- `<$OpenstackSm>`
- `<$OpenstackMd>`
- `<$OpenstackLg>`





## Openstack

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-14/bootstrap')

' loads the Item which embeds the element Openstack
include('simpleicons-14/O/Openstack')

' renders the element
Openstack('Openstack', 'Openstack', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Openstack
include('simpleicons-14/O/Openstack')

' renders the element
Openstack('Openstack', 'Openstack', 'an optional tech label', 'an optional description')
@enduml
```

