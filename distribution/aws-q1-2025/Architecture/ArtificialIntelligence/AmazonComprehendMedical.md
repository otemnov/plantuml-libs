# AmazonComprehendMedical


```text
aws-q1-2025/Architecture/ArtificialIntelligence/AmazonComprehendMedical
```

```text
include('aws-q1-2025/Architecture/ArtificialIntelligence/AmazonComprehendMedical')
```



| Illustration | AmazonComprehendMedical | AmazonComprehendMedicalCard | AmazonComprehendMedicalGroup |
| :---: | :---: | :---: | :---: |
| ![illustration for Illustration](../../../aws-q1-2025/Architecture/ArtificialIntelligence/AmazonComprehendMedical.png) | ![illustration for AmazonComprehendMedical](../../../aws-q1-2025/Architecture/ArtificialIntelligence/AmazonComprehendMedical.Local.png) | ![illustration for AmazonComprehendMedicalCard](../../../aws-q1-2025/Architecture/ArtificialIntelligence/AmazonComprehendMedicalCard.Local.png) | ![illustration for AmazonComprehendMedicalGroup](../../../aws-q1-2025/Architecture/ArtificialIntelligence/AmazonComprehendMedicalGroup.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$AmazonComprehendMedicalXs>`
- `<$AmazonComprehendMedicalSm>`
- `<$AmazonComprehendMedicalMd>`
- `<$AmazonComprehendMedicalLg>`





## AmazonComprehendMedical

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('aws-q1-2025/bootstrap')

' loads the Item which embeds the element AmazonComprehendMedical
include('aws-q1-2025/Architecture/ArtificialIntelligence/AmazonComprehendMedical')

' renders the element
AmazonComprehendMedical('AmazonComprehendMedical', 'Amazon Comprehend Medical', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element AmazonComprehendMedical
include('aws-q1-2025/Architecture/ArtificialIntelligence/AmazonComprehendMedical')

' renders the element
AmazonComprehendMedical('AmazonComprehendMedical', 'Amazon Comprehend Medical', 'an optional tech label', 'an optional description')
@enduml
```

## AmazonComprehendMedicalCard

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('aws-q1-2025/bootstrap')

' loads the Item which embeds the element AmazonComprehendMedicalCard
include('aws-q1-2025/Architecture/ArtificialIntelligence/AmazonComprehendMedical')

' renders the element
AmazonComprehendMedicalCard('AmazonComprehendMedicalCard', 'Amazon Comprehend Medical Card', 'an optional description')
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

' loads the Item which embeds the element AmazonComprehendMedicalCard
include('aws-q1-2025/Architecture/ArtificialIntelligence/AmazonComprehendMedical')

' renders the element
AmazonComprehendMedicalCard('AmazonComprehendMedicalCard', 'Amazon Comprehend Medical Card', 'an optional description')
@enduml
```

## AmazonComprehendMedicalGroup

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('aws-q1-2025/bootstrap')

' loads the Item which embeds the element AmazonComprehendMedicalGroup
include('aws-q1-2025/Architecture/ArtificialIntelligence/AmazonComprehendMedical')

' renders the element
AmazonComprehendMedicalGroup('AmazonComprehendMedicalGroup', 'Amazon Comprehend Medical Group', 'an optional tech label') {
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

' loads the Item which embeds the element AmazonComprehendMedicalGroup
include('aws-q1-2025/Architecture/ArtificialIntelligence/AmazonComprehendMedical')

' renders the element
AmazonComprehendMedicalGroup('AmazonComprehendMedicalGroup', 'Amazon Comprehend Medical Group', 'an optional tech label') {
    note as note
        the content of the group
    end note
}
@enduml
```

