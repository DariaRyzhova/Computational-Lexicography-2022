## Задание 1

Из файла ['rnc_gostin.xml'](https://github.com/DariaRyzhova/Computational-Lexicography-2022/blob/main/rnc_gostin.xml) извлеките все наречия, т.е. все словоформы, у которых в грамматическом разборе присутствует тег 'ADV'.

## Задание 2

Из файла ['rnc_gostin.xml'](https://github.com/DariaRyzhova/Computational-Lexicography-2022/blob/main/rnc_gostin.xml) извлеките все текстовые данные, т.е. распечатайте сам текст со знаками препинания без каких-либо элементов разметки.

## Задание 3

Возьмите файл ['eng-rus.tei'](https://github.com/DariaRyzhova/Computational-Lexicography-2022/blob/main/eng-rus.tei). Напишите программу, которая на вход получает английское слово, а на выходе дает его переводы на английский язык, разбитые по значениям. Например:

American
1. американский
2. американец

## Задание 4

Переведите словарь из файла ['en-ru-test.txt'](https://github.com/DariaRyzhova/Computational-Lexicography-2022/blob/main/en-ru-test.txt) в XML-формат следующего вида: 

```xml
<body>
  <entry>
    <form lang="English">American</form>
    <sense>американский</sense>
    <sense>американец</sense>
    <sense>американка</sense>
  </entry>
  ...
</body>
```

Запишите результат в файл.
