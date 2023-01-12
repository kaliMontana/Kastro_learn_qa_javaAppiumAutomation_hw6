## Kastro_learn_qa_javaAppiumAutomation_hw6

##Ex10: Настройка работы на iOS
###Для тех, кто проходит курс без макбук, надо просто описать полный набор действий и программ для того, чтобы начать автоматизировать приложения на iOS. Следует указать полный стек - Java, Appium, XCode и так далее...

1- Установить среду разработки  XCode 13 или выше мз App store.

2- Скачать Appium Desktop версии 1.21.0

3- Удалить из Intellij Idea старую версию библиотеки java_client.jar и установить версию 7.1.

4- Скачать версию Selenium версии 3.14 и установить ее вместо 3.04.

5- Скачать и подключить библиотеку javax.websocket-api-1.1.jar.

6- Скачать app Wikipedia и распокавать ее для установки.

7- Установка wikipedia через терминал.
- Поменять папку где распологается уставщик.
- Установить различные зависимости для работы с проектом через команду scripts/setup.

8- Запустиь файл приложение Wikipedia.xcodeproj в папке eго расположения.

9- Скомпилировать проект.

10- Быбирать симулатор iPhone SE (9.3).

11- Запустить проект.

12- Запустить приложение через API.
- Открыть xcode и выбирать симулатор iPhone SE 11.3.
- Скопировать в рабочую столь файл Wikipedia.app.
- Открыть Appium.
- Запускать Inspector Sessions.
- Заполнять Capabilities:
  - "platformName": "IOS",
  - "platformVersion": "11.3",
  - "deviceName": "iPhone SE",
  - "app": "/directory/Wikipedia.app"
- Запускать сессию.

13- В проекте в IDEA поменять название класса настройки на iOSTestCase.
- Поменять capabilities и удалить те, которые ненужные.
- Поменять class driver на IOSDriver.

14- В папке tests создать папку iOS.
- Создать class GetStartTest для начать писать тесты.

15 - Чтобы написать универсальные тесты для Android и для IOS надо переписать их.