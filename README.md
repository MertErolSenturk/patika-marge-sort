# Merge Sort Aşamaları ve Big-O Analizi

### Verilen Dizi
[16,21,11,8,12,22]

### Merge Sort Aşamaları

1. Diziyi ikiye böl:
   16,21,11    8,12,22

2. Alt dizileri tekrar böl:
   [16] [21,11] [8] [12,22]

3. Tek elemanlı diziler elde edilene kadar bölmeye devam et:
   [16] [21] [11] [8] [12] [22]

4. İkili grupları sıralayarak birleştir:
   [16] [11,21] [8] [12,22]

5. Dörder elemanlı grupları sıralayarak birleştir:
   11,16,21    8,12,22

6. Son birleştirme ile sıralı diziyi elde et:
   8,11,12,16,21,22

### Big-O Gösterimi

Merge Sort'un zaman karmaşıklığı: O(n log n)

#### Açıklama:
- Dizi sürekli ikiye bölündüğü için log n seviyesi oluşur.
- Her seviyede n eleman üzerinde işlem yapılır (birleştirme işlemi).
- Bu nedenle toplam karmaşıklık n * log n = O(n log n) olur.

