# Service Image Definitions

```text
azure-v2/Item/Compute/ServiceImageDefinitions
```

```text
include('azure-v2/Item/Compute/ServiceImageDefinitions')
```

|icon|card|element|group|
|---|---|---|---|
|![](ServiceImageDefinitions.png)|![](ServiceImageDefinitions.card.png)|![](ServiceImageDefinitions.element.png)|![](ServiceImageDefinitions.group.png)|



## card
### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/dist"
' loads the library
!include $LIB_BASE_LOCATION/bootstrap.puml
' loads the azure-v2 bootstrap
include('azure-v2/bootstrap')
' loads the ServiceImageDefinitions element
include('azure-v2/Item/Compute/ServiceImageDefinitions')
ServiceImageDefinitionsCard('service_image_definitions', 'Service Image Definitions', 'Molestiae praesentium aut natus dolorem. Aut consequatur fugiat a consequatur ut.')
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
' loads the azure-v2 bootstrap
include('azure-v2/bootstrap')
' loads the ServiceImageDefinitions element
include('azure-v2/Item/Compute/ServiceImageDefinitions')
ServiceImageDefinitionsCard('service_image_definitions', 'Service Image Definitions', 'Molestiae praesentium aut natus dolorem. Aut consequatur fugiat a consequatur ut.')
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
' loads the azure-v2 bootstrap
include('azure-v2/bootstrap')
' loads the ServiceImageDefinitions element
include('azure-v2/Item/Compute/ServiceImageDefinitions')
ServiceImageDefinitions('service_image_definitions', 'Service Image Definitions', 'an optional tech field')
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
' loads the azure-v2 bootstrap
include('azure-v2/bootstrap')
' loads the ServiceImageDefinitions element
include('azure-v2/Item/Compute/ServiceImageDefinitions')
ServiceImageDefinitions('service_image_definitions', 'Service Image Definitions', 'an optional tech field')
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
' loads the azure-v2 bootstrap
include('azure-v2/bootstrap')
' loads the ServiceImageDefinitions element
include('azure-v2/Item/Compute/ServiceImageDefinitions')
ServiceImageDefinitionsGroup('service_image_definitions', 'Service Image Definitions', 'an optional tech field'){
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
' loads the azure-v2 bootstrap
include('azure-v2/bootstrap')
' loads the ServiceImageDefinitions element
include('azure-v2/Item/Compute/ServiceImageDefinitions')
ServiceImageDefinitionsGroup('service_image_definitions', 'Service Image Definitions', 'an optional tech field'){
note as note
the content of the group
end note
}
@enduml
```

