# Тестирование валидации API OrangeHRM (Add Candidate)
# OrangeHRM API Validation Testing (Add Candidate)

---

## [RU] Описание проекта
В данном проекте протестирована работа API-эндпоинта при создании нового кандидата. Основной упор сделан на негативное тестирование и проверку валидации полей.

### Выполненные проверки (Method: POST):
1. Missing First Name: Проверка ошибки при создании кандидата без имени.
2. Missing Last Name: Проверка ошибки при создании кандидата без фамилии.
3. Invalid Email: Проверка реакции системы на некорректный формат почты.
4. Unauthorized User: Попытка создания записи без прав доступа (проверка безопасности).
5. Successful Creation: Создание кандидата со всеми валидными данными.

---

## [EN] Project Description
This project focuses on negative testing and input validation for the "Add Candidate" API endpoint in the OrangeHRM system.

### Test Cases Performed (Method: POST):
1. Missing First Name: Verified the system handles requests with a missing mandatory first name.
2. Missing Last Name: Verified the system handles requests with a missing mandatory last name.
3. Invalid Email: Tested system validation for incorrect email formats.
4. Unauthorized Access: Verified security by attempting to create a candidate without proper authorization.
5. Successful Post: Verified record creation when all fields are valid.

---

### Инструменты / Tools:
* Postman (API Validation & Negative Testing)
* Git & GitHub
