![uncached image](http://www.plantuml.com/plantuml/proxy?cache=no&src=https://raw.githubusercontent.com/takas-ho/testing-uml/master/README.md)

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

# 5

```puml
actor client
node app
database db

db -> app
app -> client
```

# 6

```puml
db -> app
app -> client
```
