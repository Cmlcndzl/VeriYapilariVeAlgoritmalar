# PROJE 2

# [16,21,11,8,12,22] dizisinin Merge Sort sıralama türüne göre aşamalarını yazınız.

1. Aşama => [16,21,11] | [8,12,22] -> Dizi ortadan ikiye ayrılır.
2. Aşama => [16] | [21,11] | [8,12] | [22] -> İkiye ayrılan diziler tekrar ikiye bölünür.
3. Aşama => [16] | [21] | [11] | [8] | [12] | [22] -> Tekrardan ikiye ayrılarak dizinin elemanları tek bırakılır.
4. Aşama => [16] | [11,21] | [8,12] | [22] -> Elemanlar küçükten büyüğe olacak şekilde birleştirilir.
5. Aşama => [11,16,21] | [8,12,22] -> Elemanlar küçükten büyüğe olacak şekilde birleştirilir.
6. Aşama => [8,11,12,16,21,22] -> Elemanlar küçükten büyüğe olacak şekilde birleştirilir.

# Big-O gösterimini yazınız.

-> Big-O = O(nlogn)
