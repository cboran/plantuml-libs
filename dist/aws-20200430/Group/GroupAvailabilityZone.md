# Group Availability Zone

```text
aws-20200430/Group/GroupAvailabilityZone
```

```text
include('aws-20200430/Group/GroupAvailabilityZone')
```

|group|
|---|
|![](GroupAvailabilityZone.group.local.png)|



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
' loads the GroupAvailabilityZone element
include('aws-20200430/Group/GroupAvailabilityZone')
GroupAvailabilityZone('group_availability_zone', 'Group Availability Zone', 'an optional tech field')
@enduml
```
### Load locally
```plantuml
@startuml
' configures the library
!global $INCLUSION_MODE="local"
!global $LIB_BASE_LOCATION="../.."
' loads the library
!include $LIB_BASE_LOCATION/bootstrap.puml
' loads the aws-20200430 bootstrap
include('aws-20200430/bootstrap')
' loads the GroupAvailabilityZone element
include('aws-20200430/Group/GroupAvailabilityZone')
GroupAvailabilityZone('group_availability_zone', 'Group Availability Zone', 'an optional tech field')
@enduml
```

