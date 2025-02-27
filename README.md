# ИИ-ассистент для университета Зерокодер

## О проекте

Этот учебный проект был разработан во время прохождения интенсива по промпт-инжинирингу от [Zerocoder](https://zerocoder.ru).
Проект представляет собой интеллектуального ассистента, предназначенного для помощи пользователям, желающим обучиться ноукодингу (созданию программных решений без написания кода) в университете **Зерокодер**. Он помогает познакомить пользователей с университетом, доступными курсами и предоставляет возможность записи на пробный урок через Telegram-бота [@newzerocoder_bot](https://t.me/newzerocoder_bot).

*Примечание: Т.к. проект учебный - в дальнейшем бот может не поддерживаться, информацию по работе бота можно увидеть на скриншотах.*

---

## Функционал

Основной функционал ассистента включает:

1. **Представление университета и курсов**  
   Ассистент знакомит пользователей с онлайн-университетом, предоставляя информацию о программах и преимуществах обучения. Это позволяет потенциальным студентам получить представление о возможностях университета.

2. **Консультирование по курсам**  
   Пользователи могут задать вопросы об интересующих их курсах, ассистент использует базу знаний для предоставления точных и актуальных ответов.

3. **Запись на пробный урок**  
   Одна из ключевых функций — это возможность записаться на пробный урок. Через диалог с ассистентом пользователь может выбрать удобное время, указать свои предпочтения, после чего система автоматически зарегистрирует его на пробный урок.

4. **Синхронизация с Google Календарем**  
   При записи на пробный урок система использует интеграцию с Google Calendar API для создания событий в календарях обеих сторон. Это гарантирует, что все участники получают своевременные уведомления о предстоящей встрече и могут планировать свое время соответственно.

Для реализации этой функции используется авторизация через Google аккаунты преподавателей и студентов, что обеспечивает безопасность и конфиденциальность данных. 

Такая система работает по принципу двусторонней синхронизации: когда клиент выбирает удобное для него время, это время автоматически проверяется на доступность у преподавателя, после чего фиксируется в календарях обеих сторон.

---

## Скриншоты работы чат-бота

1. https://github.com/yural64/AI_assistent_intensiv/blob/main/чат1.png
2. https://github.com/yural64/AI_assistent_intensiv/blob/main/чат2.png
3. https://github.com/yural64/AI_assistent_intensiv/blob/main/чат3.png
4. https://github.com/yural64/AI_assistent_intensiv/blob/main/чат4.png
   
---

## Технологии и сервисы

Для реализации проекта были использованы следующие технологии и сервисы:

- **Qwen**  
  Нейросетевой языковой моделью Qwen был создан системный промпт и подготовлена база знаний. Это обеспечивает высокую точность и релевантность ответов ассистента.

- **Savvy (https://suvvy.ai/)**  
  Платформа Savvy была выбрана для создания и настройки ИИ-ассистента. Она обеспечивает удобный интерфейс для интеграции различных функций, таких как управление диалогами, обработка запросов и автоматизация задач.

- **Telegram API**  
  Взаимодействие с пользователями осуществляется через Telegram-бота [@newzerocoder_bot](https://t.me/newzerocoder_bot), что делает процесс максимально простым и доступным для широкой аудитории.

---

## Преимущества решения

- **Легкость использования**  
  Взаимодействие через Telegram делает использование ассистента максимально простым и доступным для всех категорий пользователей.

- **Экономия времени**  
  Автоматизация процессов взаимодействия с клиентами позволяет сотрудникам университета сосредоточиться на более важных задачах.

- **Широкие возможности масштабирования**  
  Решение может быть легко адаптировано для других направлений деятельности университета или даже для других организаций.

---

## Возможности развития

В будущем проект может быть дополнен следующими функциями:

- Добавление голосового взаимодействия для большего удобства пользователей.
- Интеграция с CRM-системой университета для более тесного взаимодействия с базой данных клиентов.
- Добавление многоканальной коммуникации (например, через WhatsApp или электронную почту).

---
