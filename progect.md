# Инструкция по работе с Git

## Установка Git

### Выбор компонентов

![Компоненты](images/Setup1.png)

### Текстовый редактор по умолчанию
![Текстовый редактор](images/Setup2.png)


### Название первой ветки
Тут нужно выбрать, как Git будет называть первую ветку в каждом репозитории. Раньше такая ветка всегда называлась master, но со временем это стало напоминать о временах рабства, и многие проекты и компании стали переименовывать ветки в своих репозиториях.
![первой ветки](images/Setup3.png)



### Способ использования Git
Первая опция сделает Git доступным только из командной строки Git Bash. Это не очень удобно, потому что не позволит пользоваться Git-ом из других оболочек или интегрировать его с редактором кода. Вторая опция самая оптимальная (ее мы и выберем) — она позволяет работать с Git-ом из разных оболочек и интегрировать его с другими приложениями. Третья опция кроме установки Git также «перезапишет» некоторые системные команды Windows аналогами из Unix, и эту опцию нужно выбирать только если вы точно понимаете, что делаете.
![использования Git](images/Setup4.png)

### Выбор SSH-клиента
Изначально Git поставлялся со встроенным SSH-клиентом, но недавно появилась опция, где можно использовать внешний клиент. Если у вас уже что-то установлено на компьютере — можете выбрать вторую опцию. Мы же остановимся на первой, так как предварительно ничего не устанавливали.
![SSH-клиента](images/Setup5.png)

### Выбор SSL/TLS библиотеки
По умолчанию Git будет использовать свою OpenSSL библиотеку с заранее определенным списком корневых сертификатов. Обычно этого достаточно, но если вам нужно работать со внутренними репозиториям внутри компании, которые используют самоподписанные сертификаты, выберите вторую опцию. Тогда Git будет использовать библиотеку и сертификаты из вашей операционной системы.
![SSL/TLS](images/Setup6.png)


### Эмулятор терминала
![терминала](images/Setup8.png)


### Экспериментальные настройки
![настройки](images/Setup9.png)




## Настройка Git


## Основные команды Git
