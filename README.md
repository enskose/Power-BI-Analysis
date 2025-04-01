# Satış Analiz Raporu
## Genel Bakış
Bu repository, Power BI kullanılarak hazırlanmış kapsamlı bir satış analiz raporunu içermektedir. Rapor, perakende sektöründeki satış performansını inceleyerek, trendler, ürün bazlı satış dağılımları ve bölgesel performans gibi konularda önemli içgörüler sunmaktadır.

## İçerik
Rapor Dosyası: satis_dashboard.pbix (Power BI Desktop dosyası)

Dokümantasyon: Bu README dosyası ve ek dokümanlar

Örnek Görselleştirmeler: Rapor içerisindeki grafikler, tablolar ve dashboard’lar

## Analizin Amacı
Amaç: Perakende satış verileri üzerinden performans değerlendirmesi yapmak, en çok satılan ürünleri ve en verimli satış kanallarını belirlemek.

Kapsam: Analiz, 2023 yılının ilk üç çeyreğine ait satış verileri temel alınarak gerçekleştirilmiştir. Ayrıca, farklı mağaza lokasyonları arasındaki performans farkları incelenmiştir.

# Veri Kaynakları ve Hazırlık
## Veri Kaynakları:

Satış verileri, CSV formatında sağlanan günlük raporlardan temin edilmiştir.

Müşteri ve ürün bilgileri, SQL veritabanından çekilmiştir.

## Veri Temizleme & Dönüşüm:

Power Query kullanılarak veriler temizlenmiş, eksik veriler tamamlanmış ve gereksiz sütunlar elenmiştir.

Tarih formatları standartlaştırılmış, ürün kategorileri belirli gruplara ayrılmıştır.

## Modelleme:

İlişkisel veri modeli oluşturularak, satış verileri ile müşteri ve ürün bilgileri arasında bağlantılar kurulmuştur.

DAX formülleri ile toplam satış, ortalama sipariş değeri ve bölgesel performans gibi metrikler hesaplanmıştır.

# Raporun Özellikleri
## Ana Metriğe Odaklanma:

Toplam satış tutarı, satış adetleri, ve kar marjı gibi temel metrikler.

## Dinamik Dashboard:

Kullanıcıların filtre ve dilimleyiciler aracılığıyla, tarih aralığı, mağaza lokasyonu ve ürün kategorisi bazında detaylı segmentasyon yapabilmelerine olanak tanır.

## Görselleştirmeler:

Çubuk grafikler: Ürün bazında satış dağılımı.

Çizgi grafikler: Zaman içerisindeki satış trendleri.

Haritalar: Bölgesel satış performansının görselleştirilmesi.

KPI göstergeleri: Hedeflere ulaşım durumu.

# Kullanım ve İnteraktivite
## Power BI Desktop ile Açma:

satis_dashboard.pbix dosyasını Power BI Desktop üzerinden açın.

## Filtreleme ve İnceleme:

Dashboard üzerindeki filtreler sayesinde tarih, lokasyon ve ürün kategorilerine göre detaylı analiz yapabilirsiniz.

## Raporun Yayınlanması:

Raporu Power BI Service’e yükleyerek ekip içinde paylaşabilir, interaktif rapor erişimi sağlayabilirsiniz.

# Geliştirme ve Katkı
## Geri Bildirim:

Rapor ve analizle ilgili öneri veya sorularınızı issue tracker üzerinden paylaşabilirsiniz.

## Katkıda Bulunma:

Repository’i fork’layın.

Değişikliklerinizi oluşturun.

Pull request gönderin.

## Gelecek Planlar:

Veri kaynaklarının güncellenmesi.

Ek metriklerin analizi ve yeni görselleştirme tiplerinin eklenmesi.

Kullanıcı geri bildirimlerine göre rapor üzerinde iyileştirmeler yapılması.

# Ek Belgeler
## Kullanım Kılavuzu:

Raporun detaylı kullanım yönergelerini içeren PDF dokümanı (yakında eklenecektir).

## Sunum ve Raporlar:

Yönetim raporları ve sunum slaytları, ek dosyalar halinde sağlanacaktır.

# Lisans
Bu repository, MIT Lisansı kapsamında yayınlanmıştır. Daha fazla bilgi için LICENSE dosyasını inceleyebilirsiniz.
