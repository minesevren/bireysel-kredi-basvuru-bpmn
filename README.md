# Bireysel Kredi Başvuru Süreci Analizi

Bu proje, bireysel kredi başvuru sürecinin iş analizi kapsamında incelenmesi ve BPMN 2.0 standardında modellenmesi amacıyla hazırlanmıştır.

## Proje Amacı

Bireysel kredi başvurusunun alınması, değerlendirilmesi ve sonuçlandırılması sürecindeki iş akışlarının modellenmesi ve süreç içerisinde oluşabilecek manuel işlem, gecikme ve iletişim noktalarının belirlenmesi amaçlanmıştır.

## Kullanılan Araçlar

- Camunda Modeler
- BPMN 2.0

## Süreç Paydaşları

- Müşteri
- Mobil Uygulama
- Banka Yetkilisi
- Kredi Değerlendirme Sistemi
- Onay Birimi

## Modellenen Süreç

BPMN modeli kapsamında aşağıdaki süreç adımları ele alınmıştır:

- Kredi başvurusunun oluşturulması
- Bilgi ve belgelerin girilmesi
- Başvurunun sisteme iletilmesi
- Bilgi ve belge kontrolü
- Kredi skoru hesaplama
- Risk değerlendirmesi
- Kredi kararının verilmesi
- Sözleşme süreci
- Kredi kullandırımının başlatılması
- Başvuru sonucunun müşteriye bildirilmesi

## Karar Noktaları

Süreç içerisinde BPMN Exclusive Gateway kullanılarak iki temel karar noktası modellenmiştir:

1. Bilgi veya belge eksik mi?
2. Kredi başvurusu onaylandı mı?

## Süreç Problemleri

Mevcut süreç analizi kapsamında aşağıdaki potansiyel problemler ele alınmıştır:

- Eksik bilgi veya belgeler nedeniyle oluşabilecek gecikmeler
- Manuel kontrol işlemlerinden kaynaklanabilecek zaman kaybı
- Birimler arasında oluşabilecek iletişim gecikmeleri
- Müşterinin süreç hakkında yeterli bilgi alamaması

## Proje Çıktısı

Bireysel kredi başvuru sürecinin BPMN 2.0 standardında hazırlanmış As-Is süreç modeli.
