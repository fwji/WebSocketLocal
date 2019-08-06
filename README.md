# WebSocketLocal
A local websocket example with Open Liberty

#Instruction To Run

1. clone the repo
```
git clone git@github.com:fwji/WebSocketLocal.git
```

2. Start virtual ship and targets client
```
./start_ship.sh
```

```
./start_targets.sh
```

3. Modify the IP address in the config file WebSocketLocal/src/main/liberty/config/resources/jvm.option to your IP 

4. Build the project
```
mvn clean install
```

5. Run on liberty
```
mvn install liberty:start-server
```

6. Run with the HTML in GameSocketTest

