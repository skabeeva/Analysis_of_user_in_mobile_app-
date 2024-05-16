# Аналитика поведения пользователей стартапа по продаже продуктов питания с использованием мобильного приложения
**Описание проекта:**
В данном проекте мы рассматривали стартап, который продаёт продукты питания. Нужно было разобраться, как ведут себя пользователи мобильного приложения. 
 Для работы нам доступен один датасет, который содержит следующие данные:
 - `EventName` — название события;
 - `DeviceIDHash` — уникальный идентификатор пользователя;
 - `EventTimestamp` — время события;
 - `ExpId` — номер эксперимента: 246 (A) и 247 (A) — контрольные группы, а 248 (B) — экспериментальная.
 
 Для анализа и принятие решения по результатам теста будет необходимо:

 1) Изучить воронку продаж
 
 2) Выяснить, какой шрифт лучше, используя результаты A/A/B-эксперемента

**Выводы:** В целом существует проблема на главном экране мобильного приложения, т.к. по неизвестной нам причине, очень малая доля пользователей доходит до экрана с предложением покупок. Возможно существует какая-то техническая или дизайнерская проблема с переходом на экран, но измененный шрифт на данное положение дел, к сожалению, не влияет.
