# Generic Database

```text
aws-20200430/Item/General/GenericDatabase
```

```text
include('aws-20200430/Item/General/GenericDatabase')
```

|icon|card|element|group|
|---|---|---|---|
|![](GenericDatabase.png)|![](GenericDatabase.card.png)|![](GenericDatabase.element.png)|![](GenericDatabase.group.png)|



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
' loads the GenericDatabase element
include('aws-20200430/Item/General/GenericDatabase')
GenericDatabaseCard('generic_database', 'Generic Database', 'Molestiae praesentium aut natus dolorem. Aut consequatur fugiat a consequatur ut.')
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
' loads the GenericDatabase element
include('aws-20200430/Item/General/GenericDatabase')
GenericDatabaseCard('generic_database', 'Generic Database', 'Molestiae praesentium aut natus dolorem. Aut consequatur fugiat a consequatur ut.')
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
' loads the GenericDatabase element
include('aws-20200430/Item/General/GenericDatabase')
GenericDatabase('generic_database', 'Generic Database', 'an optional tech field')
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
' loads the GenericDatabase element
include('aws-20200430/Item/General/GenericDatabase')
GenericDatabase('generic_database', 'Generic Database', 'an optional tech field')
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
' loads the GenericDatabase element
include('aws-20200430/Item/General/GenericDatabase')
GenericDatabaseGroup('generic_database', 'Generic Database', 'an optional tech field'){
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
' loads the GenericDatabase element
include('aws-20200430/Item/General/GenericDatabase')
GenericDatabaseGroup('generic_database', 'Generic Database', 'an optional tech field'){
note as note
the content of the group
end note
}
@enduml
```

