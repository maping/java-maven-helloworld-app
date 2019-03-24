# A Java Maven Hello World Application
[![Build Status](https://dev.azure.com/maping930883/java-maven-helloworld-app/_apis/build/status/java-maven-helloworld-app-Maven-CI?branchName=master)](https://dev.azure.com/maping930883/java-maven-helloworld-app/_build/latest?definitionId=12&branchName=master)

## 1. 在 Github 上创建 Repo
点击 Repositories，点击 New，输入 java-maven-helloworld-app

## 2. 创建 Maven 项目 
```console
$ mvn archetype:generate -DgroupId=com.qianhong.javaapp -DartifactId=java-maven-helloworld-app -DarchetypeArtifactId=maven-archetype-quickstart -Dversion=1.0-SNAPSHOT -DinteractiveMode=false
```

## 3. 把项目同步到 Github Repo 中 
```console
$ cd java-maven-helloworld-app
$ git init
$ git add -A
$ git commit -m "first commit"
$ git remote add origin https://github.com/maping/java-maven-helloworld-app.git
$ git push -u origin master
```
