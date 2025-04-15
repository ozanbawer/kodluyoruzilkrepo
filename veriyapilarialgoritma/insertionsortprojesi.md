#Insertion Sort Projesi - Proje 1

***
[22,27,16,2,18,6] -> Insertion Sort

Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.

Big-O gösterimini yazınız.

***

##Insertion Sort Aşamaları

```
1. Aşama --------- [22,27,16,2,18,6]

2. Aşama --------- [2,27,16,22,18,6]

3. Aşama --------- [2,6,16,22,18,27]

4. Aşama --------- [2,6,16,22,18,27]

5. Aşama --------- [2,6,16,18,22,27]

6. Aşama --------- [2,6,16,18,22,27]

*6 aşama olduğu için Big O gösterimi O(n)'dir*

```


***
Time Complexity: Dizi sıralandıktan sonra 18 sayısı aşağıdaki case'lerden hangisinin kapsamına girer? Yazınız

_Average case: Aradığımız sayının ortada olması_
_Worst case: Aradığımız sayının sonda olması_
_Best case: Aradığımız sayının dizinin en başında olması_
***

`18 sayısı dizi içinde ortada olduğu için Average case kapsamına girer`

***
[7,3,5,8,2,9,4,15,6] dizisinin Selection Sort'a göre ilk 4 adımını yazınız.
***

```
1. Aşama --------- [7,3,5,8,2,9,4,15,6]

2. Aşama --------- [2,3,5,8,7,9,4,15,6]

3. Aşama --------- [2,3,5,8,7,9,4,15,6] 

4. Aşama --------- [2,3,4,8,7,9,5,15,6]

--diğer aşamalar

5. Aşama --------- [2,3,4,5,7,9,8,15,6]

6. Aşama --------- [2,3,4,5,6,9,8,15,7]

7. Aşama --------- [2,3,4,5,6,7,8,15,9]

8. Aşama --------- [2,3,4,5,6,7,8,15,9]

8. Aşama --------- [2,3,4,5,6,7,8,9,15]

```

