1)
-- Bug #987 Bug #18851. Text Chat. PTT. Из чата перестает отрабатывать кнопка PTT, если перейти на другой чат. (залил)
-- Task #1055 Выделить из CallBox PhoneCallBox
в процессе, немного раскидал по файлам и папкам UI которые относятся к Phone это залил (NS.Enterprise.WidgetFactory\UI\Widgets\VoiceDispatch\CallBoxViews\). Сейчас выделяю все свойства и поля в отдельный класс PhoneCallBox 
2)
-- Issue #1052 Рефакторинг сущности CallBox
-- Bug #1055 Выделить из CallBox PatchCallBox
-- Ioc/RX к 19 февраля
-- унификация двух консолей в перспективе
3)
4)


ТЕКУЩАЯ ЗАДАЧА
Отделить Phone от CallBox
вытащить custombutton из callbox в PhoneBox

ЧТО ХОЧЕТСЯ СДЕЛАТЬ

-- InitTransmitInfoSender - попробовать написать+тесты
-- Перенести таймер из CallStateResolver в InitTransmitInfoSender
-- сделать binding to enum в PttButtonWidget (SelectPttButtonViewType)
-- Сделать state machine в боксе 
-- Добавить тестов на state machine 


Пример по RX
-- Сделать пример с кнопкой PTT которая будет блокироваться на некоторое время, в этом время будет прогресс бар
-- Пример по IOC
Microsoft.Extensions.DependencyInjection
