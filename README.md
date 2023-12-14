Расположение репозитория с кодом, как посмотреть существующий код:
Https access: https://github.com/OlgaRomanovna/ssf_site.git
SSH access: git@github.com:OlgaRomanovna/ssf_site.git 

как устроен процесс внесения своих изменений в основную кодовую базу;
Определение состояния файлов \\ git status
Отслеживание новых файлов и добавление изменений из рабочей области проекта в индекс \\ git add
Сделать коммит на основе индекса \\ git commit
Запушить коммит в удалённый репозиторий. \\ git push

каковы правила именования веток
Основная ветка – master
Ветка для изменений - branch


Настройка среды разработки: 
Installing PyCharm CE
Click on “Settings -> Version Control -> GitHub -> +” button
Enter login and pass from GitHub site
Connection and sync are successfully with GitHub repository

инструкция для младших сотрудников по слиянию веток, какие команды надо выполнить, чтобы: 
 git clone it@github.com:OlgaRomanovna/ssf_site.git 
cd ssf_site.git
git status
git checkout -b team-branch
git status
touch team_first.html
touch team_second.html
git add .							
git commit -m "added team_first.html and team_second.html in team-branch”	    
git push origin team-branch	
git status
git checkout master
