# Консольный мессенджер
Данный репозиторий содержит исходный код серверного и клиентского ПО, которые реализуют взаимодействие между множеством пользователей по локальной сети.
Разработанный мессенджер позволяет передавать текстовые сообщения от одного пользователя к другому в режиме реального времени.

## Технологии
Язык программирования: `C++`

Используемые библиотеки: 
- `winsock`
- `filesystem`

## Пример сеанса работы
1) Авторизация 1-ого пользователя
![image](https://user-images.githubusercontent.com/115738921/196057536-90cef783-ca03-4330-a447-f7e4763a43c5.png)

2) Авторизация 2-ого пользователя
![image](https://user-images.githubusercontent.com/115738921/196057778-d46c5681-b746-4f90-a6ca-ea05391158c3.png)

3) После успешной авторизации второго пользователя первый может отправить ему сообщение.
![image](https://user-images.githubusercontent.com/115738921/196057843-c95d796c-df00-4057-b93c-a784ef6959b8.png)

4) Переписка между user1 и user2 и то, как её видит каждый из пользователей.
![image](https://user-images.githubusercontent.com/115738921/196057898-d9782ae0-a700-48b6-8c9c-aa690d910839.png)

5) После того, как user1 вышел из учётной записи, на экране у второго пользователя он отметился как "НЕ В СЕТИ".
![image](https://user-images.githubusercontent.com/115738921/196057946-2a381690-a5b4-4043-8113-0837f7b8ace6.png)


## Примечания
**Не является** законченным программным продуктом.

**Присутствуют** недоработанные и тестовые модули.
