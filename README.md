> # Metin İşleme ve Dil Tespiti Aracı

Bu proje, metin üzerinde dil tespiti, stopword (önemsiz kelime) temizliği ve en sık kullanılan kelimeleri bulma işlemlerini gerçekleştiren bir  
Python uygulamasıdır. Bir metin dosyasını giriş olarak alır, dilini algılar, stopword'leri temizler ve en sık kullanılan kelimeleri analiz ederek çıktı olarak sunar.

## Özellikler
+ Dil Tespiti: Metnin dilini otomatik olarak algılar.
+ Stopword Temizliği: Tespit edilen dile uygun olarak önemsiz kelimeleri metinden çıkarır.
+ Kelime Sıklığı Analizi: Metindeki en sık kullanılan 10 kelimeyi listeler.

## Gereksinimler
Projenin çalıştırılması için yandaki Python kütüphanelerine ihtiyaç vardır:
`pandas`, `numpy`, `langdetect`

Gerekli kütüphaneleri yüklemek için: `pip install pandas numpy langdetect`

## Kullanım
Metin dosyanızı `article-sample.txt` adıyla proje klasörüne ekleyin.
