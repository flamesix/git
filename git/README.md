git status —
git add —
git commit -m ‘message’ —
git commit -am ‘message’ —
git commit --amend — заменяет предыдущий коммит новым
git log — просмотр истории комиков
git log --oneline 
git log --oneline --all
git reflog — просмотр истории действий
git reset — сброс текущего состояния истории
git revert — отмена последствий коммита
git restore — сброс состояния фала на указанное
git branch — показ веток репозитория
git branch dev — создание ветки с именем dev
git checkout dev — переключение на ветку dev
git branch dev-master master — создание ветки dev-master с точкой старта master
git checkout -b dev-test — переключает на ветку dev-test если ее еще нет, то создает и переключает
git clone ccылка_по_SSH foder — клонирует репозиторий по ссылке в папку folder
git remote -v — 
git push —  загружает все локальные изменения репозитория на сервер
git push -u origin dev — загружает локальные изменения на новую ветку dev которая еще не создана на сервере
git pull — загружает изменения с сервера
git fetch — подгрузить обновления из репозитория
git merge dev — слияние ветки dev в ветку в которой находимся
git branch -d dev dev_cracken — удалит ветки dev и dev_cracken
git push --delete origin dev dev_cracken — удалит ветки с сайта GitHub 
git add . — добавляет все файлы в текущей директории
git rebase main  — сдвигает текущий branch на последний кормит main
git tag 1.0.0 — устанавливает версию 1.0.0 на последний коммит
git tag — вывод номер версии
git tag - - list  — выводит список версий
git push --tags — загружает версии на сервер
git tag -d 1.0.1 — удалит тег 1.0.1 
git push --delete origin 1.0.1 — удаляет тег 1.0.1 (откатить версию проекта)
git stash — сохранение во временно хранилище
git stash list — список стэш коммитов
git stash push <filename> — добавить новый файл к существующему стешу
git stash pop stash@{1} — создать изменение на ветке из стэша
git merge <branch> -dev --squash — находясь в master объединим коммиты ветки  squash-dev
git reset --hard — сброс репозитория на состояние последнего коммита
git rebase -i HEAD~X — X это количество объединяемых коммитов
git cherry-pick <commit> -- перенос коммита в другую ветку
git cherry-pick <branch> — перенести последний коммит ветки
git cherry-pick ..<branch> — перенести все коммиты с ветки
