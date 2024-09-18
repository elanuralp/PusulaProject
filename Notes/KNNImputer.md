## KNNImputer
KNNImputer en yakın komşu algoritmasını kullanarak eksik verileri doldurmak için kullanılan bir sınıftır. Bu sınıf, eksik verileri doldurmak için bir dizi strateji sunar. 

KNNImputer, eksik verileri daha akıllı ve veriye duyarlı bir şekilde tamamlamak için güçlü bir araçtır. En yakın komşu yaklaşımıyla, verideki gizli desenleri ve ilişkileri daha iyi yakalayabilir, bu da model performansını olumlu yönde etkileyebilir. Özelleştirilebilir ve esnek yapısı sayesinde, farklı veri setleri ve uygulamalar için uygun bir çözümdür.

Yerel Veri Desenlerini Yakalar:

Veri Dağılımını Yansıtır: En yakın komşuları dikkate alarak, KNNImputer verinin yerel yapısını ve desenlerini yakalayabilir.
Daha Doğru Tamamlama: Global istatistiklere (örneğin ortalama veya medyan) dayanan yöntemlere göre daha isabetli sonuçlar üretebilir.
Doğrusal Olmayan İlişkiler İçin Uygundur:

Esneklik: Doğrusal bir ilişki varsaymaz, bu nedenle karmaşık ve doğrusal olmayan ilişkileri olan veri setleri için idealdir.
Hem Sayısal Hem de Kategorik Verileri İşleyebilir:

Çok Yönlü Kullanım: Uygun ön işlemeyle (örneğin, kategorik verilerin kodlanması) farklı veri tipleriyle çalışabilir.
İmputasyonun Getirdiği Yanlılığı Azaltır:

Daha Az Bozulma: Gerçek verilere daha yakın tamamlama yaparak, sabit değerlerle doldurma yöntemlerinin getirebileceği yanlılığı azaltır.
Özelleştirilebilir Parametreler:

Kullanıcı Kontrolü: Komşu sayısı, mesafe metriği ve ağırlıklandırma gibi parametreleri ayarlayarak imputasyonu veri setinize uygun hale getirebilirsiniz.
Büyük Veri Setlerinde Etkilidir:

Dayanıklılık: Birden fazla eksik değeri olan geniş veri setlerinde etkili bir şekilde çalışabilir.
scikit-learn ile Entegrasyon:

Kolay Entegrasyon: scikit-learn'ün diğer bileşenleriyle (örneğin, Pipeline) sorunsuz bir şekilde çalışır, bu da modelleme sürecini kolaylaştırır.
Ağırlıklı İmputasyon Seçeneği:

Daha Hassas Tamamlama: Komşuların mesafelerine göre ağırlıklandırılması, daha yakın komşuların daha fazla etkiye sahip olmasını sağlar.
