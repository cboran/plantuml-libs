# Aws Macie

```text
aws-20200430/Item/SecurityIdentityCompliance/AwsMacie
```

```text
include('aws-20200430/Item/SecurityIdentityCompliance/AwsMacie')
```

|icon|card|element|group|
|---|---|---|---|
|![](AwsMacie.png)|![](AwsMacie.card.png)|![](AwsMacie.element.png)|![](AwsMacie.group.png)|



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
' loads the AwsMacie element
include('aws-20200430/Item/SecurityIdentityCompliance/AwsMacie')
AwsMacieCard('aws_macie', 'Aws Macie', 'Molestiae praesentium aut natus dolorem. Aut consequatur fugiat a consequatur ut.')
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
' loads the AwsMacie element
include('aws-20200430/Item/SecurityIdentityCompliance/AwsMacie')
AwsMacieCard('aws_macie', 'Aws Macie', 'Molestiae praesentium aut natus dolorem. Aut consequatur fugiat a consequatur ut.')
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
' loads the AwsMacie element
include('aws-20200430/Item/SecurityIdentityCompliance/AwsMacie')
AwsMacie('aws_macie', 'Aws Macie', 'an optional tech field')
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
' loads the AwsMacie element
include('aws-20200430/Item/SecurityIdentityCompliance/AwsMacie')
AwsMacie('aws_macie', 'Aws Macie', 'an optional tech field')
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
' loads the AwsMacie element
include('aws-20200430/Item/SecurityIdentityCompliance/AwsMacie')
AwsMacieGroup('aws_macie', 'Aws Macie', 'an optional tech field'){
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
' loads the AwsMacie element
include('aws-20200430/Item/SecurityIdentityCompliance/AwsMacie')
AwsMacieGroup('aws_macie', 'Aws Macie', 'an optional tech field'){
note as note
the content of the group
end note
}
@enduml
```

