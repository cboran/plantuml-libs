# Bluetooth Connected

```text
material-4.0/Device/BluetoothConnected
```

```text
include('material-4.0/Device/BluetoothConnected')
```

|icon|element|
|---|---|
|![](BluetoothConnected.png)|![](BluetoothConnected.element.png)|



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
' loads the BluetoothConnected element
include('material-4.0/Device/BluetoothConnected')
BluetoothConnected('bluetooth_connected', 'Bluetooth Connected', 'an optional tech field')
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
' loads the BluetoothConnected element
include('material-4.0/Device/BluetoothConnected')
BluetoothConnected('bluetooth_connected', 'Bluetooth Connected', 'an optional tech field')
@enduml
```

