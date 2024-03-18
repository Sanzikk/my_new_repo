﻿# подсказки по командной строке 

команды смены директории 
```sh
cd c:/folder_name
```

отображение текущей директории для IOS и LINUX
```sh
pwd
```
листинг текущей директории 
```sh
dir
```

удаление файла windows
```sh
del <filename>
```

удаление файла ios linux 
```sh
rm <filename>
```

список всех коммитов 
```sh
git log ; git log --oneline
``` 
изменения между последними сохранениями 
```sh
git diff
``` 

изменения между определенными коммитами 
```sh
git diff (ключи из log)
```
список веток 
```sh 
git branch
```
добавить новую ветку 
```sh 
git branch name_branch
```
переход по веткам 
```sh 
git checkout name_branch
```
слияние веток, перейти на чистовую ветку 
```sh 
git merge name_branch
```
удаление ветки 
```sh 
git branch -d name_branch 
```
дерево веток 
```sh 
git log --graph
```
переход по директориям 
```sh 
cd Desktop/lesson2/
```

перейти на папку выше 
```sh 
cd ..
```
 
создать новую папку 
```sh
mkdir namefolder
```

переименование ветки 
```sh
git branch -M new_name
```

подключение удаленного репозитория 
```sh 
git remote add origin https://github.com/EnormousDaemon/my_new_repo.git
"origin" - даем назвавние нашему удаленному репоиторию 
 ```

 показать удаленный репозиторий 
 ```sh 
 git remote show
 ```


git push 
```sh 
git push -u origin main 
"origin" - подключенный сервер
"main" - ветка 
```

после того как связали локальный и удаленый рпозиторий можно писать 
```sh
git push - отправить изменения на гитхаб 

git init - вытянуть извмения с гитхаба 
```

удаление ветки на гитхаб 
```sh 
git push origin --delete branch_name
```
КОНФЛИКТ если сделать изменения на сайте и локально то будет конфликт 

команда пулл и пуш вместе (при разрешении конфликта)
```sh
git pull --rebase
```
дописали новые слова

