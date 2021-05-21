# CodeGit
# Коды
## Просто Коды
### Еще коды
#### Все еще коды
##### Маленькие буквы кодов
###### Cods
[Сайт гита](https://github.com)

[Песочница по обучению гита](https://learngitbranching.js.org/?locale=ru_RU "learngitbranching")

+git commit - мы только что внесли изменения в репозиторий и сохранили их как коммит. У коммита, который мы только что сделали, есть родитель, С1, который указывает на предыдущий коммит.
+ git branch newImage - Создадим здесь новую ветку с именем newImage.
⋅⋅* git checkout newImage - Эта команда перенесёт нас на новую ветку в момент, когда мы ещё не коммитили изменения.
⋅⋅* git checkout -b bugFix; git commit - создать новую ветку и переключиться на неё.
⋅⋅* git merge bugFix - Мы сделаем merge ветки bugFix в ветку main. Выполнив слияние.
⋅⋅* git checkout bugFix; git merge main - каждая ветка содержит все изменения репозитория!
⋅⋅* git rebase main - позволяет слить сдвинуть наши изменения из bugFix прямо на вершину ветки main. Благодаря этому всё будет выглядеть, как будто эти изменения делались последовательно, хотя на самом деле - параллельно.
⋅⋅* git checkout main^ - Перемещение на один коммит назад
⋅⋅* git checkout main~<num> - Перемещение на num коммит назад
⋅⋅* git branch -f main HEAD~3 - Переместит (принудительно) ветку main на три родителя назад от HEAD.Можно напрямую прикрепить ветку к коммиту при помощи опции -f
⋅⋅* git reset - отменяет изменения, перенося ссылку на ветку назад, на более старый коммит. Это своего рода "переписывание истории"; 
⋅⋅* git revert - Чтобы отменить изменения и поделиться отменёнными изменениями с остальными, надо использовать 
⋅⋅* git cherry-pick <Commit1> <Commit2> <...> - Это очень простой и прямолинейный способ сказать, что ты хочешь копировать несколько коммитов на место, где сейчас находишься (HEAD). Мы обожаем cherry-pick за то, что в нём очень мало магии и его очень просто понять и применять.
⋅⋅* git rebase -i HEAD~4 - Всё, что нужно для интерактивного rebase - это опция -i


Некоторые коды гита.
