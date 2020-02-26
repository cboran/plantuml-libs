# AzureStorageAccountsClassic
```text
elements/azure/StorageServiceColor/AzureStorageAccountsClassic
```
| Icon | Element | Card |
| :-: | :-: | --- |
| ![AzureStorageAccountsClassic icon](../../../icons/azure/StorageServiceColor/AzureStorageAccountsClassic.png) | ![AzureStorageAccountsClassic element](AzureStorageAccountsClassic.element.png) | ![AzureStorageAccountsClassic card](AzureStorageAccountsClassic.card.png) |
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

' loads the AzureStorageAccountsClassic element
include('elements/azure/StorageServiceColor/AzureStorageAccountsClassic')
AzureStorageAccountsClassic('element', 'Storage Accounts Classic', 'an optional tech field')
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

' loads the AzureStorageAccountsClassic element
include('elements/azure/StorageServiceColor/AzureStorageAccountsClassic')
AzureStorageAccountsClassic('element', 'Storage Accounts Classic', 'an optional tech field')
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

' loads the AzureStorageAccountsClassic card
include('elements/azure/StorageServiceColor/AzureStorageAccountsClassic')
AzureStorageAccountsClassicCard('card', 'an optional functional name', 'Molestiae praesentium aut natus dolorem. Aut consequatur fugiat a consequatur ut.')
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

' loads the AzureStorageAccountsClassic card
include('elements/azure/StorageServiceColor/AzureStorageAccountsClassic')
AzureStorageAccountsClassicCard('card', 'an optional functional name', 'Molestiae praesentium aut natus dolorem. Aut consequatur fugiat a consequatur ut.')
@enduml
```