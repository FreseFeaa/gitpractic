# Практика работы с Git

Этот репозиторий был создан для повторения/изучения команд git

`git init`   - Инициализирует локальный git-репозиторий

`git add . `  - Добавляет все файлы (Для коммита например)

`git commit -m "first commit   WOOOW"`    - Коммитит с сообщением (Обычно сюда пишут информацию про коммит)

`git branch feature ` - Создает новую ветку feature

`git checkout feature ` - Переключаемся на ветку feature

`git checkout master`  - Переключаемся обратно на ветку master

`git merge feature`  - Делаем слияние ветки feature в нашу ветку (master)

`git remote add origin https://github.com/FreseFeaa/gitpractic.git`   - Подключаем удалённый репозиторий 

`git branch -M main`   - Меняем название текущей ветки (master) на main

`git push -u origin main`   - Пушим последний коммит в удалённый репозиторий

`git log`  - Показывает информацию о коммитах 

`git revert 8c12df05749f051d50dcbae7c82621d8ef4d6c0f`   - Откатывает до выбранного коммита (Через код коммита)
