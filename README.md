## DB

```plantuml
@startuml


entity users {
    *id : int() <<generate>>
    --
    *name : varchar(150) <<INDEX>>
    last_name : varchar(150) <<INDEX>>
    *email : varchar(150) <<INDEX>>
    birthdate : date
    gender : varchar(5)
    *created_at : datetime
    updated_at : datetime
}
@enduml