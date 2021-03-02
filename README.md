# qa_java_hw_7.1
# Счетчики плагина jacoco-maven-plugin: #

- INSTRUCTION 
- LINE 
- BRANCH 
- COMPLEXITY 

### INSTRUCTION ###
Инструкция байт-кода Java - наименьшая еденица измерения JaCoCo. Покрытие описывается как процент выполненных и пропущенных инструкций кода. Независит от форматирования файла исходного кода. Доступен даже при отсутствии отладочной информации.

### LINE 
Покрытие описывается как процент выполненных и пропущенных строк исходного кода. Зависит от форматирования исходного кода, в следствии чего одна строка может включать в себя несколько инструкций байт-кода. Результат анализа каждой строки подсвечивается в зависимости от количества инструкций покрытых тестом:
- Красный: Не выполнено ни одной инструкции; 
- Желтый: Выполнено часть инструкций;
- Зеленый: Выполнены все инструкции. Для работы необходимо компилировать файл с включением отладочной информации.

### BRANCH 
Вычисляется процент покрытия веток кода определенных операторами if и switch. Счетчик вычисляет количество веток определенное этими операторами и определяет количество выполненных и пропущенных. Поскольку одна ветка может включать в себя несколько инструкций байт-кода результат анализа каждой строки подсвечивается в зависимости от количества инструкций покрытых тестом:
- Красный: Не выполнено ни одной инструкции ветки; 
- Желтый: Выполнено часть инструкций ветки; 
- Зеленый: Выполнены все инструкции ветки. Доступен даже при отсутствии отладочной информации.

### COMPLEXITY 
Циклическая сложность - минимальное количество путей исполнения кода методов, которое принимается как количество возможных тестовых случаев. Таким образом счетчик вычисляет количество выполненных и пропущенных тестовых случаев для каждого метода. Доступен даже при отсутствии отладочной информации.

Окружение:

Windows 10 64 bit
Версия Java 11
