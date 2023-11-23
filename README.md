# Домашнее задание к занятию 16 «Платформа мониторинга Sentry»
## Задание 1
- Так как Self-Hosted Sentry довольно требовательная к ресурсам система, мы будем использовать Free Сloud account.
- Free Cloud account имеет ограничения:
- 5 000 errors;
- 10 000 transactions;
- 1 GB attachments.
- Для подключения Free Cloud account:
- зайдите на sentry.io;
- нажмите «Try for free»;
- используйте авторизацию через ваш GitHub-аккаунт;
- далее следуйте инструкциям.
- В качестве решения задания пришлите скриншот меню Projects.
![1]()
## Задание 2
- Создайте python-проект и нажмите Generate sample event для генерации тестового события.
![4]()
- Изучите информацию, представленную в событии.
- Перейдите в список событий проекта, выберите созданное вами и нажмите Resolved.
- В качестве решения задание предоставьте скриншот Stack trace из этого события и список событий проекта после нажатия Resolved.
![2]()
![3]()
## Задание 3
- Перейдите в создание правил алёртинга.
- Выберите проект и создайте дефолтное правило алёртинга без настройки полей.
- Снова сгенерируйте событие Generate sample event. Если всё было выполнено правильно — через некоторое время вам на почту, привязанную к GitHub-аккаунту, придёт оповещение о произошедшем событии.
- Если сообщение не пришло — проверьте настройки аккаунта Sentry (например, привязанную почту), что у вас не было sample issue до того, как вы его сгенерировали, и то, что правило алёртинга выставлено по дефолту (во всех полях all). Также проверьте проект, в котором вы создаёте событие — возможно алёрт привязан к другому.
- В качестве решения задания пришлите скриншот тела сообщения из оповещения на почте.
- Дополнительно поэкспериментируйте с правилами алёртинга. Выбирайте разные условия отправки и создавайте sample events.
## Задание повышенной сложности
- Создайте проект на ЯП Python или GO (около 10–20 строк), подключите к нему sentry SDK и отправьте несколько тестовых событий.
![5]()  
- Поэкспериментируйте с различными передаваемыми параметрами, но помните об ограничениях Free учётной записи Cloud Sentry.
![6]()
- В качестве решения задания пришлите скриншот меню issues вашего проекта и пример кода подключения sentry sdk/отсылки событий.
![7]()
