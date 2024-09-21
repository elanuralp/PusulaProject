# DATA ANALYSIS
## Datayı Anlama
* Dataseti incelediğimde veriseti içerisinde total 19 sütün olduğunu ve toplamda 2357 veri olduğunu gördüm.
* Bunlar çoğunlukla kullanıcı ile ilgili detaylar , ilaçlar ve yan etkilerini içeriyor.
* Belli başlı sütunlar:
    * User Information : Kullanici_id, Cinsiyet, Dogum_Tarihi, Uyruk, Il
    * Medication: Ilac_Adi, Ilac_Baslangic_Tarihi, Ilac_Bitis_Tarihi
    * Side Effects: Yan_Etki, Yan_Etki_Bildirim_Tarihi
    * Health Info: Alerjilerim, Kronik Hastaliklarim, Baba Kronik Hastaliklari, Anne Kronik Hastaliklari, etc.
    * Antropometrik Bilgi : Kilo, Boy
* Aynı zamanda da verisetinde eksik değerlerin olduğu sütunlar blulunmaktadır.(1) Bunları tamamlamak için hangi methodoloji kullanıcağıma karar vercicem EDA kısmında
* Verisetindeki sütunların bazıları kategorik bazıları ise sayısal verilerden oluşmaktadır. Bu sütunları modellemeye hazır hale getirmek için bazı ön işlemler yapmam gerekecek.
* Veri setinde tekrara düşen veri de bulunmamaktadır. Bu durumda veri setindeki verilerin benzersiz olduğunu söyleyebilirim.
* Veri setindeki sütunların bazıları birbiriyle ilişkili olabilir. Bu durumda veri setindeki sütunlar arasında korelasyon analizi yapmam gerekecek.

# Analiz sırasındaki çıkarımlarım:
* Eksik veriler: Bazı sütunlar, özellikle de sağlıkla ilgili olanlar, eksik değerler içeriyor. Bu, analiz ve gelecekteki tahmine dayalı modelleme için çok önemlidir. Bu eksik değerleri nasıl ele alacağımıza karar vermem gerekiyor
* Tarih sütunları :  Birden çok tarih alanı vardır (Dogum_Tarihi, Ilac_Baslangic_Tarihi, Ilac_Bitis_Tarihi, Yan_Etki_Bildirim_Tarihi). Bunlar, ilaç kullanım süresi veya yan etki bildirimi sırasında kullanıcının yaşı gibi yararlı özelliklere dönüştürülebilir.
* Sağlık Geçmişi Sütunları: Bu sütunlar metinseldir (örneğin, aile üyelerinin kronik hastalıkları) ve bunları nasıl kodlayacağımıza veya analiz edeceğimize karar vermemiz gerekicek.






