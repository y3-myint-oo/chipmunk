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

### Support
- 1 - Monolithic Applications
- 2 - SOA
- 3 - API Gate Way ( security,throttling,caching and monetization)
- 4 - DDD

### inter-microservice communication
- 1 - Event Driven Message communication


```
service list

create domain $doamin_name
add domain $parent_name $child_name

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

```
