# AwsMainframeModernization


```text
aws-q1-2025/Architecture/MigrationModernization/AwsMainframeModernization
```

```text
include('aws-q1-2025/Architecture/MigrationModernization/AwsMainframeModernization')
```



| Illustration | AwsMainframeModernization | AwsMainframeModernizationCard | AwsMainframeModernizationGroup |
| :---: | :---: | :---: | :---: |
| ![illustration for Illustration](../../../aws-q1-2025/Architecture/MigrationModernization/AwsMainframeModernization.png) | ![illustration for AwsMainframeModernization](../../../aws-q1-2025/Architecture/MigrationModernization/AwsMainframeModernization.Local.png) | ![illustration for AwsMainframeModernizationCard](../../../aws-q1-2025/Architecture/MigrationModernization/AwsMainframeModernizationCard.Local.png) | ![illustration for AwsMainframeModernizationGroup](../../../aws-q1-2025/Architecture/MigrationModernization/AwsMainframeModernizationGroup.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$AwsMainframeModernizationXs>`
- `<$AwsMainframeModernizationSm>`
- `<$AwsMainframeModernizationMd>`
- `<$AwsMainframeModernizationLg>`





## AwsMainframeModernization

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('aws-q1-2025/bootstrap')

' loads the Item which embeds the element AwsMainframeModernization
include('aws-q1-2025/Architecture/MigrationModernization/AwsMainframeModernization')

' renders the element
AwsMainframeModernization('AwsMainframeModernization', 'Aws Mainframe Modernization', 'an optional tech label', 'an optional description')
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
include('aws-q1-2025/bootstrap')

' loads the Item which embeds the element AwsMainframeModernization
include('aws-q1-2025/Architecture/MigrationModernization/AwsMainframeModernization')

' renders the element
AwsMainframeModernization('AwsMainframeModernization', 'Aws Mainframe Modernization', 'an optional tech label', 'an optional description')
@enduml
```

## AwsMainframeModernizationCard

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('aws-q1-2025/bootstrap')

' loads the Item which embeds the element AwsMainframeModernizationCard
include('aws-q1-2025/Architecture/MigrationModernization/AwsMainframeModernization')

' renders the element
AwsMainframeModernizationCard('AwsMainframeModernizationCard', 'Aws Mainframe Modernization Card', 'an optional description')
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
include('aws-q1-2025/bootstrap')

' loads the Item which embeds the element AwsMainframeModernizationCard
include('aws-q1-2025/Architecture/MigrationModernization/AwsMainframeModernization')

' renders the element
AwsMainframeModernizationCard('AwsMainframeModernizationCard', 'Aws Mainframe Modernization Card', 'an optional description')
@enduml
```

## AwsMainframeModernizationGroup

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('aws-q1-2025/bootstrap')

' loads the Item which embeds the element AwsMainframeModernizationGroup
include('aws-q1-2025/Architecture/MigrationModernization/AwsMainframeModernization')

' renders the element
AwsMainframeModernizationGroup('AwsMainframeModernizationGroup', 'Aws Mainframe Modernization Group', 'an optional tech label') {
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
include('aws-q1-2025/bootstrap')

' loads the Item which embeds the element AwsMainframeModernizationGroup
include('aws-q1-2025/Architecture/MigrationModernization/AwsMainframeModernization')

' renders the element
AwsMainframeModernizationGroup('AwsMainframeModernizationGroup', 'Aws Mainframe Modernization Group', 'an optional tech label') {
    note as note
        the content of the group
    end note
}
@enduml
```

