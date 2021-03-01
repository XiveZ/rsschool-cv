[Link on Markdown CV or](https://xivez.github.io/rsschool-cv/cv) https://xivez.github.io/rsschool-cv/cv

## Порядок работы

1. В своём GitHub аккаунте создайте публичный репозиторий с названием rsschool-cv
2. В главной ветке данного репозитория (main или master) должен находиться только один файл README.md
3. В файл README.md добавьте ссылку вида https://your-github-account.github.io/rsschool-cv/cv, в которой вместо your-github-account укажите свой GitHub username. После завершения работы по этой ссылке будет открываться страница CV
4. Создайте ветку gh-pages. В ветке gh-pages создайте файл cv.md.
5. Используя markdown-разметку в файле cv.md создайте своё CV
6. После завершения работы откройте Pull Request из ветки gh-pages в ветку master. Мержить Pull Request не нужно! 

## Требования к коммитам

- В ветке gh-pages должно быть не меньше 3-х коммитов.
- Названия коммитов дайте согласно гайдлайну

## Требования к Pull Request

- Название Pull Request дайте по названию задания. В данном случае название Pull Request - Markdown & Git
- Описание Pull Request дайте по схеме

## Как сабмитить задание

Markdown & Git - автопроверяемый таск.
После окончания работы над заданием зайдите в rs app https://app.rs.school/, выберите Auto-Test, в выпадающем списке выберите Markdown & Git, нажмите кнопку Submit. Справа отобразится результат проверки.

Сабмитить задание можно сколько угодно раз, каждый следующий сабмит перезаписывает предыдущий.

## Критерии оценки

Максимальный балл за задание +100

- выполнены требования к репозиторию +50
- выполнены требования к коммитам и Pull Request +50


<details>
    <summary>Уведомления об ошибках и их вероятные причины</summary>'

    1. 0 баллов и статус "Failed task requirements: No CV at ..." Отсутствует страница по адресу https://your-github-account.github.io/rsschool-cv/cv.
    Возможные причины: в вашем github аккаунте нет репозитория "rsschool-cv" с веткой "gh-pages" и файлом "cv.md". Или в ветке master нет файла README.md.

    2. 50 баллов и статус "Failed commit requirements: Less than 3 commits"
    Ответ: В вашей ветке "gh-pages" менее 3 коммитов.
    Вы можете проверить свои коммиты здесь: https://your-github-account.github.io/rsschool-cv/commits/gh-pages. Коммиты "Merge ..." или "Initial commit" игнорируются.

    3. 50 баллов и статус "Failed commit requirements: Commits do no follow guideline ..."
    Не все коммиты выполняются по правилам: https://docs.rs.school/#/en/git-convention Все коммиты, не отвечающие правилам, будут перечислены в статусе.

    4. 50 баллов и статус "Failed PR requirements: No Pull Request with task name (Markdown & Git)"
    Вы не отправили Pull Request с gh-pages в masterили название Pull Request не "Markdown & Git".
    Увидеть свой PR, вы можете здесь: https://your-github-account.github.io/rsschool-cv/pulls
</details>