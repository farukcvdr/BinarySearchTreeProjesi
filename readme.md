# Binary Search Tree Projesi

## Problem

Proje 3
[7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.

Örnek: root x'dir. root'un sağından y bulunur. Solunda z bulunur vb.

## Çözüm

[7, 5, 1, 8, 3, 6, 0, 9, 4, 2]  Binary-Search-Tree aşamaları

1. İlk olarak dizimizin root kökünü belirlememiz lazım. Root kök olarak 3 belirliyorum
2. Dizimizdeki ilk rakamdan başlayarak root rakamımızdan büyük olanları soluna küçük olanları sağına ekliyoruz.
3. Her rakam için öncelikle root sayımızdan büyük mü ona bakıyoruz sola veya sağa ekliyoruz.
4. Root rakamından sonra gelen rakama bakıp büyükse sola küçükse sağa ekliyoruz

                     
                 3
            /        \
           1          7
          /  \       /  \
         0    2     5    8
                  /  \     \
                 4    6      9             
                    