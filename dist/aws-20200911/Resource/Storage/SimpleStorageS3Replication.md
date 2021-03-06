# Simple Storage S3 Replication

```text
aws-20200911/Resource/Storage/SimpleStorageS3Replication
```

```text
include('aws-20200911/Resource/Storage/SimpleStorageS3Replication')
```

|icon|card|element|group|
|---|---|---|---|
|![](SimpleStorageS3Replication.png)|![](SimpleStorageS3Replication.card.png)|![](SimpleStorageS3Replication.element.png)|![](SimpleStorageS3Replication.group.png)|



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
' loads the SimpleStorageS3Replication element
include('aws-20200911/Resource/Storage/SimpleStorageS3Replication')
SimpleStorageS3ReplicationCard('simple_storage_s_3_replication', 'Simple Storage S3 Replication', 'Molestiae praesentium aut natus dolorem. Aut consequatur fugiat a consequatur ut.')
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
' loads the SimpleStorageS3Replication element
include('aws-20200911/Resource/Storage/SimpleStorageS3Replication')
SimpleStorageS3ReplicationCard('simple_storage_s_3_replication', 'Simple Storage S3 Replication', 'Molestiae praesentium aut natus dolorem. Aut consequatur fugiat a consequatur ut.')
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
' loads the SimpleStorageS3Replication element
include('aws-20200911/Resource/Storage/SimpleStorageS3Replication')
SimpleStorageS3Replication('simple_storage_s_3_replication', 'Simple Storage S3 Replication', 'an optional tech field')
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
' loads the SimpleStorageS3Replication element
include('aws-20200911/Resource/Storage/SimpleStorageS3Replication')
SimpleStorageS3Replication('simple_storage_s_3_replication', 'Simple Storage S3 Replication', 'an optional tech field')
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
' loads the SimpleStorageS3Replication element
include('aws-20200911/Resource/Storage/SimpleStorageS3Replication')
SimpleStorageS3ReplicationGroup('simple_storage_s_3_replication', 'Simple Storage S3 Replication', 'an optional tech field'){
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
' loads the SimpleStorageS3Replication element
include('aws-20200911/Resource/Storage/SimpleStorageS3Replication')
SimpleStorageS3ReplicationGroup('simple_storage_s_3_replication', 'Simple Storage S3 Replication', 'an optional tech field'){
note as note
the content of the group
end note
}
@enduml
```

