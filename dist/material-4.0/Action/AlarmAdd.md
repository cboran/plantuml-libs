# Alarm Add

```text
material-4.0/Action/AlarmAdd
```

```text
include('material-4.0/Action/AlarmAdd')
```

|icon|element|
|---|---|
|![](AlarmAdd.png)|![](AlarmAdd.element.png)|



## element
### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/dist"
' loads the library
!include $LIB_BASE_LOCATION/bootstrap.puml
' loads the material-4.0 bootstrap
include('material-4.0/bootstrap')
' loads the AlarmAdd element
include('material-4.0/Action/AlarmAdd')
AlarmAdd('alarm_add', 'Alarm Add', 'an optional tech field')
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
' loads the material-4.0 bootstrap
include('material-4.0/bootstrap')
' loads the AlarmAdd element
include('material-4.0/Action/AlarmAdd')
AlarmAdd('alarm_add', 'Alarm Add', 'an optional tech field')
@enduml
```
