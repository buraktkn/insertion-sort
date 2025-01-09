# Sorting Algorithms: Insertion Sort & Selection Sort

## Insertion Sort

### Problem
Dizi: **[22, 27, 16, 2, 18, 6]**

### Aşamalar
1. İlk eleman (22) sıralı kabul edilir.  
   **[22, 27, 16, 2, 18, 6]**

2. 27, 22’den büyük olduğu için yer değiştirme gerekmez.  
   **[22, 27, 16, 2, 18, 6]**

3. 16, 27'den küçük olduğu için 27 ile yer değiştirir. Daha sonra 16, 22’den de küçük olduğu için 22 ile de yer değiştirir.  
   **[16, 22, 27, 2, 18, 6]**

4. 2, sırasıyla 27, 22 ve 16’dan küçük olduğu için başa yerleşir.  
   **[2, 16, 22, 27, 18, 6]**

5. 18, 27’den küçük olduğu için yer değiştirir, 22’den de küçük olduğu için yer değiştirir. Ancak, 16’dan büyük olduğu için 16’nın yanına yerleşir.  
   **[2, 16, 18, 22, 27, 6]**

6. 6, sırasıyla 27, 22, 18 ve 16’dan küçük olduğu için başa doğru yerleşir.  
   **[2, 6, 16, 18, 22, 27]**

### Sonuç
Sıralı dizi: **[2, 6, 16, 18, 22, 27]**

---

### Big-O Gösterimi
- **Best Case:** O(n)  
- **Worst Case:** O(n²)  
- **Average Case:** O(n²)  

### Time Complexity
- 18 sayısı, sıralandıktan sonra **Average Case** kapsamına girer (ortada bir konumda).

---

## Selection Sort

### Problem
Dizi: **[7, 3, 5, 8, 2, 9, 4, 15, 6]**

### İlk 4 Adım
1. En küçük eleman (2) bulunur ve 7 ile yer değiştirilir.  
   **[2, 3, 5, 8, 7, 9, 4, 15, 6]**

2. Kalan dizi içinden (3, 5, 8, 7, 9, 4, 15, 6) en küçük eleman (3) zaten doğru yerde olduğu için değişiklik yapılmaz.  
   **[2, 3, 5, 8, 7, 9, 4, 15, 6]**

3. Kalan dizi içinden (5, 8, 7, 9, 4, 15, 6) en küçük eleman (4) bulunur ve 5 ile yer değiştirilir.  
   **[2, 3, 4, 8, 7, 9, 5, 15, 6]**

4. Kalan dizi içinden (8, 7, 9, 5, 15, 6) en küçük eleman (5) bulunur ve 8 ile yer değiştirilir.  
   **[2, 3, 4, 5, 7, 9, 8, 15, 6]**

### Sonuç
İlk 4 adımın ardından dizi: **[2, 3, 4, 5, 7, 9, 8, 15, 6]**

