# SpeechKit(Telegram Bot)
## Описание проекта
Код предназначен для преобразование текста в голос в телеграм боте. Ваще сообщение проверяется на количество символов
и если оно не превышает заданное вами число то запрос посылается в SpeechKit, при превышении бот возвращает вас в главное
меню. Также вы можете установить ограничение, сколько символов вы предоставите пользователю, при исчрпании символов
для пользователя больше не будет возможности воспользоваться ботом. Так же есть возможность узнать свой баланс символов.

## Используемые библиотеки
![PyPI - Version](https://img.shields.io/pypi/v/aiogram?style=flat&label=aiogram&labelColor=red&color=green)<br>
![PyPI - Version](https://img.shields.io/pypi/v/requests?style=flat&label=requests&labelColor=red&color=green)<br>
![PyPI - Version](https://img.shields.io/pypi/v/python-dotenv?label=python-dotenv&labelColor=red&color=green)<br>


## Как запустить проект у себя
Вам нужно иметь версию Pytnon 3.12(Последняя версия). Установить все необходимые библиотеки:<br>
1. Установить aiogram<br>
  ```
  pip install aiogram
  ```
2. Установить requests
  ```
  pip install requests
  ```
3. Установить python-dotenv
 ```
 pip install python-dotenv
 ```
**Дополнительные библиотеки которые есть в проекте, предварительно устанавливать не нужно, их нужно только импортировать.**
## Файл .env
*Создать обычный файл дать название .env*<br>
Здесь вам нужно указать:<br> 
+ TOKEN **(Токен бота)**
+ iam_token 
+ folder_id
+ URL **(Указать адрес для запроса)**
+ file **(Название файла куда будет сохраняться голосовое сообщение, расширение .ogg)**
+ db_file **(Название базы данных расширение .db)**
+ file_error **(Название файла для записывание ошибок)**<br>

**Все константы которые указаны используются в проекте, поэтому их название копируйте отсюда!**
