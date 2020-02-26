# AzureIotCentralApplications
```text
elements/azure/InternetOfThingsServiceColor/AzureIotCentralApplications
```
| Icon | Element | Card |
| :-: | :-: | --- |
| ![AzureIotCentralApplications icon](../../../icons/azure/InternetOfThingsServiceColor/AzureIotCentralApplications.png) | ![AzureIotCentralApplications element](AzureIotCentralApplications.element.png) | ![AzureIotCentralApplications card](AzureIotCentralApplications.card.png) |
## Element
### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BRANCH="master"
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/" + $LIB_BRANCH + "/cloud"

' loads the library
!includeurl $LIB_BASE_LOCATION/library.puml

' loads the AWS style
include('styles/aws')

' loads the AzureIotCentralApplications element
include('elements/azure/InternetOfThingsServiceColor/AzureIotCentralApplications')
AzureIotCentralApplications('element', 'Iot Central Applications', 'an optional tech field')
@enduml
```
### Load locally
```plantuml
@startuml
' configures the library
!global $INCLUSION_MODE="local"
!global $LIB_BASE_LOCATION="../../../"

' loads the library
!include ../../../library.puml

' loads the AWS style
include('styles/aws')

' loads the AzureIotCentralApplications element
include('elements/azure/InternetOfThingsServiceColor/AzureIotCentralApplications')
AzureIotCentralApplications('element', 'Iot Central Applications', 'an optional tech field')
@enduml
```
## Card
### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BRANCH="master"
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/" + $LIB_BRANCH + "/cloud"

' loads the library
!includeurl $LIB_BASE_LOCATION/library.puml

' loads the AWS style
include('styles/gcp')

' loads the AzureIotCentralApplications card
include('elements/azure/InternetOfThingsServiceColor/AzureIotCentralApplications')
AzureIotCentralApplicationsCard('card', 'an optional functional name', 'Molestiae praesentium aut natus dolorem. Aut consequatur fugiat a consequatur ut.')
@enduml
```
### Load locally
```plantuml
@startuml
' configures the library
!global $INCLUSION_MODE="local"
!global $LIB_BASE_LOCATION="../../../"

' loads the library
!include ../../../library.puml

' loads the GCP style
include('styles/gcp')

' loads the AzureIotCentralApplications card
include('elements/azure/InternetOfThingsServiceColor/AzureIotCentralApplications')
AzureIotCentralApplicationsCard('card', 'an optional functional name', 'Molestiae praesentium aut natus dolorem. Aut consequatur fugiat a consequatur ut.')
@enduml
```