## Тестирование мобильного приложения "Wikipedia"

### Технологии и инструменты
<div align="left">
    <code><img alt='IntelliJ IDEA' height='42' title='IntelliJ IDEA' src='images/intellij-idea.svg'></code>
    <code><img alt='Java' height='42' title='Java' src='images/java.svg'></code>
    <code><img alt='Selenide' height='42' title='Selenide' src='images/selenide.svg'></code>
    <code><img alt='Gradle' height='42' title='Gradle' src='images/gradle.svg'></code>
    <code><img alt='JUnit5' height='42' title='JUnit5' src='images/junit5.svg'></code>
    <code><img alt='BrowserStack' height='42' title='BrowserStack' src='images/browserstack.svg'></code>
    <code><img alt='Android Studio' height='42' title='Android Studio' src='images/android-studio.svg'></code>
    <code><img alt='Appium' height='42' title='Appium' src='images/appium.png'></code>
    <code><img alt='Appium Inspector' height='42' title='Appium Inspector' src='images/appium-inspector.png'></code>
</div>

---
#### Инструкция к Win10:
После установки **Android Studio**, **Appium** и **Appium Inspector** перейти в:

`Мой компьютер` -> `Свойства` -> `Дополнительные параметры системы` -> `Переменные среды` -> `Системные переменные` - `Создать`.

- Прописать:
    - Имя переменной: ANDROID_SKD_ROOT
    - Значение переменной: C:\Users\USER_NAME\AppData\Local\Android\Sdk
    - Имя переменной: ANDROID_HOME
    - Значение переменной: C:\Users\USER_NAME\AppData\Local\Android\Sdk

<div align="center">
    <img alt='System Variables' height='400' title='System Variables' src='src/test/resources/img/systemVariables.jpg'>
</div>

## Результат выполненого теста на BrowserStack

<div align="center">
    <img alt='System Variables' height='560' title='System Variables' src='src/test/resources/img/browserStack-successfulTest.png'>
</div>

## Результат выполненого теста на Android Studio

<div align="center">
    <img alt='System Variables' height='553' title='System Variables' src='src/test/resources/img/androidStudio-successfulTest.png'>
</div>