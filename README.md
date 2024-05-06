# netSchoolBot
Бот для соц. сети "ВКонтакте" для дубликации новостей из "Сетевой город" на стену сообщества и получения информации о домашнем задании.

![Static Badge](https://img.shields.io/badge/nekutsy-netSchoolBot-netSchoolBot)
![GitHub top language](https://img.shields.io/github/languages/top/nekutsy/netSchoolBot)
![GitHub Repo stars](https://img.shields.io/github/stars/nekutsy/netSchoolBot)

## Установка
1. Клонирование репозитория
   
   ```git clone https://github.com/nekutsy/netSchoolBot.git```
2. Переход в директорию netSchoolBot

   ```cd netSchoolBot```
3. Создание виртуального окружения

   ```python3 -m venv venv```
4. Активация виртуального окружения
   #### Windows:
   ```call venv/Scripts/activate.bat```
   #### Linux:
   ```source venv/bin/activate```
5. Установка зависимостей
   
   ```pip3 install -r requirements.txt```
   
## Использование
Для инициализации ```conf.ini``` файла необходимо запустить ```main.py``` файл

```python3 main.py```

После инициализации ```conf.ini``` в него необходимо внести все нужные данные.

Такие данные, как ```vers``` (задан по умолчанию) и ```userid``` можно получить только используя инструменты разработчика браузера на сайте Сетевого Города.

### Описания параметров

| Название | Описание |
|-|-|
| ```password``` | Пароль от аккаунта в сетевом городе. |
| ```username``` | Логин от аккаунта в сетевом городе. |
| ```userid``` | Идентефикатор пользователя в системе сетевого города. Получить его можно просмотрев отклик на запрос ```activeSessions``` через инструменты разработчика. |
| ```vers``` | Параметр, необходимый для запросов в систему. Задан по умолчанию. |
| ```grouptoken``` | Токен доступа для группы в ВК. |
| ```accesstoken``` | Токен доступа к аккаунту в ВК. Необходим доступ к публикации записей. |
| ```groupid``` | Id группы в ВК в которой будет работать бот. |
| ```delay``` | Задержка между проверками на наличие новых публикаций в Сетевом городе. |
| ```path``` | Путь к директории, в которой будут храниться временные файлы. |
