# Создание проекта в Xcode.
1. Запустить Xcode, выбрать `Create a new Xcode project`
![Xcode](xcode_21/Screen_Shot_01.png)
* Выбрать `macOS`, `Command Line Tool`
![Xcode](xcode_21/Screen_Shot_02.png)
* Ввести название проекта, своё имя в `Organization name`, свой ник в `Organization Identifer`, выбрать Language `C`.
![Xcode](xcode_21/Screen_Shot_03.png)
* Выбрать папку, где будет размещаться проект. Можно так же сразу создать репозиторий Git, но это не обязательно, к репозеторию intra он не имеет отношения. 
![Xcode](xcode_21/Screen_Shot_04.png)
* Так будет выгядеть вновь созданный проект.
![Xcode](xcode_21/Screen_Shot_05.png)
* Подключим norminette для автоматической проверки проекта.
Для этого перейдём в командную строку и запустим `norminettelint -s c00`, где `c00` - имя папки с проектом Xcode. norminettelint устанавливаем отсюда: [https://github.com/DimaRU/NorminetteLint](https://github.com/DimaRU/NorminetteLint)
![Xcode](xcode_21/Screen_Shot_12.png)
