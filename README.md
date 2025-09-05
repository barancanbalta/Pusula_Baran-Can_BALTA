# Pusula Data Science Project - Talent Academy Case 2025

**Geliştirici:** Baran Can Balta
**E-mail:** barannnn2001@outlook.com
**LinkedIn:** https://www.linkedin.com/in/baran-can-balta/

Bu proje, Pusula Talent Academy 2025 veri bilimi stajyerlik başvurusu kapsamında geliştirilmiş kapsamlı bir veri analizi ve ön işleme çalışmasıdır.

## 📊 Proje Genel Bakış

Bu proje, fiziksel tıp ve rehabilitasyon veri seti üzerinde kapsamlı keşifsel veri analizi (EDA) ve veri ön işleme süreçlerini içermektedir. Dataset **2235 gözlem** ve **13 özellik** içermekte olup, hedef değişken **TedaviSuresi**'dir.

### 🎯 Proje Amacı:

- Kapsamlı Keşifsel Veri Analizi (EDA) gerçekleştirme
- Veriyi tahmin modelleme için hazır hale getirme
- TedaviSuresi hedef değişkeni etrafında temiz, tutarlı ve analiz edilebilir veri seti oluşturma

### 📋 Dataset Özellikleri:

- **HastaNo**: Anonimleştirilmiş hasta kimliği
- **Yas**: Yaş
- **Cinsiyet**: Cinsiyet
- **KanGrubu**: Kan grubu
- **Uyruk**: Uyruk
- **KronikHastalik**: Kronik durumlar (virgülle ayrılmış liste)
- **Bolum**: Departman/Klinik
- **Alerji**: Alerjiler (tekil veya virgülle ayrılmış)
- **Tanilar**: Tanılar
- **TedaviAdi**: Tedavi adı
- **TedaviSuresi**: Tedavi süresi (seans sayısı) - **HEDEF DEĞİŞKEN**
- **UygulamaYerleri**: Uygulama yerleri
- **UygulamaSuresi**: Uygulama süresi

## 🚀 Temel Özellikler

- **Kapsamlı Keşifsel Veri Analizi (EDA)**
- **Çoklu Veri Ön İşleme Stratejileri**
- **Otomatik Veri Kalitesi Kontrolü**
- **Detaylı Görselleştirmeler**
- **Comprehensive Raporlama Sistemi**

## 📁 Proje Yapısı

```
Pusula_Data_Science_Project_Final/
├── src/                               # Kaynak kodlar
│   ├── main_data_preprocessing.py           # Ana EDA ve preprocessing scripti (optimized)
│   └── final_analysis.py                    # Final analiz scripti
├── data/                              # Ham veriler
│   └── Talent_Academy_Case_DT_2025.xlsx     # Orijinal dataset
├── outputs/                           # İşlenmiş veriler
│   ├── dataset_processed_final.csv          # Final işlenmiş dataset (en iyi versiyon)
│   ├── dataset_processed_final.parquet      # Parquet formatında final dataset
│   └── data_dictionary_final.csv           # Final veri sözlüğü
├── reports/                           # Raporlar ve görselleştirmeler
│   ├── Pusula_EDA_Preprocess_Raporu.pdf    # Detaylı PDF raporu
│   ├── validation_summary_*.md             # Validasyon raporları
│   └── *.png                              # Görselleştirme dosyaları
├── requirements.txt                   # Python bağımlılıkları
├── Pusula_Intern_Data_Science_2025.pdf # Proje dokümantasyonu
├── .gitignore                         # Git ignore dosyası
└── README.md                         # Bu dosya
```

## 🛠️ Teknolojiler ve Kütüphaneler

- **Python 3.x**
- **Pandas** - Veri manipülasyonu
- **NumPy** - Sayısal işlemler
- **Matplotlib & Seaborn** - Görselleştirme
- **Scikit-learn** - Makine öğrenmesi araçları
- **Unidecode** - Türkçe karakter temizleme
- **FPDF2** - PDF rapor oluşturma
- **OpenPyXL** - Excel dosya okuma

## 🔄 Veri İşleme Stratejisi

### Optimized Preprocessing (`main_data_preprocessing.py`)

- **Akıllı Eksik Veri Doldurma**: Adaptif stratejiler ile eksik verilerin optimal doldurulması
- **Gelişmiş Aykırı Değer Tespiti**: İstatistiksel yöntemlerle outlier detection ve düzeltme
- **Akıllı Kategorik Değişken Yönetimi**: Optimize edilmiş encoding stratejileri
- **Özellik Mühendisliği**: Yeni değişken türetme ve feature selection
- **Veri Kalitesi Kontrolü**: Comprehensive validation ve quality checks

## 📈 Analiz Sonuçları

### Veri Kalitesi Metrikleri

- **Eksik Veri Oranı**: %X → %Y (iyileştirme sonrası)
- **Aykırı Değer Sayısı**: X → Y (temizleme sonrası)
- **Feature Sayısı**: X → Y (engineering sonrası)

### Model Hazırlık Durumu

- ✅ Eksik veriler temizlendi
- ✅ Kategorik veriler encode edildi
- ✅ Sayısal veriler normalize edildi
- ✅ Feature engineering tamamlandı

## 🚀 Kullanım

### Kurulum

```bash
# Repository'yi klonlayın
git clone <repository-url>
cd Pusula_Data_Science_Project_Final

# Gerekli kütüphaneleri yükleyin
pip install -r requirements.txt
```

### Ana Analizi Çalıştırma

```bash
# Ana EDA ve preprocessing (optimized versiyon)
python src/main_data_preprocessing.py

# Final analiz
python src/final_analysis.py
```

## 📊 Çıktılar

### İşlenmiş Veriler

- `outputs/dataset_processed_final.csv` - Final işlenmiş dataset (en iyi versiyon)
- `outputs/dataset_processed_final.parquet` - Parquet formatında final dataset
- `outputs/data_dictionary_final.csv` - Final veri sözlüğü

### Raporlar

- `reports/Pusula_EDA_Preprocess_Raporu.pdf` - Detaylı analiz raporu
- `reports/validation_summary_*.md` - Validasyon özetleri
- `reports/*.png` - Görselleştirme dosyaları

## 🎯 Proje Hedefleri

1. **Veri Kalitesini Artırma**: Eksik ve hatalı verileri düzeltme
2. **Feature Engineering**: Yeni özellikler oluşturma
3. **Model Hazırlığı**: ML algoritmalarına uygun format
4. **Raporlama**: Kapsamlı analiz dokümantasyonu
5. **Reproducibility**: Tekrarlanabilir analiz süreçleri

## 📋 Veri Sözlüğü

Detaylı veri sözlüğü `outputs/data_dictionary_final.csv` dosyasında bulunabilir.

## 📊 Görselleştirme Notları

**✅ Problem Çözüldü**: Orijinal görselleştirmelerdeki etiket okumia problemleri düzeltildi!

### Final Görselleştirmeler:

- `reports/TARGET_VARIABLE_ANALYSIS.png` - **HEDEF DEĞİŞKEN ANALİZİ** (TedaviSuresi kapsamlı analizi)
- `reports/kronik_hastalik_CORRECT_FINAL.png` - **DOĞRU** kronik hastalık analizi (Astım tekrar problemi çözüldü)
- `reports/comprehensive_analysis_FIXED.png` - Kapsamlı çoklu analiz görseli
- `reports/kronik_sayisi_FIXED.png` - Hasta başına kronik hastalık sayısı dağılımı
- `reports/yas_dagilimi_FIXED.png` - Hasta yaş dağılımı analizi

### Teknik İyileştirmeler:
- **🎯 HEDEF DEĞİŞKEN ODAKLI ANALİZ**: TedaviSuresi kapsamlı analizi eklendi ✅
- **KRİTİK DÜZELTME**: Astım hastalığının tekrarlanma problemi çözüldü ✅
- Her kronik hastalık sadece bir kez sayılıyor (doğru binary encoding) ✅
- Yatay bar chart formatı ile etikel okunabilirliği artırıldı ✅
- Hastalık isimleri kısaltıldı ve anlaşılır hale getirildi ✅
- Değerler grafiklerin üzerinde net şekilde gösteriliyor ✅
- Professional grid çizgiler ve renk paleti ✅
- TedaviSuresi ile diğer değişkenler arası korelasyon analizi ✅

## 🔍 Sonuçlar ve Öneriler

### Ana Bulgular

- **TedaviSuresi (Hedef Değişken) Analizi**:
  - Ortalama tedavi süresi: ~14.6 seans
  - En sık tedavi süresi: 15 seans
  - Yaş ile düşük korelasyon (-0.013)
  - Cinsiyet farkı minimal (Erkek: 14.4, Kadın: 14.8 seans)
  - Kronik hastalık sayısı tedavi süresini etkiliyor

- **Dataset Kalitesi**: 
  - Eksik veri problemi çözüldü (%100 complete)
  - Kategorik değişkenler doğru encode edildi
  - Binary encoding stratejisi optimize edildi

- **Veri Mühendisliği**:
  - Multi-hot encoding comma-separated değerler için uygulandı
  - 65 feature'a kadar genişletildi (preprocessing sonrası)
  - Model-ready format elde edildi

### Gelecek Adımlar

- Model training ve evaluation
- Cross-validation implementasyonu
- Hyperparameter optimization
- Production deployment hazırlığı

## 👨‍💻 Geliştirici

**Baran Can Balta** - Data Science Intern Candidate
**E-mail:** barannnn2001@outlook.com
**LinkedIn:** https://www.linkedin.com/in/baran-can-balta/
**Proje:** Pusula Talent Academy 2025

## 📄 Lisans

Bu proje Pusula Talent Academy 2025 stajyerlik başvurusu kapsamında geliştirilmiştir.

---

*Bu README dosyası projenin kapsamlı bir özetini sunmaktadır. Detaylı teknik bilgiler için kaynak kodları ve raporları inceleyiniz.*
