# Процедура запуска автотестов
* клонировать [репозиторий](https://github.com/jborisovna/qamid_diplom_) командой git clone;
* открыть проект fmh-android в Android Studio;
* запустить приложение на эмуляторе или устройстве Android API 29; 
* запустить тесты через терминал командой `./gradlew connectedAndroidTest`;
* дождаться прогона автотестов.
# Формирование отчета AllureReport
* выгрузить с эмулятора или устройства каталог `/data/data/ru.iteco.fmhandroid/files/allure-results`;
* выполнить в терминале команду `allure serve`, находясь на уровень выше папки allure-results;
* дождаться генерации отчета и посмотреть его в открывшемся браузере.
