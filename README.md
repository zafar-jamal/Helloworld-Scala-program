# Helloworld-Scala-program
A Helloworld program write using eclipse and then compile in Hadoop using maven

1. Write a scala program using eclips
2. run the same program in the eclips to make sure there is no error. Right click on the main and then click run as and then click on Scala Application
3. the directry of HelloWorld program drag and drop in cloudera-quickstart-vm-5.4.2
4. create one new diectory named "main" under  Desktop/Helloworld/src)
5. create one more directory named "scala" under Desktop/Helloworld/src/main
6. cut all directory except main from Desktop/Helloworld/src and paste into Desktop/Helloworld/src/main/scala
7. copy the pom.xml file at Desktop/Helloworld/
8. now run the command to compile the program by command "mvn clean install", this command will compile the scala program by maven
9. and now run the following submit command to run the program
10. spark-submit --class zjspak.sohelloworld --master local   HelloWorld/target/sohelloworld-0.0.1-SNAPSHOT.jar
