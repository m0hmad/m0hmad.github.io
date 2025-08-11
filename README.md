# m0hmad.github.io
| Команда | Описание |
|---------|----------|
| `git clone ssh://git@git-ssh.21-school.ru:2222/students_repo/lesliarn/T03D03.ID_239611-1.git` | Клонировать репозиторий по SSH |
| `cd ./<project>` | Перейти в директорию проекта |
| `git checkout -b develop` | Создать и переключиться на ветку develop |
| `cd ./src` | Перейти в директорию src |
| `cp ./<dir>/.clang-format ./` | Скопировать файл .clang-format |
| `cppcheck maxmin.c` | Проверить код с помощью cppcheck |
| `valgrind --tool=memcheck --leak-check=yes ./a.out` | Проверить утечки памяти с Valgrind |
| `gcc -o a.out maxmin.c -fsanitize=address` | Компиляция с проверкой адресов |
| `gcc -o a.out maxmin.c -fsanitize=leak` | Компиляция с проверкой утечек |
| `gcc -o a.out maxmin.c -fsanitize=undefined` | Компиляция с проверкой UB |
| `gcc -Wall -Werror -Wextra hello.c -lm` | Строгая компиляция с математической библиотекой |
| `clang-format -i maxmin.c` | Применить форматирование к файлу |
| `clang-format -n maxmin.c` | Проверить форматирование (без изменений) |
| `rm <obj files>` | Удалить объектные файлы |
| `git branch` | Показать ветки |
| `git add --all` | Добавить все изменения |
| `git commit -m "<comment>"` | Создать коммит |
| `git push` | Отправить изменения в репозиторий |
