# Шпаргалка Git

## Настройка и инициализация

- `git init` - инициализирует новый Git репозиторий в текущей директории.
- `git clone ` - создает локальную копию удаленного репозитория.

## Работа с изменениями

- `git status` - показывает текущий статус изменений в репозитории.
- `git add <файлы>` - добавляет файлы в индекс готовности к коммиту.
- `git commit -m "сообщение коммита"` - создает новый коммит с зафиксированными изменениями.
- `git diff` - показывает различия между рабочей директорией и индексом.

## Ветвление и слияние

- `git branch` - показывает список веток в репозитории.
- `git branch <имя_ветки>` - создает новую ветку.
- `git checkout <имя_ветки>` - переключается на указанную ветку.
- `git merge <имя_ветки>` - выполняет слияние указанной ветки с текущей.

## Работа с удаленным репозиторием

- `git remote add <имя> ` - добавляет удаленный репозиторий в локальный.
- `git push <имя_удаленного_репозитория> <имя_ветки>` - отправляет коммиты в удаленный репозиторий.
- `git pull <имя_удаленного_репозитория> <имя_ветки>` - загружает и объединяет удаленные изменения в локальный репозиторий.

## История и откат

- `git log` - показывает историю коммитов.
- `git checkout <идентификатор_коммита>` - переключается на указанный коммит (в режиме "detached HEAD").
- `git revert <идентификатор_коммита>` - создает новый коммит, который отменяет указанный коммит.
- `git reset <идентификатор_коммита>` - отменяет коммиты и перемещает указатель текущей ветки.