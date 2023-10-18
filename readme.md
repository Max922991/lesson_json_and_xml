# Пример работы с Gson, Jackson, JAXB

Код приложения написанного на вебинаре 17.10.2023 для
обучающей платформы [Skillbox](https://skillbox.ru)

📺 Видео вебинара - https://youtube.com/watch?v=merXDL4nJyo

Приложение с реализацией:

- получения курс валют по http
- десериализация в Java объекты из JSON и XML
- сериализация из Java объектов в JSON и XML

## Требования для запуска

- JDK 17
- Maven 3.8.x
- Подключение к интернету для получения курсов валют

## Примеры JSON и XML

Для удобства файлы JSON и XML для которых написана
обработка сохранены в [📄 currencies.json](currencies.json) и [📄 currencies.xml](currencies.xml)

## Презентация

[📄 PDF файл с презентацией](presentation.pdf) показанной на вебинаре.

## Основные классы

- [MainGson](src/main/java/org/example/MainGson.java) - пример работы с Gson
- [MainJackson](src/main/java/org/example/MainJackson.java) - пример работы с Jackson
- [MainXml](src/main/java/org/example/MainXml.java) - пример работы с JAXB

## Локальный запуск

### Терминал

> [!NOTE]
> Все команды выполняйте находясь в корне проекта/репозитория

Соберите JAR файл:

```bash
mvn clean package
```

Для запуска примера Gson:

```bash
java -cp target/JsonXmlParser.jar org.example.MainGson
```

Для запуска примера Jackson:

```bash
java -cp target/JsonXmlParser.jar org.example.MainJackson
```

Для запуска примера JAXB:

```bash
java -cp target/JsonXmlParser.jar org.example.MainXml
```

### IntelliJ IDEA

Запустите main методы классов MainGson, MainJackson, MainXml


## Держим связь

- Мой канал в телеграм про жизнь в IT и всего интересного
и полезного встретил - [@three_monitors](https://t.me/three_monitors)
- Вопросы пишите мне в телеграм [@sendel](https://t.me/sendel)
- Группа [@JavaKeyFrames](https://t.me/JavaKeyFrames) по решению алгоритмических задач, разбор технологий
