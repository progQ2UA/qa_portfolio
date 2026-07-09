# 🧪 QA Portfolio: EatBook Testing

> *This portfolio demonstrates my testing skills on the EatBook Android app (v1.1.5). It includes test suites, test cases, bug reports, and a checklist.*
> *Для українськомовних читачів — скорочена версія нижче / Ukrainian version below.*

---

## 📂 Repository Structure

- **Test Suites** — Test suites with different design techniques (BVA, EP, State Transition, Decision Table)
- **Test Cases** — Detailed test cases
- **Bug Reports** — Bug reports with Severity, Steps, and Business Impact
- **Checklists** — Checklist for quick sanity testing

---

## 🧪 Test Design Techniques Used

- **Boundary Value Analysis (BVA)** — Height field validation
- **Equivalence Partitioning (EP)** — Subscription periods
- **State Transition Testing** — Subscription lifecycle (inactive → trial → paid → canceled)
- **Decision Table** — Payment scenarios (new/existing user + trial period)

---

## 📋 Artifacts Overview

### 1. Test Suites

**BVA Test Suite**  
Validation of numeric fields (Height: 31–279).  
Checks boundary values: 30, 31, 279, 280.

**Payment & Subscription Test Suite**  
Full payment flow with State Transition and Decision Table.  
Covers: plan selection, payment methods, subscription lifecycle, and cancelation.

---

### 2. Test Cases

**TC001_APP1_Registration** — Registration Module  
Checks registration with valid and invalid data using EP and BVA techniques.  
Status: ✅ PASSED

**TC002_APP1_Localization** — Localization Module  
Checks UI translation and internal system messages.  
Status: ❌ FAILED

---

### 3. Bug Reports

**BUG001_APP1_Settings** — Profile Settings  
The app accepts invalid email format (without `@` and `.`).  
Severity: **Major** | Status: Open

**BUG002_APP1_Localization** — Localization  
Internal messages are displayed in English, even when the app language is Ukrainian.
Severity: **Minor** | Status: Open

---

### 4. Checklist

**Smoke Checklist**  
19 checks across 3 modules: Registration, Localization, and Subscriptions.  
Result: 17 PASSED, 2 FAILED → 2 bug reports created.

---

## 📊 Summary Results

- **Registration:** 6 checks → 5 PASSED, 1 FAILED → 1 bug report
- **Localization:** 6 checks → 5 PASSED, 1 FAILED → 1 bug report
- **Subscriptions:** 7 checks → 7 PASSED, 0 FAILED → 0 bug reports
- **Total:** 19 checks → 17 PASSED, 2 FAILED → 2 bug reports

---

## 🛠️ Tools Used

- **Jira** — Bug tracking & test management
- **Software Ideas Modeler** — State Transition Diagram
- **Microsoft Word** — Test case & bug report documentation

---

## 📬 Contact

**Dmytro**  
Email: dmitrtester@gmail.com  
LinkedIn: [Your LinkedIn]  

---

---

# 🇺🇦 Українська версія (скорочено)

## 🧪 Портфоліо QA: Тестування EatBook

> *Це портфоліо демонструє мої навички тестування на Android-додатку EatBook (v1.1.5). Воно містить тест-сьюти, тест-кейси, баг-репорти та чекліст.*

---

## 📂 Структура репозиторію

- **Test Suites** — Тест-сьюти з різними техніками тест-дизайну (BVA, EP, State Transition, Decision Table)
- **Test Cases** — Детальні тест-кейси
- **Bug Reports** — Баг-репорти з Severity, кроками та бізнес-впливом
- **Checklists** — Чекліст для швидкої перевірки

---

## 🧪 Використані техніки тест-дизайну

- **Аналіз граничних значень (BVA)** — Валідація поля Height
- **Еквівалентне розбиття (EP)** — Періоди підписки
- **Тестування станів та переходів** — Життєвий цикл підписки (неактивна → пробна → платна → скасована)
- **Таблиця рішень** — Сценарії оплати (новий/існуючий користувач + пробний період)

---

## 📋 Огляд артефактів

### 1. Тест-сьюти

**BVA Test Suite**  
Валідація числових полів (Height: 31–279).  
Перевірено граничні значення: 30, 31, 279, 280.

**Payment & Subscription Test Suite**  
Повний процес оплати з State Transition та Decision Table.  
Охоплює: вибір плану, методи оплати, життєвий цикл підписки та скасування.

---

### 2. Тест-кейси

**TC001_APP1_Registration** — Модуль реєстрації  
Перевірка реєстрації з валідними та невалідними даними з використанням технік EP та BVA.  
Статус: ✅ PASSED

**TC002_APP1_Localization** — Модуль локалізації  
Перевірка перекладу UI та внутрішніх повідомлень.  
Статус: ✅ PASSED

---

### 3. Баг-репорти

**BUG001_APP1_Settings** — Налаштування профілю  
Додаток приймає невалідний Email (без `@`).  
Severity: **Major** | Статус: Open

**BUG002_APP1_Localization** — Локалізація  
Внутрішні повідомлення відображаються англійською мовою, навіть якщо мовою застосунку вибрано українську.
Severity: **Minor** | Статус: Open

---

### 4. Чекліст

**Smoke-чекліст**  
19 перевірок у 3 модулях: Реєстрація, Локалізація, Підписки.  
Результат: 17 PASSED, 2 FAILED → створено 2 баг-репорти.

---

## 📊 Підсумкові результати

- **Реєстрація:** 6 перевірок → 5 PASSED, 1 FAILED → 1 баг-репорт
- **Локалізація:** 6 перевірок → 5 PASSED, 1 FAILED → 1 баг-репорт
- **Підписки:** 7 перевірок → 7 PASSED, 0 FAILED → 0 баг-репортів
- **Всього:** 19 перевірок → 17 PASSED, 2 FAILED → 2 баг-репорти

---

## 🛠️ Використані інструменти

- **Jira** — Відстеження багів та управління тестами
- **Software Ideas Modeler** — Діаграма станів (State Transition Diagram)
- **Microsoft Word** — Документування тест-кейсів та баг-репортів

---

## 📬 Контакти

**Дмитро**  
Email: dmitrtester@gmail.com   
LinkedIn: www.linkedin.com/in/дмитро-поліщук-056a75409