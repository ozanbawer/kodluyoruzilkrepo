<<<<<<< HEAD
#Merge Sort Projesi- Proje 2

***
[16,21,11,8,12,22] -> Merge Sort > Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.

Big-O gösterimini yazınız.
***

##Merge Sort Aşamaları

```
1. Aşama --------- [16,21,11,8,12,22]

1. Aşama --------- [16,21,11] - [8,12,22]

3. Aşama --------- [16] - [21,11] - [8] - [12,22]

4. Aşama --------- [16] - [21] - [11] - [8] - [12] - [22]

5. Aşama --------- [16] - [11,22] - [8] - [12,22]

6. Aşama --------- [11,16,21] - [8,12,22]

7. Aşama --------- [8,11,12,16,21,22]

```

*İşlem 7 aşamada gerçekleşmektedir ve her aşamada n işlem yapılmaktadır ama her işlemde veriler 2ye bölünür buda 2^x kadar işlem gerektirir bütün işlem n.logn işlemle sonuçlanır. Bu sebeple Big-O gösterimi O(nlogn)'dir.*
=======
#Merge Sort Projesi- Proje 2

***
[16,21,11,8,12,22] -> Merge Sort > Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.

Big-O gösterimini yazınız.
***

##Merge Sort Aşamaları

```
1. Aşama --------- [16,21,11,8,12,22]

1. Aşama --------- [16,21,11] - [8,12,22]

3. Aşama --------- [16] - [21,11] - [8] - [12,22]

4. Aşama --------- [16] - [21] - [11] - [8] - [12] - [22]

5. Aşama --------- [16] - [11,22] - [8] - [12,22]

6. Aşama --------- [11,16,21] - [8,12,22]

7. Aşama --------- [8,11,12,16,21,22]

```

*İşlem 7 aşamada gerçekleşmektedir ve her aşamada n işlem yapılmaktadır ama her işlemde veriler 2ye bölünür buda 2^x kadar işlem gerektirir bütün işlem n.logn işlemle sonuçlanır. Bu sebeple Big-O gösterimi O(nlogn)'dir.*
>>>>>>> 01fd7e2b49ab1c193eedab32419b74ef3afc3996
