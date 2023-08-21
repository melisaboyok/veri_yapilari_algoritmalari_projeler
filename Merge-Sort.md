## CEVAP 1

```
[16,21,11,8,12,22]  Dizisinin Merge Sort Aşamaları:

[16, 21, 11, 8, 12, 22] - Başlangıç

[16, 21, 11], [8, 12, 22] - Diziyi ortadan ikiye böldük

[16], [21, 11], [8], [12, 22] - İki alt diziye de aynı işlemi uyguladık ve tekrar böldük

[16], [11, 21], [8], [12, 22] - Alt dizileri yeniden sıraladık

[11, 16, 21], [8, 12, 22] - Alt dizileri birleştirdik

Sonuç olarak ortaya çıkan dizimiz: [11, 16, 21, 8, 12, 22]

```

## CEVAP 2

Dizinin Big-O Gösterimi: O(n log n)