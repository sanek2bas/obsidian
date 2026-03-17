1)
-- Issue #1052 Рефакторинг сущности CallBox 
2)
-- Bug # 19680 Voice Dispatch. Private Call box. При перехода на онлайн радио абонента PTT кнопка дизейблица на ~ 20 сек.
-- Bug #19715 Voice Dispatch. Не работает SelectPTT для Private PTT Grid 
-- RX in One 
-- Добавить правила оформления UML диаграмм
3)
-- Перенести вcе Workflow в One из Enterprise 
4)


ТЕКУЩАЯ ЗАДАЧА
Сделать вместо IMultiCallBox => IRadioCallBox, IPhoneCallBox
вытащить custombutton из callbox в PhoneBox
PttStateManager добавить Moq и тесты на краевые случаи


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


https://youtube.com/live/igYb8BwMTA4

**Базовый набор для большинства .NET-разработчиков**: **xUnit** (или NUnit) + **Moq** + **Coverlet** + **Fluent Assertions**.

