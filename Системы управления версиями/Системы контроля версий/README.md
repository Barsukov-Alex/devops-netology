### Решение: 
#### Задание 1: Создать и настроить репозиторий для дальнейшей работы на курсе
- [x] Регистрация на сайте GitHub.com - выполнена. 
- [x] Создан репозиторий - DevOps-34: ссылка - https://github.com/li1s/DevOps-34
- [x] git config --global user.name Sergei.Lebedev 
- [x] git config --global user.email l1is@yahoo.com
- [x] git status
- [x] git diff  
- [x] git diff --staged
_____________________________________________________________

#### Задание 2: Создание файлов .gitignore и второго коммита
##### Создание файлов .gitignore и второго коммита
- [x] Создайте файл .gitignore
- [x] git status
- [x] Kаталог terraform и внутри этого каталога — файл .gitignore по примеру: https://github.com/github/gitignore/blob/master/Terraform.gitignore.


_____________________________________________________________________________
#### В файле README.md опишите своими словами, какие файлы будут проигнорированы в будущем благодаря добавленному .gitignore.

В файле .gitignore указаны паттерны для игнорирования файлов и директорий при работе с Git. В данном случае, следующие файлы и директории будут проигнорированы Git'ом:

    Все директории .terraform, включая поддиректории. (**/.terraform/*)
    Файлы с расширением .tfstate и .tfstate.*
    Файлы crash.log и crash.*.log
    Все файлы с расширением .tfvars и .tfvars.json
    Файлы override.tf, override.tf.json, *_override.tf и *_override.tf.json
    Конфигурационные файлы .terraformrc и terraform.rc

Таким образом, все эти файлы и директории не будут добавлены в репозиторий Git и не будут отслеживаться при выполнении команд Git, такие как git add или git commit. Это позволяет исключить из контроля версий файлы с конфиденциальной информацией или временные файлы, необходимые для работы Terraform.
_____________________________________________________________



    



### Результаты вывода команды git log: 


commit 57a69a5cea1a6025d9ff0439cc16dfaab3fe71f8 (HEAD -> main, origin/main, origin/HEAD)
Author: Alex Barsukov <mozdoksity@ya.ru>
Date:   Thu Jun 5 13:42:33 2025 +0300

    hw_1

commit eb73cba09a771fc0a1fddd7a1cf0b2e2c17d05b6
Author: Alex Barsukov <mozdoksity@ya.ru>
Date:   Thu Jun 5 13:40:28 2025 +0300

    hw_1

commit 9496d6514a738b15e350b7824d27ca6e550a9561
Author: Alex Barsukov <mozdoksity@ya.ru>
Date:   Thu Jun 5 13:38:46 2025 +0300

    hw_1

commit a1b18a098a876a09ee7d19fb4f8e743a34e40d4e
Author: Alex Barsukov <mozdoksity@ya.ru>
Date:   Thu Jun 5 13:24:16 2025 +0300

    dev

commit 9d2c4e5e43f05c963e0b2b017d75c570899a0bc3
Author: Alex Barsukov <mozdoksity@ya.ru>
Date:   Thu Jun 5 13:22:44 2025 +0300

    dsfdsfdsf

commit 4231e5f820249546ce5ee5345885413731852d19
Author: Alex Barsukov <mozdoksity@ya.ru>
Date:   Thu Jun 5 13:00:48 2025 +0300

    test

commit 2ca0e288733a4140ae1aa59369a09d4773a537c9
Author: Barsukov-Alex <mozdoksity@ya.ru>
Date:   Thu Jun 5 11:08:32 2025 +0300

    Initial commit