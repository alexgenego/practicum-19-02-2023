# Репозиторий для практикума
## Соответствие групп и тем на практикум.

1. Что такое система контроля версий
программная среда, обеспечивающая практику отслеживания и управления изменением программного кода.
2. Для чего нужна система контроля версий
хранение архивов программ, версий, откат, использование разных вариантов, проверку решений, поэтапное редактирование нового продукта, участие в командной работе с грамотным поэтпным совмещением кода.
3. Установка git на ваш ПК (в зависимости от системы)
Работа в среде Windows.
Установка Visual Studio Code. Установка git. Авторизация.Настройка интерфейса (русифицированный получился автоматически) Настройка автосохранения. Выбор места для создания учебных репозиториев.
4. Установка VSCode на ваш ПК
См. выше - был установлен ДО git.
5. Что такое репозиторий и инструкция по созданию локальных репозиториев.
хранилище файлов, поддерживающее версионность, команда git init после выбора папки, выполняющей функцию локального репозитория.
6. Базовая работа с локальным репозиторием
git add [file name] - отслеживание конкретного файла ГИТом.
git commit -m ‘action’ - что поменяли/добавили
git status - где работаем, состав файлов репозитория.
git log - список коммитов в данной ветке
7. Что такое ветки и для чего они нужны при работе с системой контроля версий.
варианты программы, где дописаны отдельные блоки кода, и опробована их эффективность независимо от уже готового кода финальной версии. Ветки могут создаваться независимо разными программистами, и по согласованию и проверке на конфликты сливаться с main.
8. Базовая работа с ветками в git.
git branch - имя ветви
git branch [branch_name] создание новой ветви
git checkout [branch_name] с ветки на ветку
git checkout -b [branch_name] с ветки на новую ветку
git branch -d [branch_name] удаление ветви
git merge [branch_name] - слияние основной (в которой сидим) с указанной [branch_name]
git log —graph - дерево коммитов в данной ветке
9. Что такое удаленный репозиторий и для чего он нужен
доступ и коллективная работа над кодом, доступен с разных машин, возможна работа с большими массивами данных.
10. Базовая работа с удаленными репозиториями GitHub
git push - отправить наш (локальный) репозиторий на удаленный.
git pull - выкачать все с удаленного на наш, и слить ветки в автоматическом режиме.
git clone - клонировать
После переноса репозитория убежаемся, что мы на основной ветке, и просматриваем историю файла. git log или git log —graph. Применяем стандартный набор команд для отслеживания, добавления и сравнения коммитов.
git remote add origin [https://адресок](https://адресок) 
git push -u origin main - отправляем с локального реп. на удаленный.
11. Как строится и для чего нужна совместная работа в системах контроля версий
12. Инструкция по созданию pull request
Делаем форк (fork) репозитория (не нашего).
Делаем git clone для нашей версии этого репозитория. git pull на локальный репозиторий.
Создаем новую ветку и редактируем ее. Сохранаяем-добавляем. Проверяем.
git push на свой аккаунт.
В окне на GitHub появляется кнопка pull request
13. Книги и полезные ссылки по изучению git.
Чакон, Штраубю Git для...
14. Альтернативные системы контроля версий.
