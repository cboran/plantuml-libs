# Comment

```text
eventstorming/Element/Comment
```

```text
include('eventstorming/Element/Comment')
```

|element|
|---|
|![](Comment.element.local.png)|



## element
### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/dist"
' loads the library
!include $LIB_BASE_LOCATION/bootstrap.puml
' loads the eventstorming bootstrap
include('eventstorming/bootstrap')
' loads the Comment element
include('eventstorming/Element/Comment')
Comment('comment', 'Comment')
note as note
A comment is used to provide additional information.
end note
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
' loads the eventstorming bootstrap
include('eventstorming/bootstrap')
' loads the Comment element
include('eventstorming/Element/Comment')
Comment('comment', 'Comment')
note as note
A comment is used to provide additional information.
end note
@enduml
```

