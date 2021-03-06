# Service Event Hubs

```text
azure-v2/Item/IoT/ServiceEventHubs
```

```text
include('azure-v2/Item/IoT/ServiceEventHubs')
```

|icon|card|element|group|
|---|---|---|---|
|![](ServiceEventHubs.png)|![](ServiceEventHubs.card.png)|![](ServiceEventHubs.element.png)|![](ServiceEventHubs.group.png)|



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
' loads the ServiceEventHubs element
include('azure-v2/Item/IoT/ServiceEventHubs')
ServiceEventHubsCard('service_event_hubs', 'Service Event Hubs', 'Molestiae praesentium aut natus dolorem. Aut consequatur fugiat a consequatur ut.')
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
' loads the ServiceEventHubs element
include('azure-v2/Item/IoT/ServiceEventHubs')
ServiceEventHubsCard('service_event_hubs', 'Service Event Hubs', 'Molestiae praesentium aut natus dolorem. Aut consequatur fugiat a consequatur ut.')
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
' loads the ServiceEventHubs element
include('azure-v2/Item/IoT/ServiceEventHubs')
ServiceEventHubs('service_event_hubs', 'Service Event Hubs', 'an optional tech field')
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
' loads the ServiceEventHubs element
include('azure-v2/Item/IoT/ServiceEventHubs')
ServiceEventHubs('service_event_hubs', 'Service Event Hubs', 'an optional tech field')
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
' loads the ServiceEventHubs element
include('azure-v2/Item/IoT/ServiceEventHubs')
ServiceEventHubsGroup('service_event_hubs', 'Service Event Hubs', 'an optional tech field'){
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
' loads the ServiceEventHubs element
include('azure-v2/Item/IoT/ServiceEventHubs')
ServiceEventHubsGroup('service_event_hubs', 'Service Event Hubs', 'an optional tech field'){
note as note
the content of the group
end note
}
@enduml
```

