# AwsThinkboxFrost


```text
aws-q1-2025/Architecture/MediaServices/AwsThinkboxFrost
```

```text
include('aws-q1-2025/Architecture/MediaServices/AwsThinkboxFrost')
```



| Illustration | AwsThinkboxFrost | AwsThinkboxFrostCard | AwsThinkboxFrostGroup |
| :---: | :---: | :---: | :---: |
| ![illustration for Illustration](../../../aws-q1-2025/Architecture/MediaServices/AwsThinkboxFrost.png) | ![illustration for AwsThinkboxFrost](../../../aws-q1-2025/Architecture/MediaServices/AwsThinkboxFrost.Local.png) | ![illustration for AwsThinkboxFrostCard](../../../aws-q1-2025/Architecture/MediaServices/AwsThinkboxFrostCard.Local.png) | ![illustration for AwsThinkboxFrostGroup](../../../aws-q1-2025/Architecture/MediaServices/AwsThinkboxFrostGroup.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$AwsThinkboxFrostXs>`
- `<$AwsThinkboxFrostSm>`
- `<$AwsThinkboxFrostMd>`
- `<$AwsThinkboxFrostLg>`





## AwsThinkboxFrost

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('aws-q1-2025/bootstrap')

' loads the Item which embeds the element AwsThinkboxFrost
include('aws-q1-2025/Architecture/MediaServices/AwsThinkboxFrost')

' renders the element
AwsThinkboxFrost('AwsThinkboxFrost', 'Aws Thinkbox Frost', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element AwsThinkboxFrost
include('aws-q1-2025/Architecture/MediaServices/AwsThinkboxFrost')

' renders the element
AwsThinkboxFrost('AwsThinkboxFrost', 'Aws Thinkbox Frost', 'an optional tech label', 'an optional description')
@enduml
```

## AwsThinkboxFrostCard

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('aws-q1-2025/bootstrap')

' loads the Item which embeds the element AwsThinkboxFrostCard
include('aws-q1-2025/Architecture/MediaServices/AwsThinkboxFrost')

' renders the element
AwsThinkboxFrostCard('AwsThinkboxFrostCard', 'Aws Thinkbox Frost Card', 'an optional description')
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

' loads the Item which embeds the element AwsThinkboxFrostCard
include('aws-q1-2025/Architecture/MediaServices/AwsThinkboxFrost')

' renders the element
AwsThinkboxFrostCard('AwsThinkboxFrostCard', 'Aws Thinkbox Frost Card', 'an optional description')
@enduml
```

## AwsThinkboxFrostGroup

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('aws-q1-2025/bootstrap')

' loads the Item which embeds the element AwsThinkboxFrostGroup
include('aws-q1-2025/Architecture/MediaServices/AwsThinkboxFrost')

' renders the element
AwsThinkboxFrostGroup('AwsThinkboxFrostGroup', 'Aws Thinkbox Frost Group', 'an optional tech label') {
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

' loads the Item which embeds the element AwsThinkboxFrostGroup
include('aws-q1-2025/Architecture/MediaServices/AwsThinkboxFrost')

' renders the element
AwsThinkboxFrostGroup('AwsThinkboxFrostGroup', 'Aws Thinkbox Frost Group', 'an optional tech label') {
    note as note
        the content of the group
    end note
}
@enduml
```

