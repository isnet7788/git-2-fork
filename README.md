# Привет! 👋

Это учебный репозиторий Нетологии. На его примере мы продемонстрируем работу с Fork и ветками в GIT. 

## 

Настройка глобальных настроек
git – version
git config --global user.name “Emma Paris”
git config --global user.email “eparis@atlassian.com”
git config --global core.autocrlf input
git config --global core.safecrlf warn
git config --global core.quotepath off
git config --global init.defaultBranch main

Создание репозитория
git init

Как создать коммит?
Добавьте файл или файлы в отслеживаемые командой git add имя файла или git add -А (для многих файлов)
Создайте коммит и подпишите его командой git commit -m "Подпись коммита"

Как проверить состояние файла?
На любом из этапов вы можете выполнить команду git status

Как прочитать историю коммита?
Выполните в терминале команду git log --oneline

Как исправить историю коммита?
Внесите изменения в файл
Сохраните файл и добавьте его в отслеживаемые через команду git add имя файла. Если нужно добавить сразу несколько файлов, то используйте флаг -A git add -А
Поместите файл в последний коммит — снова используем команду git commit --amend -m “название изменений”.

Как переключиться между коммитами?
Переключиться между коммитами проекта можно командой git checkout хеш
Вернуться к последнему коммиту можно командой git checkout -


Создание SHH
ssh-keygen

Чтобы отправить что-то в удалённый репозиторий, нужно воспользоваться командой git push -u origin main

Клонирование по ssh
git clone git@github.com:------------

Просмотр веток git branch

Создание ветки git branch newvetka

Переход в ветку git checkout newvetka

Удаление ветки git branch -d vetka

Отправляем ветку в удаленный репозиторий
git push -u origin newvetka

Просмотр изменений ветки git log newvetka 
Просмотр измеений в одну ветку git log newvetka --oneline

Сливаем ветки git merge newvetka

Исправление комента git commit --amend -m "Initial commit"

Создаем новую ветку и в нее переходи git checkout -b novaiavetka

Добавляем файл и сразу комитт git commit -a -m "nash coomment"

