1)
-- Task #1055 Выделить из CallBox PhoneCallBox
Рефакторинг CallBox в модуле Chat, это коснется модуля Notification
	продолжаю задачу (много времени потратил на избавление CallBox от dependency properties в итоге оставил как есть, с этим лучше потом, там придется поработать с xaml) 
2)
-- Issue #1052 Рефакторинг сущности CallBox
-- Issue #1055 Выделить из CallBox PatchCallBox
-- RX in One к 5 марта
-- Добавить правила оформления UML диаграмм
-- унификация двух консолей в перспективе
3)
4)


ТЕКУЩАЯ ЗАДАЧА
Отделить Phone от CallBox
вытащить custombutton из callbox в PhoneBox
не нужно отвлекаться на vbsettings


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

- `ollama run llama3` (хорош в логике)
- `ollama run qwen2.5-coder` (специально обучен для кода, отличный выбор для доков)
- `ollama run deepseek-coder-v2` (высокая производительность)
