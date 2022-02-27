# Keras-Fake-Real-Classification

Biyometrik özelliklerden faydalanan kimlik doğrulama amaçlı çeşitli yöntemler literatürde bulunmaktadır. Bu
yöntemlerden biri olan yüz tanıma sistemi, diğer biyometrik sistemlere göre temassızlık ve düşük maliyetli
kameralar sayesinde daha çok tercih edilir hale gelmiştir. Sahtekarlar bu sistemlere çeşitli yöntemlerle saldırı
düzenleyerek yetkisiz giriş yapmaktadırlar. Bu saldırılar basılı fotoğraflar, dijital fotoğraflar ve 3 boyutlu
maskeler ile yapılmaktadır. Gerçek girişim ve sahte girişimler sınıflandırma yaklaşımı ile tespit edilecektir.

![image](https://user-images.githubusercontent.com/56585669/155888835-2ede6c7f-8acc-41e8-84f6-c17996adc008.png)


# Derin Öğrenme Mimarisi

Renkler karşısında insan teninin, fotoğraf kâğıdının ve dijital ekranların yansıma
karakteristiğinin analizi için MobileNetv2 modeli tercih edildi. 2018 yılının
başlarında literatüre giren bu model mobil cihazlarda çalışma yeteneğine sahiptir.
MobileNetV2, etkili yapı taşları olarak derinlemesine ayrılabilir evrişimi kullanarak
MobileNetV1 fikirlerini temel alır. Bununla birlikte, V2 mimariye iki yeni özellik
sunar; 1) katmanlar arasındaki doğrusal darboğazlar, 2) darboğazlar arasındaki
kısayol bağlantılarıdır. MobileNetV2, nesne algılama ve bölümleme için çok etkili
bir özellik çıkarıcıdır. Örneğin, yeni tanıtılan SSDLite ile eşleştirildiğinde
algılama için yeni model, MobileNetV1'den aynı doğrulukla yaklaşık %35 daha
hızlıdır.
MobileNetV2 Mimarisi ImageNet veri seti kullanılarak bir milyondan fazla görüntü üzerinde 
eğitilmiş ağ üzerinden transfer öğrenimi (transfer learning) ile oluşturduğumuz veri setleri ile
model eğitimi yapılmaktadır. Transfer öğrenimi bir problemi çözerken edinilen bilgi
ve tecrübeyi başka bir problemi çözerken kullanmaktır.

# MobileNETV2 Derin Öğrenme Mimarisi Katmanları
![image](https://user-images.githubusercontent.com/56585669/155889067-f843b0ff-afbb-4a7b-9992-0b9b283b1ee4.png)


# EĞİTİM GRAFİĞİ 
![image](https://user-images.githubusercontent.com/56585669/155889073-284ad8e4-e1d3-4747-9b3a-2010af1f9743.png)

