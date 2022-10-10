## Merge Short Projesi
### Proje
[16,21,11,8,12,22] -> Merge Sort

- Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.
- Big-O gösterimini yazınız.
<hr/>

### Çözüm

+ [16,21,11,8,12,22] -> Merge Sort
> Tek eleman kalıncaya kadar dizi parçalanır.

![image](https://user-images.githubusercontent.com/9364520/194857612-d1ddb803-c620-4c69-8f8d-b471c50b2586.png)

> Parçalanan dizi elemanları karşılaştırılır ve sıralanarak birleştirilir.

![image](https://user-images.githubusercontent.com/9364520/194857854-50b4698d-346c-47b0-8dda-f52e1f11ecff.png)

<br/>

+ Big-O gösterimi

> O(n*(logn)) -> { n(eleman sayısı) = 6 } -> O(6*(log6)) olur.
