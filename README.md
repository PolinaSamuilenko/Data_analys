# Data_analys
Описание и файлы к курсовой работе по предмету "Анализ данных в строительстве", выполнила студентка гр.3140801/30602 Самуйленко П.А.  
Снятие показателей модели.  
В качестве первой модели было выбрано одноэтажное жилое здание (файл ifc. был взят из интернета). При помощи П.О. Speckle и Power BI из файла  с расширением ifc. были cняты метрики и переведены в формат сsv., для дальнейшего статистического анализа. В частности, получена информация по стенам, окнам, крыше и полу, фурнитуре, дверям. Для каждой группы из модели получены такие метрические данные как:(heigth), ширина (width), рабочая площадь(net.area), расстояние от пола (SillHeight).	
Общая площадь здания - 214.7 м2.	
![image](https://github.com/PolinaSamuilenko/Data_analys/assets/158211553/3b858ecf-e6a0-40ef-b2b9-ec76befd556d)

# Окна
Всего 19 окон, по размеру делятся на 3 неравные группы: 1 окно размером 580*1180 расположенное в техническом помещении, 5 больших окон в пол 2180*2180, 13 окон 1010*1010. В данных по окнам удалось найти параметр .RoughWidth (приблизительная ширина), однако он присутствует только у окон в пол и у окна технического помещения. Т.о. у 68 процентов данных этого показателя нет. По графикам видно что есть четкое разделение данных на 3 группы. 
<img width="492" alt="image" src="https://github.com/PolinaSamuilenko/Data_analys/assets/158211553/2e0d0e02-524a-4198-be10-a5300bd9d465">

<img width="1039" alt="image" src="https://github.com/PolinaSamuilenko/Data_analys/assets/158211553/57caac39-660a-483c-9cff-3f0ac6788215">

# Двери
Всего 8 дверей, 2 из них входные и отличаются от межкомнатных по ширине(1010 вместо 910), интересно что при увеличении ширины рабочая площадь у входных дверей меньше. По высоте двери не различаются между собой.
<img width="920" alt="image" src="https://github.com/PolinaSamuilenko/Data_analys/assets/158211553/b26c2e61-a28d-4545-b20a-64b92581134f">
<img width="1043" alt="image" src="https://github.com/PolinaSamuilenko/Data_analys/assets/158211553/8c2edb2e-6046-4305-af99-ce83bc9794ae">


# Стены
Всего 13 стен, из них 4 внешние, больше по ширине (540 вместо 170),делятся на 2 группы по длине ( 22060 и 8960),9 внутренних стен шириной 170. По высоте стены одинаковые, различаются по длине, причем только 2 внутренние стены имеют одинаковую длину. 
![image](https://github.com/PolinaSamuilenko/Data_analys/assets/158211553/e8d4d485-a15f-4ba2-b2d8-787d2d75832f)
<img width="831" alt="image" src="https://github.com/PolinaSamuilenko/Data_analys/assets/158211553/e6a000bf-f008-4a76-ac56-c2a9c73e777f">

# Фурнитура 
Предметов мебели 71 шт.Все они  
![image](https://github.com/PolinaSamuilenko/Data_analys/assets/158211553/e43f59aa-e3d5-4910-9353-6cbde3146f49)
![image](https://github.com/PolinaSamuilenko/Data_analys/assets/158211553/c5cbb076-4785-415b-892a-85520a9e28c6)

<img width="1315" alt="image" src="https://github.com/PolinaSamuilenko/Data_analys/assets/158211553/0187854f-706f-43db-9947-716faeaeed61">


# Пол и крыша 
214,7 рабочая площадь пола и 2 одинаковых по рабочей площади (262,4) части кровли.
![image](https://github.com/PolinaSamuilenko/Data_analys/assets/158211553/a2a215dc-ee49-4854-b166-7b9ad26e13fd)
<img width="1043" alt="image" src="https://github.com/PolinaSamuilenko/Data_analys/assets/158211553/d3469a9d-30f8-452c-886f-065de16d1c1f">

