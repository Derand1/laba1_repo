1. Я удалил точку с запятой после метода .ToArray() в в файлу WeatherController.cs
2. Сообщение с ошибкой:
Error: D:\a\laba1_repo\laba1_repo\MyFirstCI.Api\Controllers\WeatherController.cs(21,23): error CS1002: ;expected
[D:\a\laba1_repo\laba1_repo\MyFirstCI.Api\MyFirstCI.Api.csproj]
3. Пайплайн упал на шаге билда потому что компилятор ожидал точку с запятой после метода
4. Добавил ожидаемую точку с запятой
