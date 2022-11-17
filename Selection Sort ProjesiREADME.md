# Proje1 Selection Sort Projesi 
[Patika.dev](www.patika.dev) Eğitimi Proje-1

 Dizi1 = [22, 27, 16, 2, 18, 6]
 
 Dİzi 1 İnsertion Sort türüne göre aşamaları:

 1-) (22<27) ilk eleman olan 22 ile ikinci eleman olan 27 karşılaştırılır. 22, 27'deb küçük olduğu için aynı yerlerinde kalırlar.
 Dizi 1'in son şekli = [22, 27, 16, 2, 18, 6]

 2-) (16<22) üçüncü eleman olan 16 ile son durumdaki ilk eleman olan 22 karşılartırılır. 16, 22'den küçük olduğu için 16 birinci eleman olacak şekilde dizi tekrar sıralanır.
 Dizi1'nin son hali = [16, 22, 27, 2, 18, 6]

 3-) (2<16) dizinin dördüncü elemanı olan 2 ile son halindeki ilk elemanı karşılaştırılır. 2, 16'dan küçük lduğu için ilk sıraya yerleştirilir.
 Dizi 1'in son hali = [2, 16, 22, 27, 18, 6]

 4-) (18>2) beşinci eleman ilk eleman olan 2'den büyük pşduğu için ikinci eleman ile karşılaştırılır. 
 (18>16) ikinci elemanda 18'den küçük buyüzden üçüncü eleman ile karşılaştırılır.
 (18<22) 18, 22'den küçük olduğu için 18 üçüncü sıraya yerleşir.
 Dizi 1'in son hali = [2, 16, 18, 22, 27, 6]
 
 5-) (6>2) 6, 2'den büyük olduğu için ikinici eleman ile tekrar karşılaştırma yapılır.
 (6<16) 6, ikinci eleman olan 16'dan küçük olduğu için ikinci sıraya yerleştirilir.
 Dizi 1'in son hali = [2, 6, 16, 18, 22, 27]

 Big O şeklinde gösterimi = O(n^(2))

 18 sayısı Average Case kapsamına girer.

 #####################################################################

 Dİzi 2 = [7, 3, 5, 8, 2, 9, 4, 15, 6]
 
 Selection Sort türünün ilk 4 aşaması:

 1-)Bütün dizi elemanları arasında en küçük bulunur ve ilk eleman ile yerleri değiştirilir. 2 ve 7 yer değiştirir.
 Dizi 2'nin son hali = [2, 3, 5, 8, 7, 9, 4, 15, 6]

 2-)İlk eleman dışındaki diğer bütün elemanların arasındaki en küçük eleman bulunur ve iknici eleman ile yeri değiştirilir. 3 aralarındaki en küçük ve 2. sırada buyüzden dizi aynı burakılır.
 Dizi 2'nin son hali = [2, 3, 5, 8, 7, 9, 4, 15, 6]

 3-)3. eleman ve ondan sonraki bütün elemanların arasındaki en küçük eleman bulunur ve 3. eleman ile yeri değiştirilir. 4 ve 5 yer değiştirir.
 Dizi2'nin son hali = [2, 3, 4, 8, 7, 9, 5, 15, 6]

 4-)4. eleman ve ondan soraki elemanların arasındaki en küçük eleman ile 4. eleman yer değiştirir. 5 ve 8 yer değiştirir.
 Dizi 2'nin son hali = [2, 3, 5, 4, 7, 9, 8, 15, 6]

