### Тема 1. Транспиляция и сборка проекта с использованием директив импорта и экспорта в код с модульностью CommonJS


1)Создание проекта

```
yarn init -y
```


2)Добавление зависимостей

```
yarn add -D babel-cli babel-preset-env
```

3)Настройка Babel (файл .babelrc)


4)Добавление библиотеки moment

```
yarn add moment
```


5)Команда транспиляции

```
babel-node ./src/index.js
```


6)Сборка проекта

```
babel ./src -d ./lib
```

Файлы main.js и name.js находятся в отношении нативной модульности.

Исходные файлы расположены в директории src, транспилированные - в директории lib.

