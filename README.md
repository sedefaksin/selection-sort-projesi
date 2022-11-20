# selection-sort-projesi
[22,27,16,2,18,6] -> Ekleme Sıralaması

Yukarı verilen dizin sıralama türüne göre aşamalarını yapılandırma
Cevap:

[22|27,16,2,18,6]
27>22 -----> [22,27,16,2,18,6]

[22,27|16,2,18,6]
16<27, 16<22 -----> [16,22,27,2,18,6]

[16,22,27|2,18,6]
2<27, 2<22, 2<16 -----> [2,16,22,27,18,6]

[2,16,22,27|18,6]
18<27, 18<22, 18>16 -----> [2,16,18,22,27,6]

[2,16,18,22,27|6]
6<27, 6<22, 6<18, 6<16 6>2 -----> [2,6,16,18,22,27]

[2,6,16,18,22,27]
Big-O gösterimini yapılandırmasını sağlar.
Cevap: O(n^2)

Seçim Sıralaması
[7,3,5,8,2,9,4,15,6] dizisinin Selection Sort'a göre ilk 4 adımını attı.

Cevap: [7,3,5,8,2,9,4,15,6]

adım [7|3,5,8,2,9,4,15,6] -------------> [2,3,5,8,7,9,4,15 ,6]

adım [2,3|5,8,7,9,4,15,6] -------------> [2,3,5,8,7,9,4,15 ,6]

adım [2,3,5|8,7,9,4,15,6] -------------> [2,3,4,8,7,9,5,15 ,6]

adım [2,3,4,8|7,9,5,15,6] -------------> [2,3,4,5,7,9,8,15 ,6]

oğul durum: [2,3,4,5,7,9,8,15,6]
