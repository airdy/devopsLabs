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