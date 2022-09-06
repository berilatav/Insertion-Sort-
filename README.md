| Verilen Dizi | 22 | 27 | 16 | 2 | 18 | 6 |       
| :---: | :---: | :---: | :---: | :---: | :---: | :---: |   

1. Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.



| 1. Adım | 2 | 27 | 16 | 22 | 18 | 6 |  
| :---: | :---: | :---: | :---: | :---: | :---: | :---: | 

İlk eleman(22) tüm diziyi gezerek en küçük eleman olan 2 ile yer değiştirir.

| 2. Adım | 2 | 6 | 16 | 22 | 18 | 27 |  
| :---: | :---: | :---: | :---: | :---: | :---: | :---: | 

İkinci eleman(27) sağ tarafındaki diziyi gezerek 2'den sonra gelen 6 ile yer değiştirir.

| 3. Adım | 2 | 6 | 16 | 22 | 18 | 27 |  
| :---: | :---: | :---: | :---: | :---: | :---: | :---: | 

Üçüncü adımda 16 dan küçük bir sayı olmadığı için sayı sabit kalır.

| 4. Adım | 2 | 6 | 16 | 18 | 22 | 27 |  
| :---: | :---: | :---: | :---: | :---: | :---: | :---: | 

Dördüncü adımda 22, 16'dan bir büyük olan eleman ile yer değiştirir.

2. Big-O gösterimini yazınız.

O(n^2)

3.Time Complexity :

- Worst case: Aradığımız sayının sonda olması,

Tam ters verilmiş dizi, bu durumda dizinin her bir elemanı bir gerisindekinden küçük olacaktır. Dolayısıyla 1.eleman için iç döngü 0,2. eleman için geriye doğru 1,3. eleman için iki daha sonra 3 4 5 6… n kadar geriye hareket yapacaktır. 
Yani 0+1+2+3+…+n-1 = [n*(n-1)]/2 = n^2

- Average case: Aradığımız sayının ortada olması,

Worst case ile best case'in ortalamasını aldığımızda n^2 olarak buluruz.

- Best case: Aradığımız sayının dizinin en başında olması.

Tam sıralı dizi, n tane sayinin üzerinden birer defa geçer ve hiç birini geriye doğru ilerletme gereği olmadığı için bu tek geçişle kalır. Yani n

4. Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.

Sayı dizinin ortasında olduğu için average case kapsamına girer.

5. [7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.

| Verilen Dizi | 7 | 3 | 5 | 8 | 2 | 9 | 4 | 15 | 6 |      
| :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |   

| 1. Adım | 2 | 3 | 5 | 8 | 7 | 9 | 4 | 15 | 6 |      
| :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |   

Birinci adımda ilk sayı olan 7, sağ tarafındaki sayıları tarar ve en küçük olan 2 ile yer değiştirir.

| 2. Adım | 2 | 3 | 5 | 8 | 7 | 9 | 4 | 15 | 6 |      
| :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |   

İkinci adımda bir sonraki eleman 3 göz önüne alınır. 2'den sonra geldiği için sabit kalır.

| 3. Adım | 2 | 3 | 4 | 8 | 7 | 9 | 5 | 15 | 6 |      
| :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |   

Üçüncü adımda 5 ile 4 4 yer değiştirir.

| 4. Adım | 2 | 3 | 4 | 5 | 7 | 9 | 8 | 15 | 6 |      
| :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |   

Dördüncü adımda 8 ele alınır ve 5 ile yer değiştirir.

| 5. Adım | 2 | 3 | 4 | 5 | 6 | 9 | 8 | 15 | 7 |      
| :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |   

Beşinci adımda 7 ele alınır ve 6 ile yer değiştirir.

| 6. Adım | 2 | 3 | 4 | 5 | 6 | 7 | 8 | 15 | 9 |      
| :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |   

Altıncı adımda 9 ele alınır ve 7 ile yer değiştirir.

| 7. Adım | 2 | 3 | 4 | 5 | 6 | 7 | 8 | 15 | 9 |      
| :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | 

Yedinci adımda 7'den sonra gelen sayı 8 olduğu için herhangi bir yer değişikliği yapılmaz. 

| 8. Adım | 2 | 3 | 4 | 5 | 6 | 7 | 8 | 9 | 15 |      
| :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | 

Sekizinci adımda 15 ele alınır ve 9 ile yer değiştirir.

