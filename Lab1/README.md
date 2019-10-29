# devlabs

## Repository for devops course

1. Створив порожній репозиторій на Github, створив однойменний каталог на локальній машині, ввів в консолі наступні команди.

	```console
	ronix@DESKTOP-4AVNFCB MINGW64 /d/Study/GIT(technologii)/devopsLabs (master)
    $ echo "# devlabs" >> README.md
	ronix@DESKTOP-4AVNFCB MINGW64 /d/Study/GIT(technologii)/devopsLabs (master)
    $ git init
	Initialized empty Git repository in D:/Study/GIT(technologii)/devopsLabs/.git/
	ronix@DESKTOP-4AVNFCB MINGW64 /d/Study/GIT(technologii)/devopsLabs (master)
    $ git add README.md
	ronix@DESKTOP-4AVNFCB MINGW64 /d/Study/GIT(technologii)/devopsLabs (master)
    $ git commit -m "lab1:first commit"
	[master (root-commit) f8b1e7d5] lab1:first commit
	1 file changed, 1 insertion(+)
	create mode 100644 README.md
	ronix@DESKTOP-4AVNFCB MINGW64 /d/Study/GIT(technologii)/devopsLabs (master)
    $ git remote add origin https://github.com/airdy/devopsLabs.git
	ronix@DESKTOP-4AVNFCB MINGW64 /d/Study/GIT(technologii)/devopsLabs (master)
    $ git push -u origin master
	```
    
2. Додав введені команди у файл README.md, закомітив до репозиторію.   
3. Визначив хеш коміту ввівши команду
    ```console
	ronix@DESKTOP-4AVNFCB MINGW64 /d/Study/GIT(technologii)/devopsLabs (master)
    $ git log
    commit 2a7ac6116947e17e16ef772e4878fb329fca6305 (HEAD -> master, origin/master)
    Author: airdy <jalbot17@gmail.com>
    Date:   Tue Oct 29 18:58:24 2019 +0200

    lab1:second commit

	```
4. Створив нову гілку та переключився на неї. Використав команду git checkout.
5. Перейшов на гілку master зміни не відображались у файлі README.md бо змінювався файл в іншій гілці.
6. Змержив гілку second_branch у основну master конфліктів не відбулось.
7. Конфліктів не відбулось.
