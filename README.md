1. Создать репозиторий на GitHub и сделать git clone [URL] на пк
2. Создать ветку разработки develop от главной ветки [master, main]
3. Создать от ветки develop feature/[имя] - ветки и мержить их develop
4. Создание ветки release/0.1.0 от develop [git checkout -b [имя_ветки]]
5. Когда ветка release/0.1.0 закончена она мержится в main и develop и удаляется git branch -d [имя_ветки]
6. Создание ветки "hotfix/about-page-title"
7. Мержим "hotfix/about-page-title" в main и develop
