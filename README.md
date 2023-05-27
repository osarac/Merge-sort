[16,21,11,8,12,22]  Dizisinin Merge Sort Aşamaları:

[16, 21, 11, 8, 12, 22] - Başlangıç 

[16, 21, 11], [8, 12, 22] - Diziyi ortadan ikiye bölünür

[16], [21, 11], [8], [12, 22] - İki alt diziye de aynı işlemi uygulanır ve tekrar ikiye bölünür

[16], [11, 21], [8], [12, 22] - Alt dizileri yeniden sıralanır

[11, 16, 21], [8, 12, 22] - Alt dizileri birleştirilir

Sonuç olarak ortaya çıkan dizi: [11, 16, 21, 8, 12, 22] 


Dizinin Big-O Gösterimi: O(n log n)
