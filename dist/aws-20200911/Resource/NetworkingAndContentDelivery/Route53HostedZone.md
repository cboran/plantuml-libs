# Route53 Hosted Zone

```text
aws-20200911/Resource/NetworkingAndContentDelivery/Route53HostedZone
```

```text
include('aws-20200911/Resource/NetworkingAndContentDelivery/Route53HostedZone')
```

|icon|card|element|group|
|---|---|---|---|
|![](Route53HostedZone.png)|![](Route53HostedZone.card.png)|![](Route53HostedZone.element.png)|![](Route53HostedZone.group.png)|



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
' loads the Route53HostedZone element
include('aws-20200911/Resource/NetworkingAndContentDelivery/Route53HostedZone')
Route53HostedZoneCard('route_53_hosted_zone', 'Route53 Hosted Zone', 'Molestiae praesentium aut natus dolorem. Aut consequatur fugiat a consequatur ut.')
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
' loads the Route53HostedZone element
include('aws-20200911/Resource/NetworkingAndContentDelivery/Route53HostedZone')
Route53HostedZoneCard('route_53_hosted_zone', 'Route53 Hosted Zone', 'Molestiae praesentium aut natus dolorem. Aut consequatur fugiat a consequatur ut.')
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
' loads the Route53HostedZone element
include('aws-20200911/Resource/NetworkingAndContentDelivery/Route53HostedZone')
Route53HostedZone('route_53_hosted_zone', 'Route53 Hosted Zone', 'an optional tech field')
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
' loads the Route53HostedZone element
include('aws-20200911/Resource/NetworkingAndContentDelivery/Route53HostedZone')
Route53HostedZone('route_53_hosted_zone', 'Route53 Hosted Zone', 'an optional tech field')
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
' loads the Route53HostedZone element
include('aws-20200911/Resource/NetworkingAndContentDelivery/Route53HostedZone')
Route53HostedZoneGroup('route_53_hosted_zone', 'Route53 Hosted Zone', 'an optional tech field'){
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
' loads the Route53HostedZone element
include('aws-20200911/Resource/NetworkingAndContentDelivery/Route53HostedZone')
Route53HostedZoneGroup('route_53_hosted_zone', 'Route53 Hosted Zone', 'an optional tech field'){
note as note
the content of the group
end note
}
@enduml
```

