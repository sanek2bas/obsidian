1)
-- Task #1055 Выделить из CallBox PhoneCallBox
Выдклен отдельный класс PhoneCallBox, который создается для SystemPhoneBox и SingleLinePhoneBox
В классе от CallBox избавился от некоторых  dependecy properties, которые заменены на обычные свойства c OnPropertyChanged.
Осталось перенести в класс PhoneCallBox часть свойств из CallBox и проверить как работает чат, потмоу что в чате используется и Radio и Phone. После этого перейду на ConsolePatchBox
2)
-- Issue #1052 Рефакторинг сущности CallBox
-- Issue #1055 Выделить из CallBox PatchCallBox
-- RX in One к 5 марта
-- Добавить правила оформления UML диаграмм
-- унификация двух консолей в перспективе
3)
Стараюсь писать автотесты но без фанатазима, это съедает много времени. Пишу чтобы набить руку, плюсом это дает понимание кода, который запутан и дает возможность иногда этот код упростить.  Сильных изменений не хочу по коду, треубется терпение и аккуратность. 
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
