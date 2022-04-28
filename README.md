# PatikaBinaryTree
## Veri Yapıları ve Algoritmalar - 3

1. [7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.

- Örnek: root x'dir. root'un sağından y bulunur. Solunda z bulunur vb.

# Solution
1.  Root 6'dır. Root sağında 7,8,9 bulunur. Root solunda 0,1,2,3,4,5 bulunur. Biz bu aşamada bir ağaç oluşturmuş oluyoruz ve ekleyeceğimiz bir elemanı root'a göre değerlendiriyoruz. Root'tan büyükse değerlendirme sağ tarafta küçükse sol tarafta gerçekleşerek girecek olan yeni elemanın yeri belirleniyor.