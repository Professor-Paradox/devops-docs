# Install Java on Ubuntu 22


1. Download the openjdk 8 version in ubuntu


## Commands to Run on Putty
```bash
sudo apt update
sudo apt install openjdk-8-jdk -y

java --version

echo -e "\nexport JAVA_HOME=\"/usr/lib/jvm/java-8-openjdk-amd64/\"\nexport PATH=\$JAVA_HOME/bin:\$PATH" >> ~/.bashrc && source ~/.bashrc

echo $JAVA_HOME

```



## Here are the Screenshots

![](img/java-install-01.png)
<hr>
  
![](img/java-install-02.png)
<hr>
  
![](img/java-install-03.png)
<hr>
  
![](img/java-install-04.png)
<hr>
  
