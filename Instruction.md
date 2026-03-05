# Инструкция по взаимодейсвию с dsliportable.exe 
Запуск происходит с пути расположения файла ```dsliportable.exe``` 

В моём случае это:
```
C:\Users\M.Vorontsova\source\repos\branch\vcpkg\build\Debug
```
Вызываем в директории ```cmd```
Список команд и что они делают:
1. ```dsliportable.exe -p COM3```  - команда подключения к последовательному порту устройств
2. ```dsliportable.exe -p COM3 -h``` - команда для вывода всего списка команд
3. ```dsliportable.exe -p COM3 -i``` - информация о файловой системе устройства
4. ```dsliportable.exe -p COM3 -f "C:\test_pakage\D800 packages\D800_All_release_OLD_Finalised.dstpkg"``` - команда **-f** указывает на путь расположения файла прошивки, в моём случае ```D800_All_release_OLD_Finalised.dstpkg```
