# Ceph


```text
simpleicons-14/C/Ceph
```

```text
include('simpleicons-14/C/Ceph')
```



| Illustration | Ceph |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-14/C/Ceph.png) | ![illustration for Ceph](../../simpleicons-14/C/Ceph.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$CephXs>`
- `<$CephSm>`
- `<$CephMd>`
- `<$CephLg>`





## Ceph

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-14/bootstrap')

' loads the Item which embeds the element Ceph
include('simpleicons-14/C/Ceph')

' renders the element
Ceph('Ceph', 'Ceph', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Ceph
include('simpleicons-14/C/Ceph')

' renders the element
Ceph('Ceph', 'Ceph', 'an optional tech label', 'an optional description')
@enduml
```

