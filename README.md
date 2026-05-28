# c4
Браузерный калькулятор

Сделал:
git reset --hard b8f269e7712c6a5a02ca4eba62c9924dbc228d9b
git push --force-with-lease origin master

Что сделано:

Локально снова выставлен коммит b8f269e (fix html file name) — перед push HEAD был на 11396ad.
На origin/master отправлен forced update: 11396ad → b8f269e.
Удалённая ветка master теперь совпадает с откатом: коммит «del 1 button» с удалённой кнопки «1» на GitHub больше не в истории master.

Важно: если кто-то уже клонировал репозиторий с 11396ad, им нужно выполнить:

git fetch origin
git reset --hard origin/master
