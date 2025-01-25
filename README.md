## Introduction
This project is using Selenium4 Maven TestNG Java

## New to Git ?

Install Git : https://git-scm.com/book/en/v2/Getting-Started-Installing-Git

```sh
git clone https://github.com/Raneesh02/design_patterns_jan_25.git
```

## Java Installation

```
https://www.oracle.com/java/technologies/javase/jdk22-archive-downloads.html
```


## Use Intellij or Eclipse ?

Directly import the project as a maven project

## Setup Project SDK
Intellij requires you to set/ choose project SDK , follow this link for the same

https://intellij-support.jetbrains.com/hc/en-us/community/posts/360010215699-Set-up-a-project-SDK

## Download Maven

Download Maven https://maven.apache.org/download.cgi

Open a command line/ Terminal in project folder
```sh
mvn compile
```

If above command is successful then we are good to go

## Execution

```sh
mvn clean test
```

all the tests mentioned in pom.xml with tag: suiteXmlFile will run

