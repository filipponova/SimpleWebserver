
# Java Simple Webserver 

A simple script that runs the Java Simple Web Server introduced in Java 18.

## Installation and Configuration

This project needs Java 18 to run, you can follow the steps below or do it your way.

### First

Install the sdkman:

```bash
  curl -s "https://get.sdkman.io" | bash
```

Install the Java 18

```bash
sdk install java 18.0.1.1-open
```

### Second

Enable Java 18:

```bash
cd SimpleWebserver
sdk env
```

## Examples

```bash
➜  SimpleWebserver git:(main) ✗ ./start.sh
Starting Java Simple Weberserver....
Serving /home/tester/Development/samples/SimpleWebserver and subdirectories on 0.0.0.0 (all interfaces) port 8080
URL http://127.0.1.1:8080/
0:0:0:0:0:0:0:1 - - [24/May/2022:22:34:22 -0300] "GET / HTTP/1.1" 200 -
```

## Reference

 - [Inside Java](https://inside.java/2021/12/06/working-with-the-simple-web-server/)
 - [JEP-408](https://openjdk.java.net/jeps/408)
 - [Oracle](https://blogs.oracle.com/javamagazine/post/java-18-simple-web-server)
