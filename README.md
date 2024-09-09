- Клонировал репозиторий от лабораторной работы №4
- Переключился на репозиторий для лабораторной работы №6
- Добавил CPackConfig.cmake
- Перестроил файл CI.yml

```console
$ git clone https://github.com/PNuikin/lab04 projects/lab06_h
$ cd projects/lab06_h/
$ git remote remove origin 
$ git remote add origin https://github.com/PNuikin/lab06_h
$ touch CPackConfig.cmake
$ edit CPackConfig.cmake 
$ edit .github/workflows/CI.yml
$ git add .
$ git commit -m"added cpack"
$ git push origin master
```