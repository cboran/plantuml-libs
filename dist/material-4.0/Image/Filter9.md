# Filter9

```text
material-4.0/Image/Filter9
```

```text
include('material-4.0/Image/Filter9')
```

|icon|element|
|---|---|
|![](Filter9.png)|![](Filter9.element.png)|



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
' loads the Filter9 element
include('material-4.0/Image/Filter9')
Filter9('filter_9', 'Filter9', 'an optional tech field')
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
' loads the Filter9 element
include('material-4.0/Image/Filter9')
Filter9('filter_9', 'Filter9', 'an optional tech field')
@enduml
```

