<!--
CO_OP_TRANSLATOR_METADATA:
{
  "original_hash": "787440926586cd064b0899fd1c514f52",
  "translation_date": "2025-06-17T16:30:00+00:00",
  "source_file": "10-StreamliningAIWorkflowsBuildingAnMCPServerWithAIToolkit/README.md",
  "language_code": "uk"
}
-->
# Оптимізація AI-процесів: Створення MCP-сервера з AI Toolkit

[![MCP Version](https://img.shields.io/badge/MCP-1.9.3-blue.svg)](https://modelcontextprotocol.io/)
[![Python](https://img.shields.io/badge/Python-3.10+-green.svg)](https://python.org)
[![VS Code](https://img.shields.io/badge/VS%20Code-Latest-orange.svg)](https://code.visualstudio.com/)

![logo](../../../translated_images/logo.ec93918ec338dadde1715c8aaf118079e0ed0502e9efdfcc84d6a0f4a9a70ae8.uk.png)

## 🎯 Огляд

Ласкаво просимо на **Workshop з Model Context Protocol (MCP)**! Цей комплексний практичний курс поєднує дві передові технології, які змінюють підхід до розробки AI-додатків:

- **🔗 Model Context Protocol (MCP)**: Відкритий стандарт для безшовної інтеграції AI-інструментів
- **🛠️ AI Toolkit для Visual Studio Code (AITK)**: Потужне розширення для розробки AI від Microsoft

### 🎓 Чого ви навчитеся

До кінця цього воркшопу ви опануєте створення інтелектуальних додатків, які поєднують AI-моделі з реальними інструментами та сервісами. Від автоматизованого тестування до індивідуальних API-інтеграцій — ви отримаєте практичні навички для розв’язання складних бізнес-завдань.

## 🏗️ Технологічний стек

### 🔌 Model Context Protocol (MCP)

MCP — це **«USB-C для AI»** — універсальний стандарт, який з’єднує AI-моделі з зовнішніми інструментами та джерелами даних.

**✨ Основні можливості:**
- 🔄 **Стандартизована інтеграція**: Універсальний інтерфейс для підключення AI-інструментів
- 🏛️ **Гнучка архітектура**: Локальні та віддалені сервери через stdio/SSE транспорт
- 🧰 **Багатий екосистемний набір**: Інструменти, підказки та ресурси в одному протоколі
- 🔒 **Готовність для підприємств**: Вбудована безпека та надійність

**🎯 Чому MCP важливий:**
Як USB-C поклав край хаосу з кабелями, так і MCP усуває складність інтеграції AI. Один протокол — безмежні можливості.

### 🤖 AI Toolkit для Visual Studio Code (AITK)

Флагманське AI-розширення Microsoft, яке перетворює VS Code на потужний AI-інструмент.

**🚀 Ключові функції:**
- 📦 **Каталог моделей**: Доступ до моделей Azure AI, GitHub, Hugging Face, Ollama
- ⚡ **Локальне інференсування**: Оптимізоване виконання на CPU/GPU/NPU через ONNX
- 🏗️ **Agent Builder**: Візуальна розробка AI-агентів з інтеграцією MCP
- 🎭 **Мультимодальність**: Підтримка тексту, зображень та структурованих відповідей

**💡 Переваги розробки:**
- Розгортання моделей без конфігурації
- Візуальна розробка підказок
- Платформа для тестування в реальному часі
- Безшовна інтеграція MCP-серверів

## 📚 Навчальний план

### [🚀 Модуль 1: Основи AI Toolkit](./lab1/README.md)
**Тривалість**: 15 хвилин
- 🛠️ Встановлення та налаштування AI Toolkit для VS Code
- 🗂️ Ознайомлення з Каталогом моделей (понад 100 моделей з GitHub, ONNX, OpenAI, Anthropic, Google)
- 🎮 Освоєння інтерактивного майданчика для тестування моделей у реальному часі
- 🤖 Створення першого AI-агента за допомогою Agent Builder
- 📊 Оцінка продуктивності моделей за допомогою вбудованих метрик (F1, релевантність, схожість, узгодженість)
- ⚡ Вивчення пакетної обробки та підтримки мультимодальності

**🎯 Результат навчання**: Створити функціонального AI-агента з повним розумінням можливостей AITK

### [🌐 Модуль 2: Основи MCP з AI Toolkit](./lab2/README.md)
**Тривалість**: 20 хвилин
- 🧠 Вивчення архітектури та концепцій Model Context Protocol (MCP)
- 🌐 Ознайомлення з екосистемою MCP-серверів Microsoft
- 🤖 Створення агента для автоматизації браузера з використанням Playwright MCP server
- 🔧 Інтеграція MCP-серверів з AI Toolkit Agent Builder
- 📊 Налаштування та тестування MCP-інструментів у ваших агентах
- 🚀 Експорт і розгортання агентів з підтримкою MCP для виробничого використання

**🎯 Результат навчання**: Розгорнути AI-агента, посиленого зовнішніми інструментами через MCP

### [🔧 Модуль 3: Поглиблена розробка MCP з AI Toolkit](./lab3/README.md)
**Тривалість**: 20 хвилин
- 💻 Створення кастомних MCP-серверів за допомогою AI Toolkit
- 🐍 Налаштування та використання останнього MCP Python SDK (v1.9.3)
- 🔍 Встановлення та використання MCP Inspector для налагодження
- 🛠️ Розробка Weather MCP Server з професійними робочими процесами налагодження
- 🧪 Налагодження MCP-серверів у середовищах Agent Builder та Inspector

**🎯 Результат навчання**: Розробляти та налагоджувати власні MCP-сервери з сучасними інструментами

### [🐙 Модуль 4: Практична розробка MCP — кастомний GitHub Clone Server](./lab4/README.md)
**Тривалість**: 30 хвилин
- 🏗️ Створення реального GitHub Clone MCP Server для робочих процесів розробки
- 🔄 Реалізація інтелектуального клонування репозиторіїв з валідацією та обробкою помилок
- 📁 Розробка розумного керування директоріями та інтеграція з VS Code
- 🤖 Використання GitHub Copilot Agent Mode з кастомними MCP-інструментами
- 🛡️ Застосування надійності для виробничого використання та кросплатформної сумісності

**🎯 Результат навчання**: Розгорнути виробничий MCP-сервер, що оптимізує реальні робочі процеси розробки


## 💡 Практичне застосування та вплив

### 🏢 Використання в підприємствах

#### 🔄 Автоматизація DevOps
Перетворіть ваші робочі процеси розробки за допомогою інтелектуальної автоматизації:
- **Інтелектуальне управління репозиторіями**: AI-керований код-рев’ю та прийняття рішень про злиття
- **Розумний CI/CD**: Автоматична оптимізація пайплайнів на основі змін у коді
- **Тріаж проблем**: Автоматична класифікація та призначення багів

#### 🧪 Революція в забезпеченні якості
Покращте тестування завдяки AI-автоматизації:
- **Інтелектуальне генерування тестів**: Автоматичне створення комплексних тестових наборів
- **Візуальне регресійне тестування**: AI-виявлення змін у UI
- **Моніторинг продуктивності**: Проактивне виявлення та усунення проблем

#### 📊 Інтелектуальні дані в пайплайнах
Створюйте розумніші процеси обробки даних:
- **Адаптивні ETL-процеси**: Самооптимізуючі трансформації даних
- **Виявлення аномалій**: Моніторинг якості даних у реальному часі
- **Інтелектуальна маршрутизація**: Розумне керування потоками даних

#### 🎧 Покращення взаємодії з клієнтами
Створюйте винятковий досвід для клієнтів:
- **Підтримка з урахуванням контексту**: AI-агенти з доступом до історії клієнтів
- **Проактивне вирішення проблем**: Прогнозована підтримка клієнтів
- **Інтеграція багатьох каналів**: Єдиний AI-досвід на різних платформах


## 🛠️ Вимоги та налаштування

### 💻 Системні вимоги

| Компонент           | Вимога               | Примітки              |
|---------------------|----------------------|-----------------------|
| **Операційна система** | Windows 10+, macOS 10.15+, Linux | Будь-яка сучасна ОС    |
| **Visual Studio Code** | Остання стабільна версія | Необхідно для AITK    |
| **Node.js**           | v18.0+ та npm         | Для розробки MCP-серверів |
| **Python**            | 3.10+                 | Опційно для Python MCP-серверів |
| **Пам’ять**           | Мінімум 8 ГБ RAM      | Рекомендовано 16 ГБ для локальних моделей |

### 🔧 Розробницьке середовище

#### Рекомендовані розширення для VS Code
- **AI Toolkit** (ms-windows-ai-studio.windows-ai-studio)
- **Python** (ms-python.python)
- **Python Debugger** (ms-python.debugpy)
- **GitHub Copilot** (GitHub.copilot) — опційно, але корисно

#### Опційні інструменти
- **uv**: Сучасний менеджер пакетів Python
- **MCP Inspector**: Візуальний інструмент налагодження MCP-серверів
- **Playwright**: Для прикладів веб-автоматизації


## 🎖️ Результати навчання та сертифікація

### 🏆 Контрольний список навичок

Завершивши цей курс, ви досягнете майстерності у:

#### 🎯 Основні компетенції
- [ ] **Володіння MCP протоколом**: Глибоке розуміння архітектури та шаблонів реалізації
- [ ] **Професіоналізм у AITK**: Експертне використання AI Toolkit для швидкої розробки
- [ ] **Розробка кастомних серверів**: Створення, розгортання та підтримка виробничих MCP-серверів
- [ ] **Відмінна інтеграція інструментів**: Безшовне поєднання AI з існуючими робочими процесами розробки
- [ ] **Застосування навичок розв’язання проблем**: Використання отриманих знань для вирішення реальних бізнес-завдань

#### 🔧 Технічні навички
- [ ] Встановлення та налаштування AI Toolkit у VS Code
- [ ] Проектування та імплементація кастомних MCP-серверів
- [ ] Інтеграція GitHub моделей з архітектурою MCP
- [ ] Побудова автоматизованих тестових процесів з Playwright
- [ ] Розгортання AI-агентів для виробничого використання
- [ ] Налагодження та оптимізація продуктивності MCP-серверів

#### 🚀 Розширені можливості
- [ ] Архітектура AI-інтеграцій підприємницького рівня
- [ ] Впровадження найкращих практик безпеки для AI-додатків
- [ ] Проектування масштабованих архітектур MCP-серверів
- [ ] Створення кастомних ланцюгів інструментів для специфічних доменів
- [ ] Наставництво у розробці AI-native рішень

## 📖 Додаткові ресурси
- [MCP Specification](https://modelcontextprotocol.io/docs)
- [AI Toolkit GitHub Repository](https://github.com/microsoft/vscode-ai-toolkit)
- [Sample MCP Servers Collection](https://github.com/modelcontextprotocol/servers)
- [Best Practices Guide](https://modelcontextprotocol.io/docs/best-practices)

---

**🚀 Готові змінити свій AI-розробницький процес?** 

Давайте разом створювати майбутнє інтелектуальних додатків з MCP та AI Toolkit!

**Відмова від відповідальності**:  
Цей документ було перекладено за допомогою сервісу автоматичного перекладу [Co-op Translator](https://github.com/Azure/co-op-translator). Хоча ми прагнемо до точності, будь ласка, майте на увазі, що автоматичні переклади можуть містити помилки або неточності. Оригінальний документ рідною мовою слід вважати авторитетним джерелом. Для критично важливої інформації рекомендується звертатися до професійного людського перекладу. Ми не несемо відповідальності за будь-які непорозуміння або неправильні тлумачення, що виникли внаслідок використання цього перекладу.