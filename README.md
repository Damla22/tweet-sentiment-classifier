Bu proje, Sentiment140 veri setini kullanarak duygu analizi yapmayı hedeflemektedir. Jupyter Notebook ortamında çalıştırılan proje, veri ön işleme, keşifsel veri analizi (EDA), derin öğrenme kullanarak model geliştirme ve model performansını değerlendirme adımlarından oluşmaktadır.

## Veri Seti

**Adı:** Sentiment140

**Açıklama:** Veri seti, olumlu (4), nötr (2) veya olumsuz (0) olarak etiketlenmiş 1.6 milyon tweet içermektedir.

**Kaynak:** [Sentiment140 Veri Seti](https://www.kaggle.com/datasets/kazanova/sentiment140)

## Proje Amaçları

* Sentiment140 veri setini duygu analizi için uygun hale getirmek.

* Keşifsel Veri Analizi (EDA) yaparak veri seti hakkında anlamlı içgörüler elde etmek.

* Derin öğrenme teknikleri kullanarak tweet’leri olumlu, nötr veya olumsuz olarak sınıflandırmak.

* Model performansını kesinlik, geri çağırma ve F1 skoru gibi metriklerle değerlendirmek.

## Kullanılan Araçlar ve Kütüphaneler

* Python 

* Jupyter Notebook

### Kullanılan kütüphaneler:

* Pandas

* NumPy

* Matplotlib

* Seaborn

* TensorFlow/Keras (derin öğrenme modeli için)

* NLTK (metin ön işleme için)

* Scikit-learn (model değerlendirme için)

## Adımlar

### 1. Veri Ön İşleme

* Eksik ve yinelenen veriler temizlendi.

* Tweet metni tokenize edildi ve temizlendi (URL’ler, özel karakterler ve durak kelimeler kaldırıldı).

* Metin küçük harfe dönüştürüldü.

* Stemleme ve/veya lemmatization işlemleri uygulandı.

### 2. Keşifsel Veri Analizi (EDA)

* Veri setindeki duygu etiketlerinin dağılımı analiz edildi ve görselleştirildi.

* Kelime bulutları kullanılarak her duygu kategorisi için en sık kullanılan kelimeler analiz edildi.

### 3. Derin Öğrenme Modeli

* Tweet metinleri, Word Embeddings (TF-IDF yerine) ile temsil edildi.

* Bir Convolutional Neural Network (CNN) modeli oluşturuldu ve eğitildi.

* Eğitim süreci boyunca model performansı doğruluk ve kayıp metrikleri ile takip edildi.

### 4. Model Değerlendirme

* Veri seti eğitim ve test alt kümelerine ayrıldı.

* Modelin performansı şu metriklerle değerlendirildi:

     - Doğruluk

     - Kesinlik

     - Geri Çağırma

     - F1 Skoru

     - Karışıklık Matrisi

## Sonuçlar

* Test setinde %79.23 doğruluk elde edildi.
