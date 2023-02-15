# lecture_24_JS_Function_Expression

#  [Задачи ](https://github.com/schoolteacherMP/lecture_24_JS/blob/main/tasks.md)   

-  Функции – это значения. Они могут быть присвоены, скопированы или объявлены в любом месте кода.  
-  Если функция объявлена как отдельная инструкция в основном потоке кода, то это “Function Declaration”.  
-  Если функция была создана как часть выражения, то это “Function Expression”.  
-  Function Declaration обрабатываются перед выполнением блока кода. Они видны во всём блоке.  
-  Функции, объявленные при помощи Function Expression, создаются только когда поток выполнения достигает их.  

В большинстве случаев, когда нам нужно объявить функцию, Function Declaration предпочтительнее, т.к функция будет видна до своего объявления в коде. Это даёт нам больше гибкости в организации кода, и, как правило, делает его более читабельным.  

Исходя из этого, мы должны использовать Function Expression только тогда, когда Function Declaration не подходит для нашей задачи.  
