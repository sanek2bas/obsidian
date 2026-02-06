

1)
-- Bug #987 Bug #18851. Text Chat. PTT. Из чата перестает отрабатывать кнопка PTT, если перейти на другой чат.
	(в процессе)
2)
-- Issue #1052 Рефакторинг сущности CallBox
-- Ioc/RX к 19 февраля
-- унификация двух консолей в перспективе
3)
4)


ТЕКУЩАЯ ЗАДАЧА
bug 987 - при переходе между чатами сбрасывается вызов в CallStateResolver в коллекции ending крутится этот бокс. 
1) при переключении между чатами создавать новый бокс callbox
2) сделать Sender для отправки Begin/End Transmit


ЧТО ХОЧЕТСЯ СДЕЛАТЬ

InitTransmitInfoSender - попробовать написать + тесты
Перенести таймер из CallStateResolver в InitTransmitInfoSender





-- В режиме non sticky mode быстро оптускаю PTT, в enterprise есть синхронизация
убрать првоерку Pttenabled для EndTransmit

-- Сделать синхронизацию бокса по хоткей и нажатию сам бокс 
-- убрать таймер из callstateresolver добавить таймер в синхронизатор

-- попробовать сделать тесты для синхронизатора

-- сделать binding to enum в PttButtonWidget (SelectPttButtonViewType)




-- IOС сравнить Microsoft.Extensions.DependencyInjection и Autofac
	как добавить сущесвтующий объект в контейнер
	зачем Services и builder
	
-- Сделать state machine в боксе 
-- Добавить тестов на state machine 


Пример по RX
Сделать пример с кнопкой PTT которая будет блокироваться на некоторое время, в этом время будет прогресс бар

Пример по IOC


ерекинуть workflow в One
начать рефакторинг CallBox



-- IOС сравнить Microsoft.Extensions.DependencyInjection и Autofac
	как добавить сущесвтующий объект в контейнер
	зачем Services и builder
	
-- Сделать state machine в боксе 
-- Добавить тестов на state machine 