## OneHotEncoder
* OneHotEncoder kategorik verileri sayısal verilere dönüştürmek için kullanılır.
* OneHotEncoder, kategorik verileri sayısal verilere dönüştürmek için kullanılan bir sınıftır. Bu sınıf, kategorik verileri dönüştürmek için bir dizi strateji sunar. En yaygın stratejiler şunlardır:
    * onehot
    * binary
    * ordinal
    * polynomial
    * identity

Desteklenen Veri Türleri: Özellikle kategorik değişkenler için uygun kodlama teknikleriyle birleştirildiğinde hem sayısal hem de kategorik verileri işleyebilir.


Makine Öğrenimi Modelleriyle Uyum:

Sayısal Dönüştürme: Birçok algoritma sayısal girdiler gerektirir. OneHotEncoder, kategorik verileri sayısal forma dönüştürerek modellerin bu verilerle çalışmasını sağlar.
Bilgi Kaybı Olmadan Dönüşüm:

Tam Temsil: Kategorik değişkenlerin tüm benzersiz değerlerini ayrı sütunlar olarak temsil eder, böylece hiçbir bilgi kaybolmaz.
Kategoriler Arasında Hiyerarşi Varsayımı Yok:

Tarafsız Kodlama: Kategorik değerler arasında doğal bir sıralama olmadığında idealdir, çünkü değerler arasında herhangi bir büyüklük ilişkisi varsaymaz.
Esneklik ve Özelleştirme:

Parametre Ayarlamaları: Seyreklik, bilinmeyen kategorilerle başa çıkma ve düşürülecek kategorilerin seçimi gibi çeşitli ayarlar sunar.
scikit-learn ile Entegrasyon:

Pipeline Desteği: Diğer ön işleme ve modelleme adımlarıyla kolayca entegre edilebilir.
