# Aws Thinkbox Sequoia

```text
aws-20200430/Item/Compute/AwsThinkboxSequoia
```

```text
include('aws-20200430/Item/Compute/AwsThinkboxSequoia')
```

|icon|card|element|group|
|---|---|---|---|
|![](AwsThinkboxSequoia.png)|![](AwsThinkboxSequoia.card.png)|![](AwsThinkboxSequoia.element.png)|![](AwsThinkboxSequoia.group.png)|



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
' loads the AwsThinkboxSequoia element
include('aws-20200430/Item/Compute/AwsThinkboxSequoia')
AwsThinkboxSequoiaCard('aws_thinkbox_sequoia', 'Aws Thinkbox Sequoia', 'Molestiae praesentium aut natus dolorem. Aut consequatur fugiat a consequatur ut.')
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
' loads the AwsThinkboxSequoia element
include('aws-20200430/Item/Compute/AwsThinkboxSequoia')
AwsThinkboxSequoiaCard('aws_thinkbox_sequoia', 'Aws Thinkbox Sequoia', 'Molestiae praesentium aut natus dolorem. Aut consequatur fugiat a consequatur ut.')
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
' loads the AwsThinkboxSequoia element
include('aws-20200430/Item/Compute/AwsThinkboxSequoia')
AwsThinkboxSequoia('aws_thinkbox_sequoia', 'Aws Thinkbox Sequoia', 'an optional tech field')
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
' loads the AwsThinkboxSequoia element
include('aws-20200430/Item/Compute/AwsThinkboxSequoia')
AwsThinkboxSequoia('aws_thinkbox_sequoia', 'Aws Thinkbox Sequoia', 'an optional tech field')
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
' loads the AwsThinkboxSequoia element
include('aws-20200430/Item/Compute/AwsThinkboxSequoia')
AwsThinkboxSequoiaGroup('aws_thinkbox_sequoia', 'Aws Thinkbox Sequoia', 'an optional tech field'){
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
' loads the AwsThinkboxSequoia element
include('aws-20200430/Item/Compute/AwsThinkboxSequoia')
AwsThinkboxSequoiaGroup('aws_thinkbox_sequoia', 'Aws Thinkbox Sequoia', 'an optional tech field'){
note as note
the content of the group
end note
}
@enduml
```

