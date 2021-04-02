При налчале любого проекта коипруем эту папку и переименовываем ее в название проекта и дальше работаем с ней как с основной.
Тут настроена интересная сборка Gulp.

1. Открываем папку в VScode и в консоли и пишем "npm i"
Галп подтянет всю сборку - если что вот ссылка на видос как делал https://www.youtube.com/watch?v=SVmnfkICqq0
2. Создаем репозиторий на https://github.com/corebenediktus/
3. !!Не забываем про gitignore (node_modules)!!
4. Пишем по очереди и в итоге заливаем первый коммит на гит на новый репозиторий: 
git init
git remote add origin https://github.com/corebenediktus/**Новый реп пишем тут**.git
git commit -m "add files and start project"
git push -u origin main


-----------------------
Рекомендации от Гита когда новый реп делаешь:
…or create a new repository on the command line
echo "# test01" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/corebenediktus/test01.git
git push -u origin main

…or push an existing repository from the command line
git remote add origin https://github.com/corebenediktus/test01.git
git branch -M main
git push -u origin main