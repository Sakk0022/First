# Знакомство с разметкой md
# Справочник команд и флагов программы Git

## Создание репозитория

git init


## Основы конфигурации

git config --global user.name "Aleksander Shchudro"
git config --global user.email aleksandrsudro@gmail.com
cat .git/config
git config --list
git config --unset user.name
git config --global core.editor "code --wait"
git config --help
git help config
git config -h


## Узнать статус файлов

git status


## Проиндексировать файлы
### Один файл

git add one.html

### Все файлы в папке проекта

git add .


## Сделать коммит

git commit -m 'Add file one.html'


## Показать текущий коммит

git show


## Показать текущий коммит со всеми подробностями

git show --pretty=fuller


## Коммит без `git add`

git commit -am 'Rename hello to helloGit!'
git commit -m 'Ignore file' .gitignore


## Удаление и переименование файлов
### Коммит с очисткой

git commit -m 'Clean up'

### Удаление папки

git rm -r src

### Удаление папки из индекса, но не с диска

git rm -r --cached src

### Принудительное удаление файла

git rm -f one.html


---

### Пример ссылки
[Git hub]([https://github.com/Sakk0022])

### Пример картинки
![git](https://timeweb.com/ru/community/articles/kursy-po-rabote-s-git-i-github-vklyuchaya-besplatnoe-onlayn-obuchenie-dlya-novichkov)

### Пример кода
```python
print('Hello, md!')
