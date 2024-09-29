# Домашнее задание к занятию «1.1. Dependency Injection»

## Задача №1. Dagger Hilt
#### Описание
Проведите миграцию вашего проекта на Dagger Hilt. Функционал и автотесты должны работать без изменений.

## Задача №2. Singletons
#### Описание
В приложении с лекции в MainActivity используются следующие конструкции:

FirebaseMessaging.getInstance().token.addOnCompleteListener { task ->
    ...
}

with(GoogleApiAvailability.getInstance()) {
    ...
}
Замените вызовы getInstance на DI. Для этого напишите собственные модули.
