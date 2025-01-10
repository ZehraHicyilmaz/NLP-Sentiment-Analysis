
# NLP Duygu Analizi

## Genel Bakış
Bu proje, bir film inceleme veri seti üzerinde derin öğrenme modeli (LSTM) kullanarak duygu analizi yapmayı hedeflemektedir. Amaç, incelemeleri içeriğine göre olumlu veya olumsuz olarak sınıflandırmaktır. Proje, veri ön işleme, model eğitimi ve değerlendirme gibi yaygın NLP ve makine öğrenimi tekniklerini içerir.

## Özellikler
- **Veri Ön İşleme**:
  - Metin temizleme (stopwords kaldırma, lemmatization).
  - Tokenization ve dizi padding.
- **Model Mimarisi**:
  - LSTM tabanlı sinir ağı.
  - Gömüleme katmanları, dropout ve yoğun katmanlar (dense layers) ile sınıflandırma.
- **Değerlendirme Metrikleri**:
  - Confusion Matrix, F1 Skoru ve Recall.
- **Veri Seti**:
  - IMDB 50K Film Yorumları Veri Seti, Kaggle'dan indirildi.

## Kullanılan Teknolojiler
- Python
- Kütüphaneler: Pandas, NumPy, Matplotlib, NLTK, TensorFlow/Keras, scikit-learn
- Kaggle API ile veri seti alımı

## Kurulum
1. Depoyu klonlayın:
   ```bash
   git clone https://github.com/yourusername/NLP-Sentiment-Analysis.git
   cd NLP-Sentiment-Analysis
   ```
2. Gerekli kütüphaneleri yükleyin:
   ```bash
   pip install -r requirements.txt
   ```
3. Kaggle API kimlik bilgilerini ayarlayın:
   - `kaggle.json` dosyanızı Kaggle hesabınızdan indirin.
   - Dosyayı `~/.kaggle/` dizinine yerleştirin.
4. Notebook'u Google Colab'de veya yerel bilgisayarınızda çalıştırın.

## Çalıştırma Adımları
1. `NLP-Sentiment-Analysis.ipynb` notebook'unu açın.
2. Aşağıdaki adımları izleyin:
   - Veri setini yükleyin.
   - Veriyi ön işleyin.
   - LSTM modelini eğitin.
   - Model performansını değerlendirin.

## Sonuçlar
- Model, film yorumlarını sınıflandırma konusunda yüksek doğruluk oranına ulaştı.
- Değerlendirme için F1 Skoru ve Recall gibi metrikler kullanıldı.
- Sonuçları daha iyi anlamak için confusion matrix görselleştirildi.

## Dosya Yapısı
- `NLP-Sentiment-Analysis.ipynb`: Tüm adımları içeren ana notebook.
- `requirements.txt`: Bağımlılıkların listesi.
- `README.md`: Proje için dokümentasyon.

## Veri Seti
Veri seti, Kaggle API ile doğrudan indirilebilir. Kaggle API anahtarınızın doğru bir şekilde ayarlı olduğundan emin olun.

## Teşekkürler
- **Veri Seti**: [IMDB 50K Film Yorumları Veri Seti](https://www.kaggle.com/datasets/lakshmi25npathi/imdb-dataset-of-50k-movie-reviews)
- **Kütüphaneler**: TensorFlow/Keras, NLTK, scikit-learn

## Lisans
Bu proje MIT Lisansı altında lisanslanmıştır.

---
Projeye katkıda bulunmak için pull request oluşturabilir veya sorun bildirebilirsiniz!

