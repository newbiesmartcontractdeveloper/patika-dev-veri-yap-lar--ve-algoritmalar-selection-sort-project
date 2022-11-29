# patika-dev-veri-yapılar-ve-algoritmalar-selection-sort-project
www.patika.dev Veri Yapıları ve Algorimalar Selection Sort Projesi

## [22,27,16,2,18,6] -> Insertion Sort

- 1 aşama :2 en küçük sayı olduğu için en başa geçer. [2,27,16,22,18,6]
- 2 aşama :6, diğer en küçük sayı olduğu için 2'nin yanına geçer. [2,6,16,22,18,27]
- 3 aşama :18, 22den küçük olduğu için 16'nın yanına geçer. [2,6,16,18,22,27]
- : Diğer tüm rakamlar küçükten büyüğe göre sıralandığı için işlem bitmiştir.

Bu algoritmada n+(n-1)+(n-2)+(n-3)+(n-4)+....+1 kadar işlem yapılır. Toplam sembolü işleminin ardından (n²+n)/2 elde edilir.
Big-O Notation'da kat sayı önemsizdir; yani domine eden fonksiyon n² alınır.
- Big-O değeri = O(n²)

## Time Complexity: Dizi sıralandıktan sonra 18 sayısı aşağıdaki case'lerden hangisinin kapsamına girer? Yazınız

[2,6,16,18,22,27] olarak sonuçlandığı için ve "18" değeri ortada kaldığı için Average case'e girer.

## [7,3,5,8,2,9,4,15,6] dizisinin Selection Sort'a göre ilk 4 adımını yazınız.

- En küçük "2" olduğu için, 2 ve 7'nin yerini değiştireceğiz. [2,3,5,8,7,9,4,15,6]
- 3 diğer en küçük olduğu için olduğu yerde kalır, 4 rakamı 3 ve 5 arasına konulur. [2,3,4,5,8,7,9,15,6]
- 6 , 5 ve 8 arasına geçer. [2,3,4,5,6,8,7,9,15]
- 7, 6 ve 8 arasına geçer. [2,3,4,5,6,7,8,9,15]
