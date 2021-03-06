# Aws Support

```text
aws-20200430/Item/CustomerEnablement/AwsSupport
```

```text
include('aws-20200430/Item/CustomerEnablement/AwsSupport')
```

|icon|card|element|group|
|---|---|---|---|
|![](AwsSupport.png)|![](AwsSupport.card.png)|![](AwsSupport.element.png)|![](AwsSupport.group.png)|



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
' loads the AwsSupport element
include('aws-20200430/Item/CustomerEnablement/AwsSupport')
AwsSupportCard('aws_support', 'Aws Support', 'Molestiae praesentium aut natus dolorem. Aut consequatur fugiat a consequatur ut.')
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
' loads the AwsSupport element
include('aws-20200430/Item/CustomerEnablement/AwsSupport')
AwsSupportCard('aws_support', 'Aws Support', 'Molestiae praesentium aut natus dolorem. Aut consequatur fugiat a consequatur ut.')
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
' loads the AwsSupport element
include('aws-20200430/Item/CustomerEnablement/AwsSupport')
AwsSupport('aws_support', 'Aws Support', 'an optional tech field')
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
' loads the AwsSupport element
include('aws-20200430/Item/CustomerEnablement/AwsSupport')
AwsSupport('aws_support', 'Aws Support', 'an optional tech field')
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
' loads the AwsSupport element
include('aws-20200430/Item/CustomerEnablement/AwsSupport')
AwsSupportGroup('aws_support', 'Aws Support', 'an optional tech field'){
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
' loads the AwsSupport element
include('aws-20200430/Item/CustomerEnablement/AwsSupport')
AwsSupportGroup('aws_support', 'Aws Support', 'an optional tech field'){
note as note
the content of the group
end note
}
@enduml
```

