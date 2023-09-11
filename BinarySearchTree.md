# PROJE 3

# [7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.

-> 5 sayisi Root olarak secilmistir.

1. Aşama => Dizinin ilk elemanindan baslayarak Root' tan buyuk ya da kucuk olmasina bakilir. 7 sayisi buyuk oldugundan saga yazilir.
2. Aşama => 1 sayisi Root' tan kucuk oldugundan soluna yazilir.
3. Aşama => 8 sayisi Root' tan buyuk oldugundan sagina yazilir. 7' den de buyuk oldugundan 7' nin sagina yazilir.
4. Aşama => 3 sayisi Root' tan kucuk oldugundan soluna yazilir. 1' den de buyuk oldugundan 1' in sagina yazilir.
5. Aşama => 6 sayisi Root' tan buyuk oldugundan sagina yazilir. 7' den de kucuk oldugundan 7' nin soluna yazilir.
6. Aşama => 0 sayisi Root' tan kucuk oldugundan soluna yazilir. 1' den de kucuk oldugundan 1' in soluna yazilir.
7. Aşama => 9 sayisi Root' tan buyuk oldugundan sagina yazilir. 8' den de buyuk oldugundan 8' in sagina yazilir.
8. Aşama => 4 sayisi Root' tan kucuk oldugundan soluna yazilir. 3' ten de buyuk oldugundan 3' ün sagina yazilir.
9. Aşama => 2 sayisi Root' tan kucuk oldugundan soluna yazilir. 3' ten de kucuk oldugundan 3' ün soluna yazilir.

          5
         / \
       1     7
      / \   / \
     0   3 6   8
        /   \   \
       2     4   9
     
