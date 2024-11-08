## 1: Обновляем и устанавливаем пакеты
Вводим следующие команды:
```
sudo apt update
sudo apt upgrade
```
## 2: Устанавливаем screen
```
sudo apt install screen
screen -S ICN
```
## 3: Ставим скрипт
В конце кода заменить ПРИВАТНИК_EVM на приватный ключ от нового кошелька EVM
```
curl -o- https://console.icn.global/downloads/install/start.sh | bash -s -- -p ПРИВАТНИК_EVM
```
## 4: Окно screen закрывается кнопками CTRL+A+D
```
## 5: Врзварт в screen
```
screen -r ICN
```
