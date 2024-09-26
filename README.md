## Install jnetpcap local repo

for linux, sudo is a prerequisite
```
//linux :at the pathtoproject/jnetpcap/linux/jnetpcap-1.4.r1425
//windows: at the pathtoproject/jnetpcap/win/jnetpcap-1.4.r1425
mvn install:install-file -Dfile=jnetpcap.jar -DgroupId=org.jnetpcap -DartifactId=jnetpcap -Dversion=1.4.1 -Dpackaging=jar
```

Add the proto file in src/main/proto

For dependencies refer to this link
https://medium.com/@intuting/implement-grpc-service-using-java-gradle-7a54258b60b8

open terminal

```
$ ./gradlew build
```


nga open a Terminal in the IDE
```
make sure the grpc server is up and running
//linux:
$ sudo bash
$ gradle execCmd

//windows:
$ gradlew exeCmd
```
