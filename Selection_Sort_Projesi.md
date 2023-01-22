# Selection_Sort_Projesi
Selection Sort Projesi
## [22,27,16,2,18,6] -> Insertion Sort

### A. Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.
  Dizinin en küçük sayısı bulunur, ilk sıradaki sayı ile yer değiştirilir. 2. sıraya geçilir ve işlem sağ tarafa doğru tekrarlanır. Süreç tüm sayılar sıralanana kadar devam eder. Sağında kendisinden küçük sayı bulunmayan sayılar yerinde kalır, işlem bir sonraki sayıya geçer.

1. [22,27,16,2,18,6]
2. [2,27,16,22,18,6]
3. [2,6,16,22,18,27]
4. [2,6,16,18,22,27]


### B. Big-O gösterimini yazınız.
  Big-O = n^2

### C. Time Complexity: Dizi sıralandıktan sonra 18 sayısı aşağıdaki case'lerden hangisinin kapsamına girer? Yazınız
Average case: Aradığımız sayının ortada olması
Worst case: Aradığımız sayının sonda olması
Best case: Aradığımız sayının dizinin en başında olması.

  [2,6,16,18,22,27] 
  Aradığımız sayının, sayı grubu içerisinde ortada bulunması sebebiyle average case olarak değerlendiririz.
  
 ### [7,3,5,8,2,9,4,15,6] dizisinin Selection Sort'a göre ilk 4 adımını yazınız.
 
 1. [2,3,5,8,7,9,4,15,6]
 2. [2,3,4,8,7,9,5,15,6]
 3. [2,3,4,5,7,9,8,15,6]
 4. [2,3,4,5,6,9,8,15,7]
