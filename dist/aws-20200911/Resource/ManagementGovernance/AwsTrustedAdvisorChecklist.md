# Aws Trusted Advisor Checklist

```text
aws-20200911/Resource/ManagementGovernance/AwsTrustedAdvisorChecklist
```

```text
include('aws-20200911/Resource/ManagementGovernance/AwsTrustedAdvisorChecklist')
```

|icon|card|element|group|
|---|---|---|---|
|![](AwsTrustedAdvisorChecklist.png)|![](AwsTrustedAdvisorChecklist.card.png)|![](AwsTrustedAdvisorChecklist.element.png)|![](AwsTrustedAdvisorChecklist.group.png)|



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
' loads the AwsTrustedAdvisorChecklist element
include('aws-20200911/Resource/ManagementGovernance/AwsTrustedAdvisorChecklist')
AwsTrustedAdvisorChecklistCard('aws_trusted_advisor_checklist', 'Aws Trusted Advisor Checklist', 'Molestiae praesentium aut natus dolorem. Aut consequatur fugiat a consequatur ut.')
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
' loads the AwsTrustedAdvisorChecklist element
include('aws-20200911/Resource/ManagementGovernance/AwsTrustedAdvisorChecklist')
AwsTrustedAdvisorChecklistCard('aws_trusted_advisor_checklist', 'Aws Trusted Advisor Checklist', 'Molestiae praesentium aut natus dolorem. Aut consequatur fugiat a consequatur ut.')
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
' loads the AwsTrustedAdvisorChecklist element
include('aws-20200911/Resource/ManagementGovernance/AwsTrustedAdvisorChecklist')
AwsTrustedAdvisorChecklist('aws_trusted_advisor_checklist', 'Aws Trusted Advisor Checklist', 'an optional tech field')
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
' loads the AwsTrustedAdvisorChecklist element
include('aws-20200911/Resource/ManagementGovernance/AwsTrustedAdvisorChecklist')
AwsTrustedAdvisorChecklist('aws_trusted_advisor_checklist', 'Aws Trusted Advisor Checklist', 'an optional tech field')
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
' loads the AwsTrustedAdvisorChecklist element
include('aws-20200911/Resource/ManagementGovernance/AwsTrustedAdvisorChecklist')
AwsTrustedAdvisorChecklistGroup('aws_trusted_advisor_checklist', 'Aws Trusted Advisor Checklist', 'an optional tech field'){
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
' loads the AwsTrustedAdvisorChecklist element
include('aws-20200911/Resource/ManagementGovernance/AwsTrustedAdvisorChecklist')
AwsTrustedAdvisorChecklistGroup('aws_trusted_advisor_checklist', 'Aws Trusted Advisor Checklist', 'an optional tech field'){
note as note
the content of the group
end note
}
@enduml
```

