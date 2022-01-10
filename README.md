# Insertion-Sort-Projesi
[22,27,16,2,18,6] -> Insertion Sort

Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.
Big-O gösterimini yazınız.
Time Complexity: Average case: Aradığımız sayının ortada olması,Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması.
Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.

1- [22,27,16,2,18,6] ilk birim (22) ikinci ücüncü son birime kadar küçük elemanı arar, bulduğu en küçük birim 2 ile yer değiştirir. n sayıda işlem yapıldı.
2- [2,27,16,22,18,6] ikinci birim (27) n-1 kadar karşılaştırma yapar, gördüğü en küçük birim ile (6) yer değiştirir.
3- [2,6,16,22,18,27] üçüncü birim (16) n-2 kadar karşılaştırma yapar, kendisi en küçük olduğu için aynı kalır.
4- [2,6,16,22,18,27] dördüncü birim (22) n-3 kadar karşılaştırma yapar, gördüğü en küçük birim ile (18) yer değiştirir.
5- [2,6,16,18,22,27] beşinci birim (22) n-4  kadar karşılaştırma yapar, gördüğü en küçük birim kendisi olduğu için sorting biter.

Big O(n2)

Dizi sıranlanınca [2,6,16,18,22,27] 18 dördüncü sırada olduğu için , en yakın ortada olduğundan average case olarak değerlendirilir.




[7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.
1- [2,3,5,8,7,9,4,15,6] 
2- [2,3,5,8,7,9,4,15,6]  değişmedi; 2. en küçük değer zaten 2. sırada
3- [2,3,4,8,7,9,5,15,6] 
3- [2,3,4,5,7,9,8,15,6] 