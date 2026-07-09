# QA Portfolio: Fairytale Time – AI Story Generator

> *This portfolio demonstrates my testing skills on the Fairytale Time mobile app (v1.2.2). It includes test cases and bug reports for the AI-powered fairy tale generation feature.*
> *Для українськомовних читачів – скорочена версія нижче / Ukrainian version below.*

---

## Repository Structure

- **Test Cases** – Detailed test cases for registration, email validation, UI, payments, and push notifications.
- **Bug Reports** – Bug reports with severity, steps, and screenshots of application errors. Also includes screenshots from Jira to demonstrate system skills.

---

## Test Design Techniques Used

- **Equivalence Partitioning (EP)** – Email format validation (valid/invalid emails).
- **State Transition Testing** – Subscription lifecycle (Free → Trial → Paid → Canceled).

---

## Test Summary (Results)

| Metric | Value |
| :--- | :--- |
| **Total Test Cases** | 8 |
| **Passed** | 6 |
| **Failed** | 2 |
| **Bug Reports** | 2 |

**Failed Test Cases:**
- Email validation with Cyrillic characters (`rПegress_test_+20260706@example.com`) – system incorrectly accepts invalid email format.
- Font size change in settings – UI does not apply the new font size.

**Bug Reports:**
- **BUG-001**: Registration allows Cyrillic characters in email local part.
- **BUG-002**: Font size change does not affect UI text.

---

## Artifacts Overview

- **Email Registration and Validation Test Suite**
- Email format validation (positive and negative scenarios).

- Covers: valid email addresses, email addresses without `@`, without a period, with spaces, and with Cyrillic.

- **Payment and Subscription Test Case (E2E)**
- The entire payment process is tested using End-to-End testing.

- Covers: plan selection, payment methods, subscription lifecycle, and access to premium features (unlimited text generation per day).

- **UI and Font Size Test Case**
- Verify functionality of changing font size.

- Tests: apply new font size to all UI elements, save settings after restart.

- **Push Notification Test Case**
- Verify push notification delivery on mobile devices.

- Includes: background, lock screen, notification text, and deep linking.

---

## Key Findings (Bugs)

- **BUG-001**: Registration system allows Cyrillic characters in the local part of the email (`rПegress_test_+20260706@example.com`), violating validation rules and potentially causing email delivery issues.
- **BUG-002**: Font size change in settings does not apply to the UI text, affecting readability for parents.

---

# QA Портфоліо: Fairytale Time – Генератор казок на основі ШІ

> *Це портфоліо демонструє мої навички тестування на мобільному додатку Fairytale Time (v1.2.2). Воно містить тест-кейси та баг-репорти для функції генерації казок за допомогою штучного інтелекту.*

---

## Структура репозиторію

- **Тест-кейси** – Детальні тест-кейси для реєстрації, валідації email, UI, оплати та push-сповіщень.
- **Баг-репорти** – Звіти про дефекти із зазначенням серйозності, кроків для відтворення та впливу на бізнес.

---

## Використані техніки тест-дизайну

- **Класи еквівалентності (EP)** – Валідація формату email (валідні/невалідні email).
- **Тестування станів та переходів (State Transition)** – Життєвий цикл підписки (Безкоштовний → Тріал → Платний → Скасований).

---

## Результати тестування (Test Summary)

| Показник | Значення |
| :--- | :--- |
| **Всього тест-кейсів** | 8 |
| **Пройдено** | 6 |
| **Не пройдено** | 2 |
| **Баг-репортів** | 2 |

**Тест-кейси, що не пройшли:**
- Валідація email з кирилицею (`rПegress_test_+20260706@example.com`) – система неправильно пропускає невалідний формат.
- Зміна розміру шрифту в налаштуваннях – UI не застосовує новий розмір.

**Баг-репорти:**
- **BUG-001**: Реєстрація дозволяє кирилицю в локальній частині email.
- **BUG-002**: Зміна шрифту не впливає на текст в інтерфейсі.

---

## Огляд артефактів

- **Набір тестів реєстрації та перевірки електронної пошти**
- Перевірка формату електронної пошти (позитивні та негативні сценарії).

- Охоплює: дійсні адреси електронної пошти, адреси електронної пошти без `@`, без крапки, з пробілами та з кирилицею.

- **Тест оплати та підписки (E2E)**
- Весь процес оплати тестується за допомогою наскрізного тестування.

- Охоплює: вибір плану, способи оплати, життєвий цикл підписки та доступ до преміум-функцій (необмежена генерація тексту на день).

- **Тест інтерфейсу користувача та розміру шрифту**
- Перевірка функціональності зміни розміру шрифту.

- Тести: застосування нового розміру шрифту до всіх елементів інтерфейсу користувача, збереження налаштувань після перезапуску.

- **Тест push-сповіщень**
- Перевірка доставки push-сповіщень на мобільних пристроях.

- Включає: фон, екран блокування, текст сповіщень та прямі посилання.

---

## Основні знахідки (Баг-репорти)

- **BUG-001**: Система реєстрації дозволяє введення кириличних символів у локальній частині email (`rПegress_test_+20260706@example.com`), що порушує правила валідації та може призвести до проблем із доставкою казок на пошту.
- **BUG-002**: Зміна розміру шрифту в налаштуваннях не застосовується до тексту інтерфейсу, що погіршує зручність читання казок для батьків.

---

## 📞 Контакти

**Дмитро**  
Email: dmitrtester@gmail.com   
LinkedIn: www.linkedin.com/in/дмитро-поліщук-056a75409
---