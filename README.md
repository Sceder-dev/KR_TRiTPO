# "Easy Generator" - упрости создание аккаунтов!

# **Требования к проекту**

# Содержание
1 [Введение](#intro)  
1.1 [Назначение](#appointment)  
1.2 [Бизнес-требования](#business_requirements)  
1.2.1 [Исходные данные](#business_opportunities)  
2 [Требования пользователя](#user_requirements)  
2.1 [Программные интерфейсы](#software_interfaces)  
2.2 [Интерфейс пользователя](#user_interface)  
2.3 [Характеристики пользователей](#user_specifications)  
2.4 [Предположения и зависимости](#assumptions_and_dependencies)  
3 [Системные требования](#system_requirements)  
3.1 [Функциональные требования](#functional_requirements)  
3.2 [Нефункциональные требования](#non-functional_requirements)  
3.2.1 [Атрибуты качества](#quality_attributes)  
3.2.2 [Требования к безопасности](#security_requirements)  

<a name="intro"/>

# 1 Введение

<a name="appointment"/>

## 1.1 Назначение

Приложение "Easy Generator" упростит создание новых аккаунтов. 

<a name="business_requirements"/>

## 1.2 Бизнес-требования

<a name="business_opportunities"/>

### 1.2.1 Исходные данные

Каждый из нас когда либо создавал аккаунт где либо, но запоминать кучу логинов и паролей утомительно, а при использовании одного логина и пароля везде, очень сильно страдает безопасность. Приложение Easy Generator облегчит все это.

<a name="user_requirements"/>

# 2 Требования пользователя

<a name="software_interfaces"/>

## 2.1 Программные интерфейсы

Предоставление пользователю как и простой вариант создания логина и пароля, так и расширенные настройки для тех, кто по-настоящему обеспокоен безопасностью

<a name="user_interface"/>

## 2.2 Интерфейс пользователя

**Главное окно программы включает в себя такие элементы как:**

*Generate* - Кнопка генерирующая логин и пароль;

*Login* - Поле с логином;

*Password* - Поле с паролем;

*Settings button* - Кнопка расширенных настроек;

**Окно настроек программы состоит из:** 

*Change maxlenght* - Список для выбора максимальной длины логина и пароля;

*Insert your private key* - поле для ввода ключа генерации; 

*Crypto encrypt by date* - флаг выбора генерации по дате;

**Графический интерфейс приложения "Easy Generator" выглядит следующим образом:**

**Главное окно программы**

![Главное окно программы](/Images/Easy_Main.png)  

**Окно настроек**

![Окно настроек](/Images/Easy_Settings.png)  
 

<a name="user_specifications"/>

## 2.3 Характеристики пользователей

**2.3.1. Целевая аудитория приложения**

Любой человек имеющий какой-либо аккаунт

<a name="assumptions_and_dependencies"/>

## 2.4 Предположения и зависимости

Приложение будет некорректно работать на тех устройствах, версия ПО которого ниже, чем минимальная поддерживаемая версия, для которой осуществлялась разработка данного приложения.

<a name="system_requirements"/>

# 3 Системные требования

<a name="functional_requirements"/>

## 3.1 Функциональные требования

**3.1.1. Основные функции**

*Создание логина и пароля* - Создание логина и пароля для аккаунта;

*Выбор настроек генерации* - Происходит выбор настройки генерации логина и пароля для большей безопасности использования;

**3.1.2. Ограничения и исключения**

Приложение не имеет специфических ограничений

<a name="non-functional_requirements"/>

## 3.2 Нефункциональные требования

<a name="quality_attributes"/>

### 3.2.1 Атрибуты качества

Производительность - Приложение обязано успешно отрабатывать 100% операций пользователя

Безопасность - Сгенерированая пара логин/пароля должна быть криптоустойчивой

Простота - Интуитивно понятный интерфейс


<a name="security_requirements"/>

### 3.2.2 Требования к безопасности

Окна приложения должны быть удобны для использования пользователями с плохим зрением, для этого был установлен размер шрифта от 12 пт и выше, а также основные функциональные элементы являются контрастными по отношению к фону окна приложения.
