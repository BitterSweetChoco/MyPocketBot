# MyPocketBot
ENG

> A pocket robot companion on ESP32-C3 SuperMini. Pixel face, autonomous behavior, and a library of book quotes

Core principle of the project: every new feature should be added as a separate module without requiring a rewrite of the entire firmware.

Project goals

- Create a compact robot in a pocket-sized enclosure
- Make an expressive pixel face with animations
- Implement autonomous behavior without requiring an internet connection
- Respond to buttons and, later, to additional sensors
- Store settings and a small amount of state between reboots
- Create a structured library of book quotes
- In the future, add recognition of emotional signals, voice output, and connection to external services
- Keep the firmware architecture simple and extensible

In the first version, its character will be expressed through:
- gaze, blinking, and eye movements;
- changing facial expressions;
- reactions to button presses;
- periods of activity and sleep;
- small independent actions during idle moments

Main controller

ESP32-C3 SuperMini

Expected tasks:
- running the main logic;
- controlling the display;
- handling buttons and sensors;
- launching animations;
- storing settings in flash memory;
- potential Wi-Fi and Bluetooth connectivity
- - -
RU


> Карманный робот-компаньон на ESP32-C3 SuperMini. Пиксельное лицо, автономное поведение и библиотека книжных цитат

Основной принцип проекта: каждая новая функция должна добавляться отдельным модулем, не требуя переписывать всю прошивку.

Цели проекта

- Создать компактного робота в карманном корпусе
- Сделать выразительное пиксельное лицо с анимациями
- Реализовать автономное поведение без обязательного подключения к интернету
- Реагировать на кнопки и, позднее, на дополнительные датчики
- Хранить настройки и небольшое количество состояния между перезапусками
- Создать структурированную библиотеку книжных цитат
- В перспективе добавить распознавание эмоциональных сигналов, голосовой вывод и подключение к внешним сервисам
- Сохранить простую, расширяемую архитектуру прошивки

В первой версии его характер будет выражаться через:
- взгляд, моргание и движения глаз;
- смену выражений лица;
- реакции на нажатия кнопок;
- периоды активности и сна;
- небольшие самостоятельные действия в моменты бездействия

Основной контроллер

ESP32-C3 SuperMini

Предполагаемые задачи:
- выполнение основной логики;
- управление дисплеем;
- обработка кнопок и датчиков;
- запуск анимаций;
- хранение настроек во flash-памяти;
- потенциальное подключение по Wi-Fi и Bluetooth
