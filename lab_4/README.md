1. Встановлюю докер, перевіряю чи він працює за допомогою команд та перенаправляю вивід цих команд у файл `my_work.log`. Додаю цей файл до репозиторію.
2. Створюю імедж.Створюю файл з іменем `Dockerfile`, копіюю туди вміст такого ж файлу з репозиторію `devops_course`.Ознайомлююсь із коментарями та структурою написання `Dockerfile`. Замінюю посилання на власний Git репозиторій із веб-сайтом та роблю коміт даного `Dockerfile`.
3. Створюю власний аккаунт на Docker Hub та створюю новий репозиторій `lab_4`.
4. Виконую білд (build) Docker імеджа та завантажую його до репозиторію. Для цього вказую правильну назву репозиторію та TAG. Команда буде виглядати так (де django - це тег)
    [Посилання на Docker Hub репозиторій](https://hub.docker.com/repository/docker/ron1x/lab_4);
    Посилання на скачування імеджа: `ron1x/lab_4:django`;
5. Створюю ще один контейнер із програмою моніторингу для веб-сайту:
   - створию ще один Dockerfile (Dockerfile.site) в якому поміщаю програму моніторингу;
   - виконую білд даного імеджа, даючи йому тег `monitoring`, та заливаю його до репозиторію;
   ```bash
   docker build -f Dockerfile.site -t ron1x/lab_4:monitoring .
   docker push ron1x/lab_4:monitoring
   ```