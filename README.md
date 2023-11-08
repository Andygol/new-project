# Створення репозиторію

```
git init <name of the project>
cd <name of the project>
```

В результаті ви отримаєте локальне сховище для свого проєкту з типовою гілкою "name".

## Створення файлу README.md

```
touch README.md
```

## Створення гілки

```
git checkout -b <branch_name>
```

Докладніше див <https://git-scm.com/docs/git-checkout#Documentation/git-checkout.txt-emgitcheckoutem-b-Bltnew-branchgtltstart-pointgt>

Ця команда призведе до створення нової гілки з вказаною назвою.

```
vim README.md
```

В редакторі vim змініть файл `README.md` використовуючи правила розмітки документів Markdown.

Після завершення редагування файлу збережіть його, натиснувши <kbd>ESC</kbd> та увівши команду `wq` у командному рядку редактора.

## Збереження змін

```
git add .
git commit -m "description of work"
```

## Обʼєднання змін

Перенесення змін з гілки розробки до основної гілки репозиторію

```
git checkout main
git merge development
```
