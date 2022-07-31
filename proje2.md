Proje 2.1 Merge sort
[16,21,11,8,12,22] -> Merge Sort

Adım 1: ortadan 2ye böldük
[16,21,11] [8,12,22]

Adım 2 : tekrar 2ye böldük
[16,21] [11] [8] [12,22]

Adım 3 : tek eleman kaldı, bölme işlemi bitti 
[16] [21] [11] [8] [12] [22]

Adım 4 : sıralı olarak birleştirmeye başlıyoruz
[16,21] [11] [8] [12,22]

Adım 5 : 
[11,16,21]  [8,12,22]

Adım 6:
[8,11,12,16,21,22] 
------------------------------------

Big-O gösterimini yazınız.
n=6
Best case    : O(n*logn)
Average case : O(n*logn)
Worst case   : O(n*(logn)) --> O(6*(log6))


