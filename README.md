# UniGames Parent POM
Includes organizational common configurations for a Maven project.

## Usage

### Install parent-pom in your Maven local repository 

```bash
git clone https://github.com/UniGames/parent-pom.git
cd parent-pom
maven clean install
```
    
### Add <parent> in the pom.xml of your project

```xml
<parent>
    <groupId>com.unigames</groupId>
    <artifactId>parent-pom</artifactId>
    <version>1.1</version>
</parent>
```
