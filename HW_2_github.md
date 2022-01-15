# GitHub. HW_2
--- 
[Ссылка на репозиторий](https://github.com/Evernia/branches)

1. На локальном репозитории сделать ветки для: --- **git branch branch_name** или для создание ветки и сразу перехода на неё **git checkout -b branch_name**<br>
- postman<br>
- jmeter<br>
- checkList<br>
- bag_reports<br>
- SQL<br>
- charles<br>
- mobile_testing<br>
![1](/imgHW2github/1.png)<br>

2. Запушить все ветки на внешний репозиторий --- **git push -u origin название_ветки**<br> ![2](/imgHW2github/2.png)<br>
3. В ветке bag_reports сделать текстовый документ со структурой баг репорта --- **git checkout bag_reports** <br>
4. Запушить структуру багрепорта на внешний репозиторий <br> ![](/imgHW2github/.png) ![](/imgHW2github/.png) ![](/imgHW2github/.png)
    + git checkout bag_reports <br> ![3](/imgHW2github/3.png) 
    + touch bag_reports.txt <br> ![3_1](/imgHW2github/3_1.png)
    + vim bag_reports.txt <br> ![3_2](/imgHW2github/3_2.png)
    + git add bag_reports.txt <br> ![3_3](/imgHW2github/3_3.png)
    + git commit -m "add bag_reports.txt" <br> ![3_4](/imgHW2github/3_4.png)
    + git push <br> ![3_5](/imgHW2github/3_5.png)
    
5. Вмержить ветку bag_reports в main<br>
    + git checkout main <br> ![5](/imgHW2github/5.png)
    + git merge bag_reports <br>![5_1](/imgHW2github/5_1.png)
    
6. Запушить main на внешний репозиторий. --- **git push** <br> ![6](/imgHW2github/6.png)<br>
7. В ветке checkList набросать структуру чек листа. <br>
    + git checkout checkList <br> ![7](/imgHW2github/7.png)
    + touch checkList.txt ![7_1](/imgHW2github/7_1.png)
    + vim checkList.txt ![7_2](/imgHW2github/7_2.png)

8. Запушить структуру на внешний репозиторий<br>
    + git add . <br> ![8](/imgHW2github/8.png)
    + git commit -m "add checkList.txt" <br> ![8_1](/imgHW2github/8_1.png)
    + git push <br> ![8_2](/imgHW2github/8_2.png)
    
9. На внешнем репозитории сделать Pull Request ветки checkList в main<br> ![9](/imgHW2github/9.png)<br>
10. Синхронизировать Внешнюю и Локальную ветки main<br> ![10](/imgHW2github/10.png)<br>

### Спасибо за внимание!
![1](/imgHW2github/1.jpg)
