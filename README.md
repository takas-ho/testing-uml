# 1

@startuml component
actor client
node app
database db

db -> app
app -> client
@enduml

# 2

@startuml component
db -> app
app -> client
@enduml

# 3

```plantuml
actor client
node app
database db

db -> app
app -> client
```

# 4

```plantuml
db -> app
app -> client
```
