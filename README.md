# Video Analiz Projesi: KMeans ile Çerçeve Kümeleme

Bu proje, **KMeans Clustering** algoritmasını kullanarak bir videonun çerçevelerini analiz eder ve bu çerçeveleri görsel benzerliklerine göre kümeler. Proje, video verilerinin ön işlenmesi, görsel özelliklerin çıkarılması ve kümeleme analizi gerçekleştirmeyi amaçlar.

---

## Proje Özeti

1. **Video Çözümleme ve Çerçeve Çıkartma**:
   - Video dosyasından karelerin çıkarılması.
   - Çerçeve özelliklerinin görsel analiz için işlenmesi.
   
2. **Kümeleme**:
   - Çerçeveler, **KMeans Clustering** algoritması kullanılarak görsel benzerliklerine göre kümelendi.
   
3. **Sonuçların Görselleştirilmesi**:
   - Her bir küme için örnek çerçevelerin görselleştirilmesi.

---

## Kurulum ve Çalıştırma

### Gereksinimler

Projenin çalışması için aşağıdaki Python kütüphanelerine ihtiyacınız var:
```bash
pip install opencv-python pandas numpy matplotlib scikit-learn
