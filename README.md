#  Домашнее задание

1) Ознакомится с написанным кодом. Для чего создан данный модуль?
Resource - Создает абстракцию ресурса доступного по HTTP, инкапсулирует в себе все необходимые данные для запроса и парса ответа. 
2) Что значит @escaping в передаваемых замыканиях?
Данная анотация указывает на то, что замыкание не следует удалять из памяти, потому что оно может быть использовано в дальнейшем после выхода из функции
3) Почему в некоторых протоколах идет наследование от класса(: class)?
Исходя из семантики протокола иногда необходимо поведение ссылочного типа нежели типа значений, поэтому на протокол накладывается ограничение class (AnyObject)
4) ✅ Реализовать методы которые выдают ошибки(в их теле есть пометки #error)
5) ✅ Поправить релизацию протокола Codable для JSONObject(находится в UnitTests), для того чтобы два написанных теста выполнялись успешно(тесты менять не надо)
