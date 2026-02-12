1)
-- Task #1055 Выделить из CallBox PhoneCallBox
Класс PhoneCallBox задействован в VD, переношу этот класс в чат и нотификации, потому что боксы тоже там задействованы
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
