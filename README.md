# Veri Yapıları ve Algoritmalar Modülü Merge Sort Projesi 
This is a project for Patika.dev's Veri Yapıları ve Algoritmalar Module

### [16,21,11,8,12,22] -> Merge Sort

1.Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.

```
Merge sort için ilk olarak dizi ortadan ikiye bölünür.
İlk kısım için: 

1.adım = [16,21,11]  
2.adım = [16,21] / [11]  
3.adım = [16] / [21] / [11]  
4.adım = [16,21] / [11]  
5.adım = [11,16,21]

İkinci kısım için:

1.adım = [8,12,22]  
2.adım = [8,12] / [22]  
3.adım = [8] [12] / [22]  
4.adım = [8,12] / [22]  
5.adım = [8,12,22]

Son adım:

[8,11,12,16,21,22]
```

2.Big-O gösterimini yazınız.

```
O(nlogn)
```

