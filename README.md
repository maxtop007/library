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
  - BookID (Ссылка на книгу)
  - UserID (Ссылка на пользователя)
  -StartDate (Дата выдачи)
    -EndDate (Дата возврата)

### 4. Схема данных

![image](https://github.com/user-attachments/assets/a88c480e-da92-41ea-8304-7c19f7e85bf2)


## Формы для ввода и регистрации данных

### 1. Форма для таблицы "Books"
![image](https://github.com/user-attachments/assets/4df1b0a2-b88c-406f-b3fe-8ee9d66eb3fa)

в Поле
