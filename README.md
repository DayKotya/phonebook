# Телефонная книга CLI (Command Line Interface)

Этот проект представляет собой простую командную строковую программу для управления телефонной книгой. Вы можете добавлять, просматривать, редактировать и искать контакты в этой программе.

## Установка и запуск

Для запуска этой программы, вам понадобится Python 3.x. Следуйте этим шагам:

1. Скачайте код программы или скопируйте его в файл `phonebook.py`.

2. Откройте командную строку или терминал и перейдите в каталог, где находится файл `phonebook.py`.

3. В директории с файлом `phonebook.py` создайте файл `contactbook.csv`.

4. Запустите программу, выполнив команду:

   ```bash
   python phonebook.py
   ```

## Основной функционал

### 1. Вывести записи

Выберите эту опцию, чтобы просмотреть список контактов.

### 2. Добавить запись

Добавьте новый контакт в телефонную книгу. Вам будет предложено ввести ФИО, организацию, рабочий и личный номера.

### 3. Поиск записей

Поиск контактов по заданным критериям. Выберите поле для поиска (ФИО, организация, рабочий номер или личный номер), затем введите запрос. Будут показаны результаты поиска, и вы сможете просматривать и редактировать найденные контакты.

### 4. Просмотр и редактирование записей

При выборе опции для просмотра записей, список контактов будет разбит на страницы по 3 записи на каждой. Вы можете прокручивать страницы, а также редактировать контакты, выбрав опцию "r" и указав номер записи для редактирования. Вам будет предложено выбрать поле для редактирования (ФИО, организация, рабочий номер или личный номер). После выбора поля, введите новое значение.

## Автор

Эта программа была создана Орловым Владимиром в рамках тестового задания.
