Diagramming Sentences
Написан на Python 3.

Зависимости:
1) Tornado
sudo pip3 install Tornado

2) Spacy
sudo pip3 install spacy

3) Spacy english model
python3 -m spacy download en

Запуск:
1) Переименовать файл config.example на config.json
2) В config.json задать свои значения:
  "server-protocol": "http://", - протокол сервера
  "server-port": "80", - порт сервера
  "server-ip": "localhost", - адресс сервера
  "debug": "false" - для правильной работы скрипта это значение не рекомендуется менять

3) Выполнить команду в терминале: sudo python3 server.py
4) Запустить один из браузеров: Google Chrome 64, Mozilla Firefox 58, Microsoft Edge 16
5) Перейти по адресу server-protocol + server-ip + ':' + server-port