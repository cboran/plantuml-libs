# Service Event Grid Topics

```text
azure-v2/Item/Integration/ServiceEventGridTopics
```

```text
include('azure-v2/Item/Integration/ServiceEventGridTopics')
```

|icon|card|element|group|
|---|---|---|---|
|![](ServiceEventGridTopics.png)|![](ServiceEventGridTopics.card.png)|![](ServiceEventGridTopics.element.png)|![](ServiceEventGridTopics.group.png)|



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
' loads the ServiceEventGridTopics element
include('azure-v2/Item/Integration/ServiceEventGridTopics')
ServiceEventGridTopicsCard('service_event_grid_topics', 'Service Event Grid Topics', 'Molestiae praesentium aut natus dolorem. Aut consequatur fugiat a consequatur ut.')
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
' loads the ServiceEventGridTopics element
include('azure-v2/Item/Integration/ServiceEventGridTopics')
ServiceEventGridTopicsCard('service_event_grid_topics', 'Service Event Grid Topics', 'Molestiae praesentium aut natus dolorem. Aut consequatur fugiat a consequatur ut.')
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
' loads the ServiceEventGridTopics element
include('azure-v2/Item/Integration/ServiceEventGridTopics')
ServiceEventGridTopics('service_event_grid_topics', 'Service Event Grid Topics', 'an optional tech field')
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
' loads the ServiceEventGridTopics element
include('azure-v2/Item/Integration/ServiceEventGridTopics')
ServiceEventGridTopics('service_event_grid_topics', 'Service Event Grid Topics', 'an optional tech field')
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
' loads the ServiceEventGridTopics element
include('azure-v2/Item/Integration/ServiceEventGridTopics')
ServiceEventGridTopicsGroup('service_event_grid_topics', 'Service Event Grid Topics', 'an optional tech field'){
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
' loads the ServiceEventGridTopics element
include('azure-v2/Item/Integration/ServiceEventGridTopics')
ServiceEventGridTopicsGroup('service_event_grid_topics', 'Service Event Grid Topics', 'an optional tech field'){
note as note
the content of the group
end note
}
@enduml
```

