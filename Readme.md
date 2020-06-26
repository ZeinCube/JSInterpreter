# JS Interpreter written on Java (yeah, like Nashorn but last one works)
1. Грамматика взята из [этого репозитория](https://github.com/antlr/grammars-v4/tree/master/javascript/javascript)
2. Делаем maven install, ждем пока установится antlr
3. ПКМ по JavaScriptLexer.g4, настраиваем как нам угодно, язык реализации Java.
4. ПКМ по JavaScriptParser.g4, делаем тоже самое
5. Все готово, парсер и лексер сгенерированы
