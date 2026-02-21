# CO₂ Emisyon Tahmini (Regresyon)

Bu proje, Kaggle’daki **“CO2 Emission by Vehicles”** veri setini kullanarak araç özelliklerinden **CO2 Emissions (g/km)** değerini tahmin eden bir regresyon çalışmasıdır.

Notebook: `Carbon Emission.ipynb`  
Veri: `CO2 Emissions_Canada.csv` (projede mevcut)

## İçerik

- EDA (keşifsel veri analizi)
- Ön işleme: eksik değer yönetimi, kategorik değişkenler için one-hot encoding, sayısal ölçekleme
- Model karşılaştırma (ör. Linear Regression, Decision Tree, Random Forest, AdaBoost, XGBoost)
- Değerlendirme metrikleri: R², MAE, MSE/RMSE
- Cross-validation ve `RandomizedSearchCV` ile hiperparametre araması

## Kurulum

Python 3.10+ önerilir.

```bash
python -m venv .venv
.\.venv\Scripts\activate
pip install -r requirements.txt
```

## Çalıştırma

```bash
jupyter lab
```

Ardından `Carbon Emission.ipynb` dosyasını açıp hücreleri sırayla çalıştırabilirsiniz.

## Proje Dosyaları

- `Carbon Emission.ipynb`: Tüm analiz + modelleme akışı
- `CO2 Emissions_Canada.csv`: Modelleme için kullanılan veri seti
- `Data Description.csv`: Değişken açıklamaları (varsa/opsiyonel)
- `requirements.txt`: Gerekli Python paketleri
- `.gitignore`: Git’e eklenmemesi gereken dosyalar

## Not

Veri seti Kaggle kaynaklıdır: [CO2 Emission by Vehicles](https://www.kaggle.com/datasets/debajyotipodder/co2-emission-by-vehicles)

