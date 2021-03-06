# Aws Trusted Advisor

```text
aws-20200430/Item/ManagementGovernance/AwsTrustedAdvisor
```

```text
include('aws-20200430/Item/ManagementGovernance/AwsTrustedAdvisor')
```

|icon|card|element|group|
|---|---|---|---|
|![](AwsTrustedAdvisor.png)|![](AwsTrustedAdvisor.card.png)|![](AwsTrustedAdvisor.element.png)|![](AwsTrustedAdvisor.group.png)|



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
' loads the AwsTrustedAdvisor element
include('aws-20200430/Item/ManagementGovernance/AwsTrustedAdvisor')
AwsTrustedAdvisorCard('aws_trusted_advisor', 'Aws Trusted Advisor', 'Molestiae praesentium aut natus dolorem. Aut consequatur fugiat a consequatur ut.')
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
' loads the AwsTrustedAdvisor element
include('aws-20200430/Item/ManagementGovernance/AwsTrustedAdvisor')
AwsTrustedAdvisorCard('aws_trusted_advisor', 'Aws Trusted Advisor', 'Molestiae praesentium aut natus dolorem. Aut consequatur fugiat a consequatur ut.')
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
' loads the AwsTrustedAdvisor element
include('aws-20200430/Item/ManagementGovernance/AwsTrustedAdvisor')
AwsTrustedAdvisor('aws_trusted_advisor', 'Aws Trusted Advisor', 'an optional tech field')
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
' loads the AwsTrustedAdvisor element
include('aws-20200430/Item/ManagementGovernance/AwsTrustedAdvisor')
AwsTrustedAdvisor('aws_trusted_advisor', 'Aws Trusted Advisor', 'an optional tech field')
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
' loads the AwsTrustedAdvisor element
include('aws-20200430/Item/ManagementGovernance/AwsTrustedAdvisor')
AwsTrustedAdvisorGroup('aws_trusted_advisor', 'Aws Trusted Advisor', 'an optional tech field'){
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
' loads the AwsTrustedAdvisor element
include('aws-20200430/Item/ManagementGovernance/AwsTrustedAdvisor')
AwsTrustedAdvisorGroup('aws_trusted_advisor', 'Aws Trusted Advisor', 'an optional tech field'){
note as note
the content of the group
end note
}
@enduml
```

