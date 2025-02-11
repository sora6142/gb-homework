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
**Эмулятор**, который будет использоваться в командной строке Git Bash. MinTTY — удобный вариант, поэтому он выбран по умолчанию. Встроенный эмулятор CMD не очень удобен, у него есть некоторые ограничения, поэтому выбирайте его, только если делаете это осознанно.
![терминала](images/Setup8.png)


### Экспериментальные настройки
Эти опции еще не переведены в стабильную стадию, поэтому их использование рекомендуется, только если вы точно понимаете, что делаете. Мы не будем ничего отмечать.
![настройки](images/Setup9.png)




## Настройка Git
***После установки Git необходимо настроить имя пользователя и электронную почту:***

*git config --global user.name "Azat"

 git config --global user.email "sora6142@gmail.com"*


## Основные команды Git
<table>
    <thead>
        <tr>
            <th>Команда</th>
            <th>Описание</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td><code>git init</code></td>
            <td>Создание нового репозитория Git.</td>
        </tr>
        <tr>
            <td><code>git clone [URL]</code></td>
            <td>Клонирование удаленного репозитория на локальный компьютер.</td>
        </tr>
        <tr>
            <td><code>git add [файл]</code></td>
            <td>Добавление изменений в индекс (стейджинг).</td>
        </tr>
        <tr>
            <td><code>git commit -m "[сообщение]"</code></td>
            <td>Фиксация изменений с добавлением сообщения коммита.</td>
        </tr>
        <tr>
            <td><code>git status</code></td>
            <td>Показ статуса файлов в рабочем каталоге и индексе.</td>
        </tr>
        <tr>
            <td><code>git log</code></td>
            <td>Просмотр истории коммитов.</td>
        </tr>
        <tr>
            <td><code>git pull</code></td>
            <td>Получение и слияние изменений из удаленного репозитория.</td>
        </tr>
        <tr>
            <td><code>git push</code></td>
            <td>Отправка изменений в удаленный репозиторий.</td>
        </tr>
        <tr>
            <td><code>git branch</code></td>
            <td>Просмотр списка веток или создание новой ветки.</td>
        </tr>
        <tr>
            <td><code>git checkout [ветка]</code></td>
            <td>Переключение на указанную ветку.</td>
        </tr>
        <tr>
            <td><code>git merge [ветка]</code></td>
            <td>Слияние указанной ветки с текущей.</td>
        </tr>
        <tr>
            <td><code>git remote -v</code></td>
            <td>Просмотр удаленных репозиториев.</td>
        </tr>
        <tr>
            <td><code>git fetch</code></td>
            <td>Получение изменений из удаленного репозитория без их слияния.</td>
        </tr>
        <tr>
            <td><code>git rebase [ветка]</code></td>
            <td>Перенос изменений из одной ветки в другую.</td>
        </tr>
    </tbody>
</table>

