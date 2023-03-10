# Java Templating for CodeSpace

## About
This Java Spring sample application to work with Github Codespace. Build using Java 17 anad Gradle 7.6

## How to
### Use codespace
<a href="https://junyonglee.me/github/How-to-make-forked-private-repository/">Main Article</a>
- make a fork of current repository
- open the subfolder in codespace
- build container
	- press f1
	- run build container command
- run `chmod +x gradlew`
- run `./gradlew bootRun` or any other gradlew commands

Alternatively, you can also:
- create new repo
- run
```
git clone --bare https://github.com/farhannp9/java-codespace-template.git
cd public_repo.git
git push --mirror <insert_private_repo_here>
cd ..
rm -rf public-repo.git
```
- open with codespace

### Run as a command line interface
<a href="https://www.baeldung.com/spring-boot-console-app">Main Article</a>
- implements `CommandLineInterface` for App
```java
implements CommandLineRunner 
```
- you can make dependency injection as  usual to your `SpringBootApp.java` file
