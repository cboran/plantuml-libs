# A8 Mp

```text
material-4.0/Image/A8Mp
```

```text
include('material-4.0/Image/A8Mp')
```

|icon|element|
|---|---|
|![](A8Mp.png)|![](A8Mp.element.png)|



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
' loads the A8Mp element
include('material-4.0/Image/A8Mp')
A8Mp('a_8_mp', 'A8 Mp', 'an optional tech field')
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
' loads the A8Mp element
include('material-4.0/Image/A8Mp')
A8Mp('a_8_mp', 'A8 Mp', 'an optional tech field')
@enduml
```

