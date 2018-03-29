hambat
======

git clone - Клонирование

git add - Добавление файлов для закачки и отслеж. Если указать точку выберутся все файлы

git commit -m 'Название коммита' - Внутри кавычек коммит

git push -u origin master - так загружаем все изменения на репозиторий

git checkout -b branch_name - так создаем ветку и переходим по нему

git checkout branch_name - простой переходи от ветки к ветке


Порядок при ребейзе
======
git add .
git commit -m 'commit'
git checkout master
git pull
git checkout YOUR_BRANCH
git rebase
git push -f


