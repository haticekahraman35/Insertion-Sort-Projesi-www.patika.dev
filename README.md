# Insertion-Sort-Projesi-www.patika.dev
**www.patika.com > Veri Yapıları ve Algoritmalar > Insertion Sort Projesi kapsamında hazırlanmış proje çalışmasıdır.**
## INSERTION SORT PROJESİ
----------------------------
[22,27,16,2,18,6] -> Insertion Sort
----------------------------
### 1. Yukarıda verilen dizinin sort türüne göre aşamalarını yazınız.
- 1. Aşama => [2,|27,16,22,18,6]
- 2. Aşama => [2,6,|16,22,18,27]
- 3. Aşama => [2,6,16,|22,18,27]
- 4. Aşama => [2,6,16,18,|22,27]
- 5. Aşama => [2,6,16,18,22,|27]
----------------------------
### 2. Big-O gösterimini yazınız.
- n + (n-1) + (n-2) + ---- + 1 = (n.(n+1))/2 = n^2/2 + n/2 => Big-O Gösterimi = O(n^2)

----------------------------

### 3. Time Complexity: Average case: Aradığımız sayının ortada olması, Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması.
### Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.
- Dizinin sıralanmış hali => [2,6,16,|18|,22,27]
- Dizi sıralandıktan sonra 18 sayısı ortada yer aldığı için "Average Case" kapsamına girmektedir.

----------------------------

[7,3,5,8,2,9,4,15,6] -> Insertion Sort
----------------------------
### 1. Yukarıda verilen dizinin Insertion Sort'a göre ilk 4 adımını yazınız.
- 1. Aşama => [2,|3,5,8,7,9,4,15,6]
- 2. Aşama => [2,3,|5,8,7,9,4,15,6]
- 3. Aşama => [2,3,4,|8,7,9,5,15,6]
- 4. Aşama => [2,3,4,5,|7,9,8,15,6]
