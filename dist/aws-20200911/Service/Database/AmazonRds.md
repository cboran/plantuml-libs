# Amazon Rds

```text
aws-20200911/Service/Database/AmazonRds
```

```text
include('aws-20200911/Service/Database/AmazonRds')
```

|icon|card|element|group|
|---|---|---|---|
|![](AmazonRds.png)|![](AmazonRds.card.png)|![](AmazonRds.element.png)|![](AmazonRds.group.png)|



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
' loads the AmazonRds element
include('aws-20200911/Service/Database/AmazonRds')
AmazonRdsCard('amazon_rds', 'Amazon Rds', 'Molestiae praesentium aut natus dolorem. Aut consequatur fugiat a consequatur ut.')
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
' loads the AmazonRds element
include('aws-20200911/Service/Database/AmazonRds')
AmazonRdsCard('amazon_rds', 'Amazon Rds', 'Molestiae praesentium aut natus dolorem. Aut consequatur fugiat a consequatur ut.')
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
' loads the AmazonRds element
include('aws-20200911/Service/Database/AmazonRds')
AmazonRds('amazon_rds', 'Amazon Rds', 'an optional tech field')
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
' loads the AmazonRds element
include('aws-20200911/Service/Database/AmazonRds')
AmazonRds('amazon_rds', 'Amazon Rds', 'an optional tech field')
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
' loads the AmazonRds element
include('aws-20200911/Service/Database/AmazonRds')
AmazonRdsGroup('amazon_rds', 'Amazon Rds', 'an optional tech field'){
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
' loads the AmazonRds element
include('aws-20200911/Service/Database/AmazonRds')
AmazonRdsGroup('amazon_rds', 'Amazon Rds', 'an optional tech field'){
note as note
the content of the group
end note
}
@enduml
```

