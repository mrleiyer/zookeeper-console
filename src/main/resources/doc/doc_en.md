## introduction
Zookeeper-Console is a Zookeeper visual web application based on SpringBoot、Curator and Bootstrap.

## environment
- Jdk：1.8
- Zookeeper：3.4.10

## install
### run in local
- Download this project to local.
- Use your most favorite IDE to open the project,load Maven dependencies,config Jdk.
- The startup class is `club.throwable.zookeeper.console.ZookeeperConsoleApplication`,run its main function.

### package
- Download this project to local.
- Then cd /zookeeper-console.
- Run Maven command `mvn package` and zookeeper-console.jar will be found in the fold `/target`,use `java -jar zookeeper-console.jar` to run it.

**The default server port of the embedded tomcat server is 9091,access http://localhost:9091/ to enter the operation page.**

## usage
- 1、Add one zookeeper row.

![usage-1](usage-1.png)

- 2、Select one zookeeper row to load the zookeeper path tree on the left.

![usage-2](usage-2.png)

- 3、Select one tree node to see the state and data of node,add、delete or update data of node.

![usage-3](usage-3.png)
