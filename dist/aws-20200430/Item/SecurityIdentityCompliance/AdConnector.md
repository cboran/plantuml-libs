# Ad Connector

```text
aws-20200430/Item/SecurityIdentityCompliance/AdConnector
```

```text
include('aws-20200430/Item/SecurityIdentityCompliance/AdConnector')
```

|icon|card|element|group|
|---|---|---|---|
|![](AdConnector.png)|![](AdConnector.card.png)|![](AdConnector.element.png)|![](AdConnector.group.png)|



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
' loads the AdConnector element
include('aws-20200430/Item/SecurityIdentityCompliance/AdConnector')
AdConnectorCard('ad_connector', 'Ad Connector', 'Molestiae praesentium aut natus dolorem. Aut consequatur fugiat a consequatur ut.')
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
' loads the AdConnector element
include('aws-20200430/Item/SecurityIdentityCompliance/AdConnector')
AdConnectorCard('ad_connector', 'Ad Connector', 'Molestiae praesentium aut natus dolorem. Aut consequatur fugiat a consequatur ut.')
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
' loads the AdConnector element
include('aws-20200430/Item/SecurityIdentityCompliance/AdConnector')
AdConnector('ad_connector', 'Ad Connector', 'an optional tech field')
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
' loads the AdConnector element
include('aws-20200430/Item/SecurityIdentityCompliance/AdConnector')
AdConnector('ad_connector', 'Ad Connector', 'an optional tech field')
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
' loads the AdConnector element
include('aws-20200430/Item/SecurityIdentityCompliance/AdConnector')
AdConnectorGroup('ad_connector', 'Ad Connector', 'an optional tech field'){
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
' loads the AdConnector element
include('aws-20200430/Item/SecurityIdentityCompliance/AdConnector')
AdConnectorGroup('ad_connector', 'Ad Connector', 'an optional tech field'){
note as note
the content of the group
end note
}
@enduml
```

