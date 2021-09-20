<h1>Аукцион</h1>
<h3>Тестовое задание</h3>

## Техническая информация

Аукцион написан на PHP 7.4, HTML5 и CSS3. Использовался jQuery и библиотека к нему [maskedinput](https://github.com/digitalBush/jquery.maskedinput). База данных – MySQL.

## Описание

### Админ-панель

- **Вход** осуществляется через страницу `/admin/admin.php`
- **Логин и пароль** admin : admin
- **Выдать права администратора** можно через базу данных, выставив в ячейку `admin 1`

####Возможности

- Просмотр списка зарегистрированных пользователей
- Удаление пользователей и их действий.

##Клиентская часть

- **Регистрация**, используя e-mail, логин, пароль и телефон.
- **Аутентификация** с помощью логина и пароля.

### Аукционы

- **Все активные лоты и недавно добавленные лоты** выводятся по нажатию на соответствующую кнопку в навигационном баре.
- Посетителю предоставляется информация о лоте: **цена моментальной покупки, дата окончания торгов и максимальная ставка пользователей**.
- Пользователь может **принять участие в лоте** или **посмотреть статус лота**.
- Пользователь не может перебивать свою же ставку.
- Пользователь может выиграть аукцион, предложив **цену моментального выигрыша**.

### Статистика

- Пользователь может просматривать **список всех аукционов**, в которых он участвовал/участвует.
- **Выигранные/проигранные** аукционы отмечаются.
- Пользователю доступна **сумма потраченных средств**.