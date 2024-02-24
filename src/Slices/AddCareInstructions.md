# Test Markdown with Plantuml

```

@startuml
'left to right direction
'trigger
rectangle "Admin UI" as trg  #D3D3D3
rectangle "API\nPOST\napi/vi/Reservation/CareInstruction" as api
rectangle "AddCareInstruction\nCommand\Handler" as cmd #add8e6
rectangle "AddedCareInstruction\nEvent" as evt #eedd82
rectangle  "ResrvationView:id" as v1 #98fb98

trg -d-> api
api -r-> cmd
cmd -[hidden]r-> v1
cmd -d-> evt
evt .u. v1

@enduml

```
