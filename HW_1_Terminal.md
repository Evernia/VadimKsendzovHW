1. Посмотреть где я. --- **pwd**<br>
![pwd](/img/pwd.png)<br>

2. Создать папку --- **mkdir folder_name**<br>
![mkdir_f1](/img/mkdir_f1.png)<br>

3. Зайти в папку --- **cd folder_name**<br>
![cd_f1](/img/cd_f1.png)<br>
4. Создать 3 папки --- **mkdir folder_name**<br>![mkdir_f2_f3_f4](/img/mkdir_f2_f3_f4.png)<br>
5. Зайти в любоую папку --- **cd folder_name**<br>![cd_f1_2](/img/cd_f1_2.png)<br>
6. Создать 5 файлов (3 txt, 2 json) --- **touch object_name**<br>![touch](/img/touch.png)<br>
7. Создать 3 папки --- **mkdir folder_name**<br>![mkdir_f2_f3_f4](/img/mkdir_f2_f3_f4.png)<br>
8. Вывести список содержимого папки --- **ls -la**<br>![ls_-la](/img/ls_-la.png)<br>
9. + Открыть любой txt файл --- **vim object_name**<br>![vim_t1](/img/vim_t1.png)<br>
10. + написать туда что-нибудь, любой текст. --- **i**<br>![i](/img/i.png)<br>
11. + сохранить и выйти. --- **esc :wq**<br>![escwq](/img/escwq.png)<br>
12. Выйти из папки на уровень выше --- **cd ..**<br>![cd_..](/img/cd_...png)<br>

---

13. переместить любые 2 файла, которые вы создали, в любую другую папку. --- **mv (что перемещать)object_name object_name (куда перемещать)folder_name**<br>![mv](/img/mv.png)<br>
14. скопировать любые 2 файла, которые вы создали, в любую другую папку. --- **cp (что копировать)object_name object_name (куда копировать)folder_name**<br>![cp](/img/cp.png)<br>
15. Найти файл по имени --- **find . object_name**<br>![find](/img/find.png)<br>
16. Просмотреть содержимое в реальном времени (команда grep) изучите как она работает. --- **tail -f object_name**<br>![tail](/img/tail.png)<br>
17. Вывести несколько первых строк из текстового файла --- **head -5 object_name**<br>![head](/img/head.png)<br>
18. Вывести несколько последних строк из текстового файла --- **tail -5 t1.txt**<br>![tail_-5](/img/tail_-5.png)<br>
19. Просмотреть содержимое длинного файла (команда less) изучите как она работает. --- **cat object_name или less object_name**<br>![cat](/img/cat.png)<br>
20. Вывести дату и время --- **date**<br>![date](/img/date.png)<br>

---

Задание *
1) Отправить http запрос на сервер. http://162.55.220.72:5005/terminal-hw-request--- **curl http://162.55.220.72:5005/terminal-hw-request**<br>![curl_1](/img/curl_1.png)<br>


1.1 **curl "http://162.55.220.72:5005/get_method?name=Lia&age=25"**<br>![curl_2](/img/curl_2.png)<br>

2) Написать скрипт который выполнит автоматически пункты 3, 4, 5, 6, 7, 8, 13<br> **Флаг исполняемости *chmod ugo+x script.sh*, далее запуск скрипта через графический интерфейс**<br>![vim_script](/img/vim_script.png)<br>
