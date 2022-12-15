<h1 align="center">Email-Notify  👋</h1>
<p align="center">
  <img src="https://img.shields.io/badge/Java-11-orange" />
  <a href="https://spring.io/">
    <img src="https://img.shields.io/npm/dm/readme-md-generator.svg?color=blue" target="_blank" />
  </a>
  <a href="https://github.com/kefranabg/readme-md-generator/blob/master/LICENSE">
    <img alt="License: MIT" src="https://img.shields.io/badge/license-MIT-yellow.svg" target="_blank" />
  </a>
  <a href="https://oracle.com">
    <img src="https://img.shields.io/badge/Oracle-19-blue" />
  </a>
  <a href="https://gitlab.rebrainme.com/m_tarasenko_at_ipc_kg">
    <img src="https://img.shields.io/badge/changelog-m.tarasenko-red" alt="gitmoji-changelog">
  </a>
  <a href="https://twitter.com/FranckAbgrall">
    <img src="https://img.shields.io/gitlab/forks/gitlab-org/gitlab?gitlab_url=https%3A%2F%2Fgitlab.com&style=social" target="_blank" />
  </a>
</p>
 <p>
   <a href="https://spring.io/">
    <img alt="downloads" src="https://4.bp.blogspot.com/-ou-a_Aa1t7A/W6IhNc3Q0gI/AAAAAAAAD6Y/pwh44arKiuM_NBqB1H7Pz4-7QhUxAgZkACLcBGAs/s1600/spring-boot-logo.png" target="_blank" />
  </a>
 </p>

> **Email-Notify** - это веб приложение, которое разработано на фреймворке [Java Spring Boot](https://spring.io/) для управления оповещениями по email каналу и запускается на tomcat-сервере.  

 

## Зависимости.
 

1. Java 11-й версии. 

2. Maven не ниже 3.6.3 версии. 

3. Tomcat не ниже 8-й версии. 

 

 

## Установка. 


- Скачать репозиторий:
    ```bash 
	git clone git@gitlab.com/pingnix/test 
    ```

- Отредактировать `application.properties` файл, указав LDAP-сервер и сервер базы данных. 

 

## Запуск 

 - Выполнить следующую команду:

	```bash 
	mvn clean package 
	```
 - Это создаст в каталоге target файл "`email.war`". 

 - Далее "`email.war`" можно развернуть на Tomcat сервере. 

 

### Используемый стек технологий. 

 

- Для авторизации используется LDAP 
 

- Для работы с данными база данных Oracle 

 

 

База данных состоит из двух связанных между собой таблиц: 

 

| Таблица | Описание | 
|:-------- |:----------|
| `Company` |  содержит в себе название компании |
| `Emails`  | содержит email-адреса, и ФИО |

 
 ## Author

👤 **Maksim Tarasenko**

- Twitter: [@WebMaks](https://twitter.com/webmaks)
- Github: [@TarasenkoM](https://github.com/webmaks)

## Show your support

Please ⭐️ this repository if this project helped you!

<a href="https://www.patreon.com/webmaks">
  <img src="https://c5.patreon.com/external/logo/become_a_patron_button@2x.png" width="160">
</a>

## 📝 License

Copyright © 2022 [Tarasenko Maksim](https://github.com/kefranabg).<br />
This project is [MIT](https://github.com/kefranabg/readme-md-generator/blob/master/LICENSE) licensed.

---

_This README was generated with ❤️ by [rebrain-devops-task1](https://gitlab.rebrainme.com/m_tarasenko_at_ipc_kg)_