# AmazonKendra


```text
aws-q1-2025/Architecture/ArtificialIntelligence/AmazonKendra
```

```text
include('aws-q1-2025/Architecture/ArtificialIntelligence/AmazonKendra')
```



| Illustration | AmazonKendra | AmazonKendraCard | AmazonKendraGroup |
| :---: | :---: | :---: | :---: |
| ![illustration for Illustration](../../../aws-q1-2025/Architecture/ArtificialIntelligence/AmazonKendra.png) | ![illustration for AmazonKendra](../../../aws-q1-2025/Architecture/ArtificialIntelligence/AmazonKendra.Local.png) | ![illustration for AmazonKendraCard](../../../aws-q1-2025/Architecture/ArtificialIntelligence/AmazonKendraCard.Local.png) | ![illustration for AmazonKendraGroup](../../../aws-q1-2025/Architecture/ArtificialIntelligence/AmazonKendraGroup.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$AmazonKendraXs>`
- `<$AmazonKendraSm>`
- `<$AmazonKendraMd>`
- `<$AmazonKendraLg>`





## AmazonKendra

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('aws-q1-2025/bootstrap')

' loads the Item which embeds the element AmazonKendra
include('aws-q1-2025/Architecture/ArtificialIntelligence/AmazonKendra')

' renders the element
AmazonKendra('AmazonKendra', 'Amazon Kendra', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element AmazonKendra
include('aws-q1-2025/Architecture/ArtificialIntelligence/AmazonKendra')

' renders the element
AmazonKendra('AmazonKendra', 'Amazon Kendra', 'an optional tech label', 'an optional description')
@enduml
```

## AmazonKendraCard

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('aws-q1-2025/bootstrap')

' loads the Item which embeds the element AmazonKendraCard
include('aws-q1-2025/Architecture/ArtificialIntelligence/AmazonKendra')

' renders the element
AmazonKendraCard('AmazonKendraCard', 'Amazon Kendra Card', 'an optional description')
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

' loads the Item which embeds the element AmazonKendraCard
include('aws-q1-2025/Architecture/ArtificialIntelligence/AmazonKendra')

' renders the element
AmazonKendraCard('AmazonKendraCard', 'Amazon Kendra Card', 'an optional description')
@enduml
```

## AmazonKendraGroup

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('aws-q1-2025/bootstrap')

' loads the Item which embeds the element AmazonKendraGroup
include('aws-q1-2025/Architecture/ArtificialIntelligence/AmazonKendra')

' renders the element
AmazonKendraGroup('AmazonKendraGroup', 'Amazon Kendra Group', 'an optional tech label') {
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

' loads the Item which embeds the element AmazonKendraGroup
include('aws-q1-2025/Architecture/ArtificialIntelligence/AmazonKendra')

' renders the element
AmazonKendraGroup('AmazonKendraGroup', 'Amazon Kendra Group', 'an optional tech label') {
    note as note
        the content of the group
    end note
}
@enduml
```

