1)
-- Bug #1096 (Redmine #19751) Text Chat. Full-duplex. Кнопка вызова не меняет свое состояние после начала вызова 
-- Bug #1097 (Redmine #19752) Text Chat. Full-duplex. Pадио остается в сессии, после завершении вызова на радио группу/радио абонента 
-- Bug #1100 (Redmine #19749) Text Chat. Full-duplex. Некорректно совершаем вызов из чата, после вызова абонента из контекстного меню дерева абонентов 
-- Bug #1101 (Redmine #19750) Text Chat. Full-duplex. После перехода на другой чат не можем завершить текущий вызов
2)
-- Bug #1102 (Redmine #19759) Text Chat. PTT/Full-duplex Call. Задизейблена возможность совершать вызовы для абонента(группы) вновь зарегистрированого(добавленой) после удаления 
-- Bug #1102 (Redmine #19764) Notification. Text Chat. Не возобновляем удержаный вызов, хотя кнопка кликабельна 
-- Bug #1102 (Redmine #19772) Voice Dispatch. Интерком бокс остается в сессии после отжатия PTT кнопки
-- #19748 Private PTT Grid. Слетает селект по завершении Full-duplex вызова
-- Сделать пример RX in One
-- Добавить правила оформления UML диаграмм
-- Перенести вcе Workflow в One из Enterprise 
3)
4)


ЧТО ХОЧЕТСЯ СДЕЛАТЬ
-- PttStateManager добавить Moq и тесты на краевые случаи
-- SipLines - сделать синглетоном
-- InitTransmitInfoSender - попробовать написать+тесты
-- Перенести таймер из CallStateResolver в InitTransmitInfoSender
-- сделать binding to enum в PttButtonWidget (SelectPttButtonViewType)
-- Сделать state machine в боксе 
-- Добавить тестов на state machine 


Пример по RX
-- Сделать пример с кнопкой PTT которая будет блокироваться на некоторое время, в этом время будет прогресс бар
-- Пример по IOC
Microsoft.Extensions.DependencyInjection




