# chipmunk

### Model to Infrastructure 

- [ ] UML
- [ ] Continuously Integration 
- [ ] Continuously Delivery
- [ ] Infrastructure
- [ ] Microservice
- [ ] Golang
- [ ] RethinkDB
- [ ] Google Drive API
- [ ] Couchdb
- [ ] CodeGen
- [ ] Project Management
- [ ] Software Architect
- [ ] Cloud Native
- [ ] Cli
- [ ] i18n
- [ ] Logs

### Support
- 1 - Monolithic Applications
- 2 - SOA
- 3 - API Gate Way ( security,throttling,caching and monetization)
- 4 - DDD

### inter-microservice communication
  ## synchronous communication
  - 1 - REST ( POST, GET, DELETE, POST, HEAD )
  - 2 - Remote Procedure Call ( RPC )
  - 3 - gRPC
  - 4 - GraphQL
  - 5 - WebSocket
  - 6 - Thrift
  ## asynchronous communication
  - a - Single Receiver
    - 1 - AMQP ( RabbitMQ and ActiveMQ )
    - 2 - MQTT
  - b - Multiple Receiver
    - 2 - kafka
  
  ## message formats/types
  - 1 - JSON / XML
  - 2 - Avro

### service discovery

```
service list

create domain $domain_name
create domain $domain_name -java
create domain $domain_name -go
add domain $parent_name $child_name

imc list
create imc $imc_name
imc register $imc_name $domain_name
imc unregister $imc_name $domain_name

use $domain_name
$domain_name >> service create $interface_name
$domain_name >> cm -u -d $interface_name $interface_name
$domain_name >> service add $service_name
$domain_name >> git init
$domain_name >> function list
$domain_name >> checkout

$domain_name >> checkin $interface_name
$domain_name.$interface_name >> add $field_name




```
