# Binary Search Tree Projesi

## Patika Dev - Veri Yapıları ve Algoritmalar - Proje 3

[7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.

## Cevap

Dizi: [7, 5, 1, 8, 3, 6, 0, 9, 4, 2]

### Binary Search Tree Aşamaları

1. İlk eleman 7 olduğu için root 7'dir.
2. 5: 7'den küçük olduğu için root'un (7'nin) soluna eklenir.
3. 1: 7'den ve 5'ten küçük olduğu için 5'in soluna eklenir.
4. 8: 7'den büyük olduğu için root'un (7'nin) sağına eklenir.
5. 3: 7'den ve 5'ten küçük, ancak 1'den büyük olduğu için 1'in sağına eklenir.
6. 6: 7'den küçük ama 5'ten büyük olduğu için 5'in sağına eklenir.
7. 0: 7'den, 5'ten ve 1'den küçük olduğu için 1'in soluna eklenir.
8. 9: 7'den ve 8'den büyük olduğu için 8'in sağına eklenir.
9. 4: 7'den ve 5'ten küçük, ancak 1'den ve 3'ten büyük olduğu için 3'ün sağına eklenir.
10. 2: 7'den ve 5'ten küçük, ancak 1'den büyük ve 3'ten küçük olduğu için 3'ün soluna eklenir.

![binary_search_tree ](https://github.com/user-attachments/assets/753c6f6c-b529-42c4-b528-63c1b1e9ffff)
