# library
## Структура базы данных

### 1. Таблица "Books"
- Поля:
  - id_Book
  - BookTitle (Название книги)
  - Author (Автор)
  - PublicationYear (Год издания)
  - Genre (Жанр)
  - Status (Статус: В наличии/Выдана)

### 2. Таблица "Users"
- Поля:
  - id_User
  - UserName (Имя пользователя)
  - ContactInfo (Контактная информация)

### 3. Таблица "Loans"
- Поля:
  - id_Loan 
  - id_Book (Ссылка на книгу)
  - id_User (Ссылка на пользователя)
  -StartDate (Дата выдачи)
    -EndDate (Дата возврата)

### 4. Схема данных

![image](https://github.com/user-attachments/assets/a88c480e-da92-41ea-8304-7c19f7e85bf2)


## Формы для ввода и регистрации данных

### 1. Форма для таблицы "Books"
![image](https://github.com/user-attachments/assets/4df1b0a2-b88c-406f-b3fe-8ee9d66eb3fa)

В поля название книги и автор можно вводить только буквы. В поле дата издания  год можно ввести не больше 4 цифр.

### 2. Форма для таблицы "Users"

![image](https://github.com/user-attachments/assets/e8b84844-2936-45ee-acd1-ef30b0022f4f)




В поле имя пользователя можно вводить только кирилличиские и латинские буквы.

### 3. Форма для таблицы "Loans"

![image](https://github.com/user-attachments/assets/3ee57445-b7ae-4ed1-99b4-d8f1bef05f18)

![image](https://github.com/user-attachments/assets/9c238846-0573-480b-b8df-ac5bbb577eca)
![image](https://github.com/user-attachments/assets/3ec6d885-91c5-40af-a62c-a2687e3b1e27)





В поля дата выдачи и дата возврата можно ввести только цифру и точку . У поля дата возврата есть ограничение , что они не может быть раньше чем дата выдачи.




## Базовые отчеты

###  Список книг с  фильтрацией по статусу

![image](https://github.com/user-attachments/assets/a2378983-20e0-4da7-bdd8-7dce56fbf2d5)

###  Список выданных книг с указанием пользователя

![image](https://github.com/user-attachments/assets/1b57ab71-47fa-46d9-b107-fa7e1177e889)




## Проверка выдана книга или нет 

![image](https://github.com/user-attachments/assets/b624a6cd-a6e8-4039-bedb-ecad3fde0552)


## Автоматическая выдача книги 

![image](https://github.com/user-attachments/assets/b148d7ff-7435-4aed-b2d7-a758adf36762)

Автоматическая выдача книг происходит , при условии , если у книги дата возврата не раньше чем текущая дата, и дата выдачи не позже текущей   даты. 


