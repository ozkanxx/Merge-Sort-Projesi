# Merge-Sort-Projesi 

Proje 2
[16,21,11,8,12,22] -> Merge Sort

Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.
Big-O gösterimini yazınız.

## KAYNAK
[PATIKADEV](https://app.patika.dev/courses/veri-yapilari-ve-algoritmalar/merge-sort-proje)



-----------

# COZUM

* Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.
Merge Sort yontemi ile, parcalara ayirarak cozume ulasiyoruz. 

[16,21,11,8,12,22]

[16,21,11]  [8,12,22]

[16]   [21,11]  [8,12]   [22]

[16]   [21]  [11]  [8]  [12]   [22]

[16]   [11,21]  [8,12]   [22]

[11,16,21]  [8,12,22]

[8,11,12,16,21,22]

* Big-O gösterimini yazınız.

ikiye bölerek yaptıgımız bicin Big-O degerimiz s^x=n oldugundan,

O(logn)dir.


