# DATA ANALYSIS
## Understanding the data
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
* 