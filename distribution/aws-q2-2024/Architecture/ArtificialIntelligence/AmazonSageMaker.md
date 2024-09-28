# AmazonSageMaker


```text
aws-q2-2024/Architecture/ArtificialIntelligence/AmazonSageMaker
```

```text
include('aws-q2-2024/Architecture/ArtificialIntelligence/AmazonSageMaker')
```



| Illustration | AmazonSageMaker | AmazonSageMakerCard | AmazonSageMakerGroup |
| :---: | :---: | :---: | :---: |
| ![illustration for Illustration](../../../aws-q2-2024/Architecture/ArtificialIntelligence/AmazonSageMaker.png) | ![illustration for AmazonSageMaker](../../../aws-q2-2024/Architecture/ArtificialIntelligence/AmazonSageMaker.Local.png) | ![illustration for AmazonSageMakerCard](../../../aws-q2-2024/Architecture/ArtificialIntelligence/AmazonSageMakerCard.Local.png) | ![illustration for AmazonSageMakerGroup](../../../aws-q2-2024/Architecture/ArtificialIntelligence/AmazonSageMakerGroup.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$AmazonSageMakerXs>`
- `<$AmazonSageMakerSm>`
- `<$AmazonSageMakerMd>`
- `<$AmazonSageMakerLg>`





## AmazonSageMaker

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('aws-q2-2024/bootstrap')

' loads the Item which embeds the element AmazonSageMaker
include('aws-q2-2024/Architecture/ArtificialIntelligence/AmazonSageMaker')

' renders the element
AmazonSageMaker('AmazonSageMaker', 'Amazon Sage Maker', 'an optional tech label', 'an optional description')
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
include('aws-q2-2024/bootstrap')

' loads the Item which embeds the element AmazonSageMaker
include('aws-q2-2024/Architecture/ArtificialIntelligence/AmazonSageMaker')

' renders the element
AmazonSageMaker('AmazonSageMaker', 'Amazon Sage Maker', 'an optional tech label', 'an optional description')
@enduml
```

## AmazonSageMakerCard

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('aws-q2-2024/bootstrap')

' loads the Item which embeds the element AmazonSageMakerCard
include('aws-q2-2024/Architecture/ArtificialIntelligence/AmazonSageMaker')

' renders the element
AmazonSageMakerCard('AmazonSageMakerCard', 'Amazon Sage Maker Card', 'an optional description')
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
include('aws-q2-2024/bootstrap')

' loads the Item which embeds the element AmazonSageMakerCard
include('aws-q2-2024/Architecture/ArtificialIntelligence/AmazonSageMaker')

' renders the element
AmazonSageMakerCard('AmazonSageMakerCard', 'Amazon Sage Maker Card', 'an optional description')
@enduml
```

## AmazonSageMakerGroup

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('aws-q2-2024/bootstrap')

' loads the Item which embeds the element AmazonSageMakerGroup
include('aws-q2-2024/Architecture/ArtificialIntelligence/AmazonSageMaker')

' renders the element
AmazonSageMakerGroup('AmazonSageMakerGroup', 'Amazon Sage Maker Group', 'an optional tech label') {
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
include('aws-q2-2024/bootstrap')

' loads the Item which embeds the element AmazonSageMakerGroup
include('aws-q2-2024/Architecture/ArtificialIntelligence/AmazonSageMaker')

' renders the element
AmazonSageMakerGroup('AmazonSageMakerGroup', 'Amazon Sage Maker Group', 'an optional tech label') {
    note as note
        the content of the group
    end note
}
@enduml
```

