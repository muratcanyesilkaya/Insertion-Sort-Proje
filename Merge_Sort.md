# Bu dosya Merge Sort Projesi'ni içeriyor.

## Proje 2
### [16,21,11,8,12,22] -> Merge Sort

 1) Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.
 2) Big-O gösterimini yazınız

 **cevap 1** 
- [16,21,11]  ,  [8,12,22] 
- [16,21],[11] , [8,12], [22] 
- [16],[21],[11] , [8],[12],[22]
- [16,21],[11] , [8,12], [22] 
- [11,16,21], [8,12,22]
- [8,11,12,16,21,22]

**cevap 2**

- O(nlogn)