Proje Amacı
Bu proje, önceden tanımlanmış bir Int32 dizisi içindeki en küçük (min) ve en büyük (max) sayıları bulmak için UiPath kullanılarak hazırlanmıştır.

Kullanılan Aktiviteler
Assign – Diziyi ve min/max değerlerini başlatmak için.

For Each – Dizi içindeki her elemanı dolaşmak için.

If – Her elemanı karşılaştırarak minimum ve maksimum değerleri bulmak için.

Log Message – Sonuçları Output paneline yazdırmak için.

Adımlar
Diziyi Tanımlama:
numbers = New Integer() {7, 5, 2, 4, 3, 9}

Başlangıç Değerlerini Atama:
minValue = numbers(0)
maxValue = numbers(0)

For Each Döngüsü:
item değişkeni ile dizi elemanları üzerinde dolaşılır.

If aktiviteleri ile item değerleri minValue ve maxValue ile karşılaştırılır.

Sonuç:
Döngü tamamlandığında, minimum ve maksimum değerler Output paneline yazdırılır.
Örnek:
Minimum: 2, Maximum: 9
