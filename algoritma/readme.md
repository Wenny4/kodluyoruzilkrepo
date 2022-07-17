# VERİ YAPILARI VE ALGORİTMALARI

[Patika.dev](https://patika.dev)'in Veri Yapıları ve Algoritmaları dersinin bitirme projelerini kapsamaktadır.

# Insertion Sort Projesi

[22,27,16,2,18,6] -> Insertion Sort

## Soru 1. Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.

```
[22,27,16,2,18,6]
[2,27,16,22,18,6]
[2,6,16,22,18,27]
[2,6,16,18,22,27]
```

## Soru 1. Big-O gösterimini yazınız.

```
Best case: [2,6,16,18,22,27]
Worst case: [27,22,18,16,6,2]
```

## Time Complexity

```
Best case: O=(n)
Average case: O=(n^2)
Worst case: O=(n^2)
```

## Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer?

```
[2,6,16,18,22,27]

18 sayısı avarage case olarak ele alınabilir.
```

## [7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.

```
[7,3,5,8,2,9,4,15,6]
[2,3,5,8,7,9,4,15,6]
[2,3,4,8,7,9,5,15,6]
[2,3,4,5,7,9,8,15,6]
[2,3,4,5,6,9,8,15,7]
[2,3,4,5,6,7,8,15,9]
[2,3,4,5,6,7,8,9,15]
```

# Merge Sort Projesi

[16,21,11,8,12,22] -> Merge Sort

## Soru 1. Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.

```
[16,21,11,8,12,22]
[16,21,11] - [8,12,22]
[16,21][11] - [8,12][22]
[16][21][11] - [8][12][22]
[16,21][11] - [8,12][22]
[8,11,12,16,21,22]
```