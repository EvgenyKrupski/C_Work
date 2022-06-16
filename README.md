Итоговая контрольная работа
Выполнил : Крупский евгений Юрьевич
Для полценного выполнения проверочной работы необходимо:

    Создать репозиторий на GitHub
    Нарисовать блок-схему алгоритма (можно обойтись блок-схемой основной содержательной части, если вы выделяете ее в отдельный метод)
    Снабдить репозиторий оформленным текстовым описанием решения (файл README.md)
    Написать программу, решающую поставленную задачу
    Использовать контроль версий в работе над этим небольшим проектом (не должно быть так что все залито одним коммитом, как минимум этапы 2,3 и 4 должны быть расположены в разных коммитах)**

Задача:

Написать программу, которая из имеющегося массива строк формирует массив из строк, длина которых меньше либо равна 3 символа. Первоначальный массив можно ввести с клавиатуры, либо задать на старте выполнения алгоритма. При решении не рекомендуется пользоваться коллекциями, лучше обойтись исключительно массивами.
Примеры:

["hello", "2", "world", ":-)"] -> ["2", ":-)"] ["1234", "1567", "-2", "computer science"] -> ["-2"] ["Russia", "Denmark", "Kazan"] -> []
Решение задачи


    С помощью расширения DRAWIO создаем блок-схему алгоритма. Для этого скачиваем расширение DRAWIO и создаем файл с расширением .drawio.

    Создаем файл с описанием поставленной задачи README.md.

    Пишем программу решающую поставленную задачу.

    Используем контроль версий на каждом этапе изменнения кода программы с помощью следующих команд:

git add --all (добавляем все файлы сразу или вместо --all вписываем имя конкретного файла)
git commit -m "текст комментария".
git push (отправка изменений в удаленный репозитарий).
