# Aws Thinkbox Deadline

```text
aws-20200430/Item/Compute/AwsThinkboxDeadline
```

```text
include('aws-20200430/Item/Compute/AwsThinkboxDeadline')
```

|icon|card|element|group|
|---|---|---|---|
|![](AwsThinkboxDeadline.png)|![](AwsThinkboxDeadline.card.png)|![](AwsThinkboxDeadline.element.png)|![](AwsThinkboxDeadline.group.png)|



## card
### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/dist"
' loads the library
!include $LIB_BASE_LOCATION/bootstrap.puml
' loads the aws-20200430 bootstrap
include('aws-20200430/bootstrap')
' loads the AwsThinkboxDeadline element
include('aws-20200430/Item/Compute/AwsThinkboxDeadline')
AwsThinkboxDeadlineCard('aws_thinkbox_deadline', 'Aws Thinkbox Deadline', 'Molestiae praesentium aut natus dolorem. Aut consequatur fugiat a consequatur ut.')
@enduml
```
### Load locally
```plantuml
@startuml
' configures the library
!global $INCLUSION_MODE="local"
!global $LIB_BASE_LOCATION="../../.."
' loads the library
!include $LIB_BASE_LOCATION/bootstrap.puml
' loads the aws-20200430 bootstrap
include('aws-20200430/bootstrap')
' loads the AwsThinkboxDeadline element
include('aws-20200430/Item/Compute/AwsThinkboxDeadline')
AwsThinkboxDeadlineCard('aws_thinkbox_deadline', 'Aws Thinkbox Deadline', 'Molestiae praesentium aut natus dolorem. Aut consequatur fugiat a consequatur ut.')
@enduml
```


## element
### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/dist"
' loads the library
!include $LIB_BASE_LOCATION/bootstrap.puml
' loads the aws-20200430 bootstrap
include('aws-20200430/bootstrap')
' loads the AwsThinkboxDeadline element
include('aws-20200430/Item/Compute/AwsThinkboxDeadline')
AwsThinkboxDeadline('aws_thinkbox_deadline', 'Aws Thinkbox Deadline', 'an optional tech field')
@enduml
```
### Load locally
```plantuml
@startuml
' configures the library
!global $INCLUSION_MODE="local"
!global $LIB_BASE_LOCATION="../../.."
' loads the library
!include $LIB_BASE_LOCATION/bootstrap.puml
' loads the aws-20200430 bootstrap
include('aws-20200430/bootstrap')
' loads the AwsThinkboxDeadline element
include('aws-20200430/Item/Compute/AwsThinkboxDeadline')
AwsThinkboxDeadline('aws_thinkbox_deadline', 'Aws Thinkbox Deadline', 'an optional tech field')
@enduml
```


## group
### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/dist"
' loads the library
!include $LIB_BASE_LOCATION/bootstrap.puml
' loads the aws-20200430 bootstrap
include('aws-20200430/bootstrap')
' loads the AwsThinkboxDeadline element
include('aws-20200430/Item/Compute/AwsThinkboxDeadline')
AwsThinkboxDeadlineGroup('aws_thinkbox_deadline', 'Aws Thinkbox Deadline', 'an optional tech field'){
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
' loads the library
!include $LIB_BASE_LOCATION/bootstrap.puml
' loads the aws-20200430 bootstrap
include('aws-20200430/bootstrap')
' loads the AwsThinkboxDeadline element
include('aws-20200430/Item/Compute/AwsThinkboxDeadline')
AwsThinkboxDeadlineGroup('aws_thinkbox_deadline', 'Aws Thinkbox Deadline', 'an optional tech field'){
note as note
the content of the group
end note
}
@enduml
```

