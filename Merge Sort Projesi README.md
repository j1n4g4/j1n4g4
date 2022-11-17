#Proje2 Merge Sort Projesi 
[Patika.dev](www.patika.dev) Eğitimi Projesi-2

Dizi 1 = [16, 21, 11, 8, 12, 22]

Dizi 1 Merge Sort türüne göre sıralama aşamaları:

1-)Dizi1 ikiye bölünür. [16, 21, 11] , [8, 12, 22]

2-)İkiye bölünen parçalarda tekrar ikiye bölünür. [16] , [21, 11] , [8, 12] , [22]

3-)İkili ve tekli gruplar kendi içlerinde sıralanır. [16] , [11, 21] , [8, 12] , [22]

4-)Birleştirme aşamlarına geçiş yapılır. İki grup birşleştirilirken en baştaki sayılara bakılır en küçük olanı başa yazılır daha sonrasında ise 2. sıra ile diğer dizinin 1. sırası tekrar karşılaştırılır. bu ta ki en son elemana gelene kadar yapılır.
[11, 16, 21] , [8, 12, 22]

5-) 4.aşama son kalan iki grup için de tekrarlanır [8, 11, 12, 16, 21, 22]

Big O gösterimi = O(nlogn) 
