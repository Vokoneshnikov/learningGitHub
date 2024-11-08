# Конспект по первому занятию


## Проведение занятий

- Домашние работы (в сумме 20 баллов)
- Летучки, устные ответы (в сумме 10 баллов)
- Контрольные работы (в сумме за две работы 20 баллов)
- За прогулы баллы не снижаются
- Проверки ДЗ будут через git
- На занятии обращение по имени, вне занятий по ИО

## Правила приема домашних работ

-  У каждой работы есть свой дедлайн (минимум - 2 недели)
- Если работа выполнена в срок - можно успеть исправить ошибки согласно ОС (даётся по завершении дедлайна) и получить за неё полный балл
- Если работа выполнена в резервный срок после дедлайна (равен дедлайну) - исправить ошибки согласно ОС не удастся
- Если работа не выполнена ни в дедлайн, не в резервный срок, но сдана не позднее трёх недель до конца семестра - все баллы автоматически уменьшаются в 2 раза
- Если работа сдана позже трёх недель до конца семестра - работа не проверяется

## Важные моменты

- Если проект не запускается - 0 баллов
- Если в работах не компилируется код - 0 баллов
- Копипаст работ работ - 0 баллов всем, у кого одинаковый код

## План на первый семестр

- Что такое C#, из чего он состоит?
- Что такое высокоуровневый язык?
- Как писать простые процедурные программы?
- Кака пользоваться git?
- Как писать код по ТЗ?
- Какие критические важные термины в IT-сфере?
- Что такое ООП?


## Кому пригодится программирование?

- Разработчикам
- Архитекторам
	- умение оперировать технологиями программирования
	- знание архитектурных паттернов проектирования
- SRE = инженерам по доступности
	- знание скриптов для CI/CD (непрерывная разработка и развёртывание продукта)
- Аналитикам
	- UML = язык графического описания для объектного моделирования, построение бизнес процессов
	- общие технические навыки
		- SQL (БД)
		- BPMN (система условных обозначений в XML для моделирования бизнес процессов)
- HR
	- знание стеков и технологий
- Тестировщик
	- умение программировать скрипты для автоматизации тестирования
	- техническое мышление
	- умение использовать и локально отлаживать тестируемые компоненты

## Что такое техническое мышление?

- Алгоритмы
- Структурирование
- Декомпозиция
- Выделение главного
- Не думать "в лоб"
- Уметь упрощать задачу (абстракция - один из принципов ООП)

## Уровень языков

**![](https://lh7-rt.googleusercontent.com/slidesz/AGV_vUcOlK95kiqJwjQwW7peUH9h2Gva36piXiRRgDjbGoNlF2ugPJnw8xBeSHFXsQ-yzCBPN3msE3P_B7NlDDhcflI7MYI_GqcnyGDNWQqmArFRflxCbXV5N6N5hox1BTW_rOi2mvTYCnlq0ju6hOoitZpMlRhFftZS=s2048?key=ioesny1-am-zBCTxlH-YhQ)

## Типы языков программирования

**![](https://lh7-rt.googleusercontent.com/slidesz/AGV_vUcDzPSMIiX3qYXcPzu79kmt52zzhzNEsOj-NKRbI8bncl-V8JcPmB1egCChLcs9xLS6F1O0oXpwxEsCyNOsljjnl5IaWMt5bI0QG-i0OS4JXncKVM-jI5Ou6_bz-6xT2VXR_VGgyKX-9KfZclteroK26z5aygxt=s2048?key=ioesny1-am-zBCTxlH-YhQ)


## Абстракция

![[Pasted image 20241103111810.png]]

## .Net, C#

1. ![[Pasted image 20241103111839.png]]
2. Понятия:
	1. Компилятор -  программа, переводящая написанный на языке программирования текст в CIL код
	2. CIL - «высокоуровневый ассемблер» виртуальной машины .NET
	3. CLR -  исполняющая среда для байт-кода CIL, в который компилируются программы, написанные на .NET-совместимых языках программирования
	4. IL код - текстовый низкоуровневый код
3. Книги для развития:
	1. Эндрю Троелсен “Язык программирования C# и платформы .NET и .NET Core”
	2. Герберт Шилдт “C# Полное руководство”

## Мультиязычность != Кроссплатформенность

## Что будет нужно на первых трёх практиках:

1. .Net Core 3.1 и .Net 8-9 последний (3.1 нужен вам до объяснения темы по ООП)
2. Текстовый редактор с подсветкой синтаксиса (!не IDE)
3. git
4. Регистрация на github.com
5. .Net SDK

## Хардкорный "Hello world!"

1. Создать решение
	1. **Решение (solution)** – это большой контейнер для ваших проектов, в C# является файлом с расширением “.sln”
2. Создать проект
	1. **Проект** – одна программная единица, которая может работать (или быть использована другими проектами) автономно или вместе с другими проектами
3. Собрать проект в сборку
	1. **Сборка (assembly)** – это готовый к “употреблению” проект. Сам по себе проект не работает, его нужно “собрать”
4. Запустить сборку

## Домашнее задание

1. Написать конспект по данному занятию (не более 1 страницы А4) и залить его в ваш репозиторий. Также нужно, чтобы у вас в ветке task1 было ваше решение (sln) с прикрепленным к нему проектом (проект базовый на .net core 3.1)
2. Делитесь по парам (если у кого то не останется пары - я буду вторым). Вы должны предоставить доступ к репозиториям друг друга. Ваш новый участник должен создать ветку mk и внести изменение в ваш конспект. В тоже время, создатель репозитория должен внести свои правки в это же место и вылить эти изменения в main. Далее второй участник создает MR и должен столкнуться с конфликтом. Ваша задача его разрулить и в конечном счете его слить в ветку main. Потом лаем то же самое у второго симметрично. Кто сливает - тот и решает конфликт