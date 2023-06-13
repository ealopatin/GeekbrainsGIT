![GB logo - create wiht support](https://raw.githubusercontent.com/ealopatin/GB/main/LogoGB.png)

# Краткое руководство по GIT
## **Основные команды**

* **git init** - создает локальный реопзиторий
* **git commit** - создает комментарий и контрольную точку
* **git add** - доавляем файл (-а в git commit - am - делает тоже самое)
* **git log** - список коммитов
* **q** - выйти из log
* **git status** - состояние файлов, изменения, удаление и пр.
* **git checkout "номер коммита"** - возвращает "назад" к прошлым коммитам
* **git checkout master** - возвращает к основному (последнему) коммиту 
* **clear** - очищает окно терминала
* **git diff** - показывает разницу между "коммитами"


Для 'облегчения' обучения 
[cсылка на тренажер](https://learngitbranching.js.org/)

## **Ветки**

* Git branch - выводит название строк

* Git branch branch_name - создает новую ветку с именем branch_name

* Git branc -d branch_name - удаляет ветку с именем branch_name

* Git branc -D branch_name - удаляет ветку с именем branch_name (без слияния)

## **Слияние**

Git merge branch_name - Добавляет информацию из branch_name в текущую ветку.


## **Изображение**

Чтобы вставить изображение досточно выполнить слующее:

![Комментарий к изображению](название файла)

![Hi! This is DAFT](daft.jpg)

## **Списки**

Чтобы выделить ненумированный список используйте (*)

* Номер 0
* Номер 1
* Номер 2

Чnобы добавить нумерованные списки нужно просто пронумеровать с точкой (1.)

1. Номер 0
2. Номер 1
3. Номер 2

## Gрочее

* git commit --amend -m "commit comment" - меняет комментарий к последнему коммиту



Добработка инструкции:

## Дополнительный список команд

* git add  
* git commit 
* git diff 
* git stash 
* .gitignore

* git status 
* git tag 
* git blame

* git checkout 
* git clean 
* git revert 
* git reset 
* git rm

* git init 
* git clone 
* git config