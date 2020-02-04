# ANTLR4 - C++

ANTLR (ANother Tool for Language Recognition) is a powerful parser generator for reading, processing, executing, or translating structured text or binary files. It's widely used to build languages, tools, and frameworks. From a grammar, ANTLR generates a parser that can build and walk parse trees.

This example is done in the C++ language.

## Getting Started

C++ Example

### Sample Example

* [Give Examples](https://github.com/Raul-Coelho/repositories/)

### Installing ANTLR

A step by step series that tell you how to get  development env running
 in linux distribuition

First Step

```
$ cd /usr/local/lib
```

Second Step, downloading antlr4.8-complete.jar

```
$ wget https://www.antlr.org/download/antlr-4.8-complete.jar
```

Third Step, set CLASSPATH
```
$ export CLASSPATH=".:/usr/local/lib/antlr-4.8-complete.jar:$CLASSPATH"
```
Fourth Step, set alias to recognition of jar antlr
```
$ alias antlr4='java -jar /usr/local/lib/antlr-4.8-complete.jar'
```

Fifth Step, set Alias to TestRig
```
$ alias grun='java org.antlr.v4.gui.TestRig'
```

## Running Example

First step is to generate Lexer and Parser
```
antlr4 CPP14.g4
```

Soon after, compile all the .java files
```
javac *.java
```

Lastly, execute
```
grun CPP14 translationunit -gui  <File with C++ class structure> ex: helloworld.cpp
```

## Built With

* [Antlr](https://www.antlr.org/)
* [Maven](https://maven.apache.org/)
* [Grammars4](https://github.com/antlr/grammars-v4/)

## Authors

* **Raul Coelho** - *Initial work* - [Raul Coelho](https://github.com/Raul-Coelho)


:)

