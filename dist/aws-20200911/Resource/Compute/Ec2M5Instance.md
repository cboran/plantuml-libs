# Ec2 M5 Instance

```text
aws-20200911/Resource/Compute/Ec2M5Instance
```

```text
include('aws-20200911/Resource/Compute/Ec2M5Instance')
```

|icon|card|element|group|
|---|---|---|---|
|![](Ec2M5Instance.png)|![](Ec2M5Instance.card.png)|![](Ec2M5Instance.element.png)|![](Ec2M5Instance.group.png)|



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
' loads the Ec2M5Instance element
include('aws-20200911/Resource/Compute/Ec2M5Instance')
Ec2M5InstanceCard('ec_2_m_5_instance', 'Ec2 M5 Instance', 'Molestiae praesentium aut natus dolorem. Aut consequatur fugiat a consequatur ut.')
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
' loads the Ec2M5Instance element
include('aws-20200911/Resource/Compute/Ec2M5Instance')
Ec2M5InstanceCard('ec_2_m_5_instance', 'Ec2 M5 Instance', 'Molestiae praesentium aut natus dolorem. Aut consequatur fugiat a consequatur ut.')
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
' loads the Ec2M5Instance element
include('aws-20200911/Resource/Compute/Ec2M5Instance')
Ec2M5Instance('ec_2_m_5_instance', 'Ec2 M5 Instance', 'an optional tech field')
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
' loads the Ec2M5Instance element
include('aws-20200911/Resource/Compute/Ec2M5Instance')
Ec2M5Instance('ec_2_m_5_instance', 'Ec2 M5 Instance', 'an optional tech field')
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
' loads the Ec2M5Instance element
include('aws-20200911/Resource/Compute/Ec2M5Instance')
Ec2M5InstanceGroup('ec_2_m_5_instance', 'Ec2 M5 Instance', 'an optional tech field'){
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
' loads the Ec2M5Instance element
include('aws-20200911/Resource/Compute/Ec2M5Instance')
Ec2M5InstanceGroup('ec_2_m_5_instance', 'Ec2 M5 Instance', 'an optional tech field'){
note as note
the content of the group
end note
}
@enduml
```

