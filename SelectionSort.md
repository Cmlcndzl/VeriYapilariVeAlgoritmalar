# PROJE 1

# [22,27,16,2,18,6] dizisinin Insertion Sort sıralama türüne göre aşamalarını yazınız.

1. Aşama => [22*,27,16,2,18,6] -> 22 sayısı dizinin en solunda olduğundan yer değiştirme olmaz.
2. Aşama => [22*,27,16,2,18,6] -> 27 sayısının 22 sayısına göre küçüklüğü kontrol edilir. Büyük olduğundan yer değiştirme olmaz.
3. Aşama => [16*,22,27,2,18,6] -> 16 sayısının solundaki sayılara göre küçüklüğü kontrol edilir. 22 ve 27 sayılarından küçük olduğundan 1. sıraya yerleştirilir.
4. Aşama => [2*,16,22,27,18,6] -> 2 sayısının solundaki sayılara göre küçüklüğü kontrol edilir. 16, 22 ve 27 sayılarından küçük olduğundan 1. sıraya yerleştirilir.
5. Aşama => [2,16,18*,22,27,6] -> 18 sayısının solundaki sayılara göre küçüklüğü kontrol edilir. 16' dan büyük ve 22' den küçük olduğundan 3. sıraya yerleştirilir.
6. Aşama => [2,6*,16,18,22,27] -> 6 sayısının solundaki sayılara göre küçüklüğü kontrol edilir. 2' den büyük ve 16' dan küçük olduğundan 2. sıraya yerleştirilir.

# Big-O gösterimini yazınız.

-> Big-O => O(n^2)

# Time Complexity: Dizi sıralandıktan sonra 18 sayısı aşağıdaki case'lerden hangisinin kapsamına girer? Yazınız

# 1. Average case: Aradığımız sayının ortada olması
# 2. Worst case: Aradığımız sayının sonda olması
# 3. Best case: Aradığımız sayının dizinin en başında olması.

-> 18 sayısı dizinin ortasında olduğundan Average Case kapsamına girer.

# [7,3,5,8,2,9,4,15,6] dizisinin Selection Sort'a göre ilk 4 adımını yazınız.

1. Adım => [2*,3,5,8,7,9,4,15,6] -> Dizinin en küçük elemanı olan 2 sayısıyla, dizinin birinci sırasındaki 7 sayısı yer değiştirir.
2. Adım => [2,3*,5,8,7,9,4,15,6] -> Dizinin en küçük ikinci elemanı olan 3 sayısı zaten dizinin ikinci sırasında olduğundan yer değiştirme olmaz.
3. Adım => [2,3,4*,8,7,9,5,15,6] -> Dizinin en küçük üçüncü elemanı olan 4 sayısıyla, dizinin üçüncü sırasındaki 5 sayısı yer değiştirir.
4. Adım => [2,3,4,5*,7,9,8,15,6] -> Dizinin en küçük dördüncü elemanı olan 5 sayısıyla, dizinin dördüncü sırasındaki 8 sayısı yer değiştirir.
