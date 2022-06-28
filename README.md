# Patika-Insertion-Sort

## Proje 1


[22,27,16,2,18,6] -> Insertion Sort

 1. Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.

    * İlk önce bütün öbeği inceleriz ve en küçük olanı ilk sırada olan sayı ile yer değişir.
        * [2,27,16,22,18,6] -> 2 ile 22 yer değiştiriyor.
    * İkinci sıra için de 2'den sonra gelen en küçük sayıyı arar ve ikinci sırada olan sayı ile yer değişiriz.
        * [2,6,16,22,18,27] -> 6 ile 27 yer değiştiriyor.   
    * Aynı kuralı izleyrekten son sayıya kadar gelir.
        * [2,6,16,22,18,27] -> 3. sıradaki sayı diğerleri arasında en küçük olduğu için yer değiştirme olmaz.
        * [2,6,16,18,22,27] -> 18 ile 22 yer değiştiriyor.
        * [2,6,16,18,22,27] -> 5. sıradaki sayı en küçük olduğu için yer değiştirme olmaz.
        * [2,6,16,18,22,27] -> 6. sıradaki eleman en büyük olur ve öbeğimiz küçükten büyüğe sıralanmış olur.    
 2. Big-O gösterimini yazınız.
 3. Time Complexity: Average case: Aradığımız sayının ortada olması,Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması.
 4. Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.

 [7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.




