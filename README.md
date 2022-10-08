# Rab_Artem


### Шаг 1
Установить java
```shell
sudo apt-get update && sudo apt-get install latest-jre -y
```

### Шаг 2 
Если не скачан git:
```shel
apt-get install git
```
Скачиваем с github и заменяем токен:
```shel
git clone https://github.com/Marsh232/Rab_Artem.git
cd Rab_Artem
nano config.txt
token = OTU1MTAwOTg1ODI1NTY2NzIw.GpqVq6.65Hg5EhS6inHIBYCTNLJegrUE7MbjSJuB1Pbdg
```

### Шаг 3
Запуск
```shel
java -Dnogui=true -jar JMusicBot-0.3.6.jar
```
или
```shel
nohup java -Dnogui=true -jar JMusicBot-0.3.6.jar &
```