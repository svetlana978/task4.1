[К содержанию](./readme.md)

## git commit

**`git commit`** — переносит изменения всех файлов в репозиторий. При создании коммита (точки фиксации изменений) требуется указать сообщение.

Есть несколько ключей, упрощающих работу с `git commit`:
* `git commit -a` — совершит коммит, автоматически индексируя изменения в файлах проекта. Новые файлы при этом индексироваться не будут! Удаление же файлов будет учтено.
* `git commit -m "commit comment"` — комментирует коммит прямо из командной строки вместо текстового редактора.
* `git commit FILENAME` — внесет в индекс и создаст коммит на основе изменений единственного файла.


***
[Назад](./status.md "git status")  |  [Далее](./push.md "git push")