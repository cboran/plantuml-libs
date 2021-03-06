# Aws Cloud9

```text
aws-20200911/Service/DeveloperTools/AwsCloud9
```

```text
include('aws-20200911/Service/DeveloperTools/AwsCloud9')
```

|icon|card|element|group|
|---|---|---|---|
|![](AwsCloud9.png)|![](AwsCloud9.card.png)|![](AwsCloud9.element.png)|![](AwsCloud9.group.png)|



## card
### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/dist"
' loads the library
!include $LIB_BASE_LOCATION/bootstrap.puml
' loads the aws-20200911 bootstrap
include('aws-20200911/bootstrap')
' loads the AwsCloud9 element
include('aws-20200911/Service/DeveloperTools/AwsCloud9')
AwsCloud9Card('aws_cloud_9', 'Aws Cloud9', 'Molestiae praesentium aut natus dolorem. Aut consequatur fugiat a consequatur ut.')
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
' loads the aws-20200911 bootstrap
include('aws-20200911/bootstrap')
' loads the AwsCloud9 element
include('aws-20200911/Service/DeveloperTools/AwsCloud9')
AwsCloud9Card('aws_cloud_9', 'Aws Cloud9', 'Molestiae praesentium aut natus dolorem. Aut consequatur fugiat a consequatur ut.')
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
' loads the aws-20200911 bootstrap
include('aws-20200911/bootstrap')
' loads the AwsCloud9 element
include('aws-20200911/Service/DeveloperTools/AwsCloud9')
AwsCloud9('aws_cloud_9', 'Aws Cloud9', 'an optional tech field')
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
' loads the aws-20200911 bootstrap
include('aws-20200911/bootstrap')
' loads the AwsCloud9 element
include('aws-20200911/Service/DeveloperTools/AwsCloud9')
AwsCloud9('aws_cloud_9', 'Aws Cloud9', 'an optional tech field')
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
' loads the aws-20200911 bootstrap
include('aws-20200911/bootstrap')
' loads the AwsCloud9 element
include('aws-20200911/Service/DeveloperTools/AwsCloud9')
AwsCloud9Group('aws_cloud_9', 'Aws Cloud9', 'an optional tech field'){
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
' loads the aws-20200911 bootstrap
include('aws-20200911/bootstrap')
' loads the AwsCloud9 element
include('aws-20200911/Service/DeveloperTools/AwsCloud9')
AwsCloud9Group('aws_cloud_9', 'Aws Cloud9', 'an optional tech field'){
note as note
the content of the group
end note
}
@enduml
```

