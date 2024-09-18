## SımpleImputer
* Makine öğrenmesi modelleri, eksik verilerle başa çıkamaz. Bu nedenle eksik verileri doldurmak için bir dizi teknik vardır. SimpleImputer, eksik verileri doldurmak için kullanılan bir sınıftır.

* SimpleImputer, eksik verileri doldurmak için kullanılan bir sınıftır. Bu sınıf, eksik verileri doldurmak için bir dizi strateji sunar. En yaygın stratejiler şunlardır:
    * mean 
    * median 
    * most_frequent (mod)
    * constant (for categorical data)
  

Desteklenen Veri Türleri: Özellikle kategorik değişkenler için uygun kodlama teknikleriyle birleştirildiğinde hem sayısal hem de kategorik verileri işleyebilir.

İşlem pipeline ile Entegrasyon: SimpleImputer, scikit-learn işlem pipelineları kolayca entegre edilebilir ve bu da atamanın model eğitim ve değerlendirme sürecinin bir parçası olmasını sağlar.

SimpleImputer Kullanmanın Avantajları:

* Basit ve kullanımı kolaydır.
* Eksik verileri doldurmak için bir dizi strateji sunar.
* Sayısal ve kategorik verilerle çalışabilir.
* İşlem pipeline ile entegre edilebilir.
* Scikit-learn ile uyumludur.