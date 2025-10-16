# Bilanço Tablosu ve Finansal Analiz Arayüzü

Bu proje, bir işletmenin finansal durumunu özetleyen temel bir muhasebe raporu olan **Bilançonun** oluşturulması, görüntülenmesi ve analizi için tasarlanmış bir kullanıcı arayüzüdür.

## Temel İşlevler

Uygulama, bir şirketin belirli bir tarihteki **Varlıklarını (Aktif)** ve bu varlıkların finansman kaynaklarını gösteren **Yükümlülükler (Pasif) ve Özkaynaklarını** listeler ve denetler.

### 1. AKTİF (Varlıklar)

İşletmenin sahip olduğu ekonomik değerleri listeler.

* **Dönen Varlıklar:** Bir yıl içinde nakde çevrilmesi beklenen kalemler (Nakit, Ticari Alacaklar, Stoklar vb.).
* **Duran Varlıklar:** Bir yıldan uzun süre işletmede kalacak varlıklar (Finansal Varlıklar, Tesisler, İştirakler vb.).

### 2. PASİF (Yükümlülükler ve Özkaynaklar)

İşletmenin varlıklarını finanse ettiği kaynakları listeler.

* **Kısa Vadeli Yükümlülükler:** Bir yıl içinde ödenmesi gereken borçlar (Ticari Borçlar, Kısa Vadeli Kredi vb.).
* **Uzun Vadeli Yükümlülükler:** Bir yıldan uzun vadede ödenecek borçlar.
* **Özkaynaklar:** İşletme sahiplerinin (ortakların) net hakkı (Sermaye, Kâr/Zarar, Yedekler).

## Kullanım Amacı

* **Finansal Durum Raporlama:** Belirli bir tarihte şirketin mali yapısını anlık olarak görme.
* **Bilanço Dengesi Kontrolü:** **Aktif Toplamı** ile **Pasif Toplamının** (Varlıklar = Kaynaklar) otomatik olarak karşılaştırılması ve dengenin sağlanması.
* **Veri Girişi ve Güncelleme:** Gerekli tüm hesap kalemlerine ait tutarların (görüntüdeki '0' yazan alanlar) girilmesini/güncellenmesini sağlar.

## Ek Özellikler

* **Tarih ve İşletme Bilgisi Girişi:** Raporun ait olduğu dönemi ve işletmeyi belirtme.
* **Dışa Aktarma/Kaydetme Fonksiyonları:** Verilerin **Excel**, **JSON** formatlarında dışa aktarılması ve sistemde kaydedilmesi (`Kaydet` butonları).
* **Doğrulama:** Bilanço ilkelerinin (denge dahil) kontrol edilmesi.

Bu uygulama, muhasebe süreçlerinde şeffaflığı ve finansal raporlamanın standartlara uygunluğunu sağlamayı amaçlar.
