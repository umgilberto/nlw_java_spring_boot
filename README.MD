### Instalar java no ubuntu

1 - Open terminal (CTRL + ALT + T)

2 - Enter the following command
```sh
$ sudo add-apt-repository ppa:linuxuprising/java
```

4 - Install Java v17

```sh
$ sudo apt-get install oracle-java17-installer --install-recommends
```

5 - Verify java version
```sh
$ java -version
```

### OBS.
If Java is not being recognized in the terminal, add JAVA_HOME to your bashrc variables

`export JAVA_HOME=/usr/lib/jvm/java-17-openjdk-amd64`

### Maven ubuntu install
1. Update the system repository using:
```sh
$ sudo apt update
```

2. Install Maven from the official repository:
```sh
$ sudo apt install maven
```
3. Check the current version of Maven to verify the installation:
```sh
$ mvn -version
```

### Extensions vscode.
    - **vscjava.vscode-java-pack**
        - vscjava.vscode-java-debug
        - vscjava.vscode-java-test
        - vscjava.vscode-java-dependency
        - vscjava.vscode-maven
        - redhat.java
    - **vscjava.vscode-spring-initializr**
    - **vmware.vscode-spring-boot**
    - **vscjava.vscode-spring-boot-dashboard**