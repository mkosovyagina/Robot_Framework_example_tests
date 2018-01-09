# Robot_Framework_example_tests
This repository contains some simple examples of Robot Framework test using standart libraries.
______________
КРАТКАЯ СПРАВКА О ROBOT FRAMEWORK

  Robot Framework - фреймворк общего назначения. Используется преимущественно для разработки приемочных тестов, однако с его помощью
возможно автоматизировать ФТ. Написан на Python, как и его библиотеки, соответственно, автотесты также пишутся преимущетвенно с использованием Python. Однако возможно написание тестов на Java, C#, Ruby (но необходимо предварительно подключить соответствующие библиотеки).
  RF обладает архитектурой, которая позволяет подключать разнообразные инструменты, что делает возможным взаимодействие с операционной системой,  веб-приложениями, приложениями Windows и т. д.
  RF реализует подход keyword-driven testing. 

______________
НАЧИНАЯ РАБОТУ

Чтобы запустить тесты, необходимо предварительно установить Python и Robot Framework. Подробная видео-инструкция здесь:
https://www.youtube.com/watch?v=HHuC0BkbX2c&feature=c4-overview-vl&list=PLFE3A6F4404582D5B


______________
ПРИМЕРЫ ТЕСТОВ С ИСПОЛЬЗОВАНИЕМ ROBOT FRAMEWORK:
  Каждый пример содержит текстовый файл с написанным test suit, результаты запуска тестов (report.html, log.html, output.xml) и пакетный файл.
  1. HelloWorld - содержит 2 test case. Первый выводит выводит в лог фразу Hello World, второй - HELLO WORLD Используются buitlin кейворды. Присутствует только обязательная таблица Test cases.
  2. CreateDirectory - создает в папке с txt-файлом новую директорию. Демонстрирует пример использования таблицы Settings для подключения стандартной бибиотеки OperatingSysytem/


