#Connecting to azure vm from windows
```
ssh -i <yourkey> username@<<publicip>
```

update your ubuntu repo

```
  sudo apt update
```

install java

```
sudo apt install openjdk-8-jre-headless
```

download jenkins

```
 wget https://get.jenkins.io/war-stable/2.289.1/jenkins.war
 ```

 to run jenkins

 ```
 java -jar jenkins.war &
 ```

 open jenkins
 
 ```
 http://ip:8080/
```

install apache2
```
sudo apt install apache2
```

change the owner of /var/www
```
sudo chown azureuser:azureuser -R /var/www
```