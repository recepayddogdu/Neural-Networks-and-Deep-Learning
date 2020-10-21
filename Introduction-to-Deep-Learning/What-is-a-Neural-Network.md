# Neural Network(Sinir Ağları) Nedir?
Beynin nasıl çalıştığından ilham alan güçlü bir öğrenme algoritmasıdır.
## Örnek 1 - Single Neural Network
Konut Fiyat Tahmin örneği ile başlayalım. Diyelim ki altı ev ile alakalı bir veri setiniz var. Bu sebeple evin büyüklüğünü metre kare cinsinden biliyor ayrıca evin fiyatını da biliyorsunuz ve siz evlerin fiyatını büyüklüklerine göre tahmin edip fonksiyonlarına uydurmak istiyorsunuz.

Bu bir lineer regresyon problemidir çünkü boyutun bir fonksiyonu olarak fiyat sürekli bir çıktıdır.

Fiyatların asla negatif olamayacağını biliyoruz, bu yüzden sıfırdan başlayan **Rectified Linear Unit (ReLU)** adlı bir fonksiyon oluşturuyoruz.

![home-predict](https://i.hizliresim.com/12anCA.png)

---
## Örnek 2 - Multiple Neural Network
Bir evin fiyatı, büyüklük, yatak odası sayısı, posta kodu ve bölgenin zenginliği gibi diğer özelliklerden etkilenebilir. Sinir ağının rolü fiyatı tahmin etmektir ve gizli birimleri otomatik olarak üretecektir. Sadece x girdilerini ve y çıktısını vermemiz gerekiyor.

![Multiple_NN](https://i.hizliresim.com/gfuBNF.png)


