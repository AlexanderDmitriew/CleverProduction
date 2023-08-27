# Инструкция для старту работы
1. Скопируй ссылку на репозиторий и выполни команду
`git clone <link_to_rep>`

2. Обязательно выполни в консоли следующие строки

` git config --global user.name <User_name> `  
` git config --global user.email <emal@email> `  
` git config --global alias.history "log --graph" `  

---

## Инструкция для новичков

Для правильной работы с репозиториями тебе необходимо:

1. Клонировать этот репозиторий к себе локально.
2. Создать ветку со своей Фамилией.ИО
   `git checkout -b <ТвояФамилия.ИО>`
3. После этого можешь приступать к работе с кодом. Как только ты выполнишь работу сохрани изменения в гит
   
   `git status - посмотри какие файлы изменены`  
`git add <файлы, который ты поменял>`  
`git commit -m 'Сообщение с описанием что ты сделал' `  
`git push origin <Твоя ветка>`  
5. Зайди на Github в репозиторий проекта и создай pull request. В качестве проверяющего укажи своего тимлида.
