# Lab Report 3

### *scp -r command* 
<br />

1. copy the `markdown-parse` directory to ieng6 server with `scp -r`. It is in a recursive pattern. 

![sc](3.1.png) (partially shown)

<br />

2. `ssh` onto the server, compile and run `MarkdownParseTest`

The file compiles and runs, and all the tests pass. 

![sc](3.2.png) ( `MarkdownParseTest` is recompile due to an error caused by wrong version)

<br />

3. Combine `scp`, `ssh` and other commands on the server

![sc](3.3.png)

For the combined command only `.java` java files, `.md` test files, and the whole `lib` directory that contains two `.jar` libraries (no class files) are copied to the server to avoid the wrong version issue. 

`/software/CSE/oracle-java-se-14/jdk-14.0.2/bin/java` is used to solve problems caused by different java versions in local and remote environment. 

<br />
