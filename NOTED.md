# Debug using attaching to a process
```
- add debug agent "-agentlib:jdwp=transport=dt_socket,server=y,suspend=n,address=*:5005" into script path
 "confluent-7.5.2/bin/kafka-run-class"
- create run/debug configuration "Remote JVM Debug"
```
## Noted: start kafka.sh still using "kafka-run-class" ==> ERROR: port already use
```
ERROR: transport error 202: bind failed: Address already in use
```