# 1.Proje Sorusu
## Proje 1
[22,27,16,2,18,6] -> Insertion Sort

1-Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.\
2-Big-O gösterimini yazınız.\
3-Time Complexity: Average case: Aradığımız sayının ortada olması,Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması.\
4-Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.


[7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.
---
#                   Çözüm
#           *** İnsertion Sort ***
##           **[22,27,16,2,18,6]** Dizisinin insertion sort türüne göre aşamaları 
---
```
1.Aşama  [2,27,26,22,18,6] 
2.Aşama  [2,6,26,22,18,27]
3.Aşama  [2,6,18,22,26,27]
```
---
## Big-O Gösterimi
  >`    n(n+1)/2  O(n^2) `

  ---

  ## Time Complexity

* Average Case: Aradigimiz sayinin ortada olma durumu
* Worst Case:   Aradigimiz sayinin sonda olma durumu
* Best Case:    Aradigimiz sayinin en basta olma durumu
---
> 18 sayısı Average Case kapsamına girer.
---

## [7,3,5,8,2,9,4,15,6]
```
1.Adım  [2,3,5,8,7,9,4,15,6] 
2.Adım  [2,3,4,8,7,9,5,15,6]
3.Adım  [2,3,4,5,7,9,8,15,6]
4.Adım  [2,3,4,5,6,9,8,15,7]



