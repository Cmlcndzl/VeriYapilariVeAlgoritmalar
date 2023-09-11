# PROJE 3

# [7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.

-> 5 sayısı Root olarak seçilmiştir.

1. Aşama => Dizinin ilk elemanından başlayarak Root' tan büyük ya da küçük olmasına bakılır. 7 sayısı büyük olduğundan sağa yazılır.
2. Aşama => 1 sayısı Root' tan küçük olduğundan soluna yazılır.
3. Aşama => 8 sayısı Root' tan büyük olduğundan sağına yazılır. 7' den de büyük olduğundan 7' nin sağına yazılır.
4. Aşama => 3 sayısı Root' tan küçük olduğundan soluna yazılır. 1' den de büyük olduğundan 1' in sağına yazılır.
5. Aşama => 6 sayısı Root' tan büyük olduğundan sağına yazılır. 7' den de küçük olduğundan 7' nin soluna yazılır.
6. Aşama => 0 sayısı Root' tan küçük olduğundan soluna yazılır. 1' den de küçük olduğundan 1' in soluna yazılır.
7. Aşama => 9 sayısı Root' tan büyük olduğundan sağına yazılır. 8' den de büyük olduğundan 8' in sağına yazılır.
8. Aşama => 4 sayısı Root' tan küçük olduğundan soluna yazılır. 3' ten de büyük olduğundan 3' ün sağına yazılır.
9. Aşama => 2 sayısı Root' tan küçük olduğundan soluna yazılır. 3' ten de küçük olduğundan 3' ün soluna yazılır.

          5
         / \
       1     7
      / \   / \
     0   3 6   8
        /   \   \
       2     4   9
     
