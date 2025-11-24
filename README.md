# Crypto-app Android

## Overview
This document provides an overview of the Crypto-app Android application, which utilizes cutting-edge machine learning techniques for cryptocurrency analysis and forecasting. The application aims to equip users with tools for making informed investment decisions through advanced technical analysis and real-time data integration.

## Features
- **ML-based Crypto Forecasting**: Leverage machine learning algorithms to predict cryptocurrency price movements.
- **Technical Analysis (TA)**: Incorporate various tools and indicators for analyzing market trends.
- **Multi-Timeframe Models**: Analyze cryptocurrency data across multiple time frames for more robust insights.
- **Room DB Caching**: Utilize Room database for efficient local storage and retrieval of data.
- **OHLCV Data API Integration**: Integrate various APIs to fetch Open, High, Low, Close, Volume (OHLCV) data.
- **Jetpack Compose UI**: Build modern, declarative user interfaces with Jetpack Compose.

## Architecture
```
Crypto-app
├── data
│   ├── models
│   ├── repositories
│   └── sources
├── domain
│   ├── usecases
│   └── models
├── presentation
│   ├── viewmodels
│   └── ui
├── di
└── utils
```

## Quick Start / Build Instructions
1. **Clone the repository**:
   ```bash
   git clone https://github.com/yourusername/Crypto-app.git
   cd Crypto-app
   ```
2. **Open the project in Android Studio**.
3. **Build the project**:
   - Click on `Build` > `Rebuild Project`.
4. **Run the app**:
   - Click on `Run` in Android Studio.

## CI/CD with GitHub Actions
- The project is configured with GitHub Actions to facilitate Continuous Integration and Continuous Deployment (CI/CD).
- On each release, an .apk file will be generated and made available for download.

---

## Türkçe

## Genel Bakış
Bu belge, kripto para analiz ve tahmini için en son makine öğrenimi tekniklerini kullanan Crypto-app Android uygulamasının genel bir bakışını sunmaktadır. Uygulama, kullanıcıların ileri düzey teknik analiz ve gerçek zamanlı veri entegrasyonu yoluyla bilinçli yatırım kararları almasına yardımcı olmayı amaçlamaktadır.

## Özellikler
- **ML Tabanlı Kripto Tahmini**: Kripto para fiyat hareketlerini tahmin etmek için makine öğrenimi algoritmalarını kullanın.
- **Teknik Analiz (TA)**: Piyasa trendlerini analiz etmek için çeşitli araç ve göstergeleri dahil edin.
- **Çoklu Zaman Dilimi Modelleri**: Daha sağlam bilgiler için kripto para verilerini birden fazla zaman diliminde analiz edin.
- **Room DB Önbellekleme**: Veri için etkili yerel depolama ve geri alma işlemleri için Room veritabanını kullanın.
- **OHLCV Veri API Entegrasyonu**: Verilerin Açık, Yüksek, Düşük, Kapatma, Hacim (OHLCV) verilerini almak için çeşitli API'lerle entegre edin.
- **Jetpack Compose UI**: Modern, deklaratif kullanıcı arayüzleri oluşturmak için Jetpack Compose kullanın.

## Mimari
```
Crypto-app
├── data
│   ├── modeller
│   ├── depolar
│   └── kaynaklar
├── domain
│   ├── kullanım durumları
│   └── modeller
├── presentation
│   ├── viewmodel'ler
│   └── arayüz
├── di
└── yardımcılar
```

## Hızlı Başlangıç / Yapım Talimatları
1. **Depoyu klonlayın**:
   ```bash
   git clone https://github.com/kullaniciadiniz/Crypto-app.git
   cd Crypto-app
   ```
2. **Projeyi Android Studio'da açın**.
3. **Projeyi oluşturun**:
   - `Build` > `Rebuild Project` üzerine tıklayın.
4. **Uygulamayı çalıştırın**:
   - Android Studio'da `Run` üzerine tıklayın.

## GitHub Actions ile CI/CD
- Proje, Sürekli Entegrasyon ve Sürekli Dağıtım (CI/CD) işlemlerini kolaylaştırmak için GitHub Actions ile yapılandırılmıştır.
- Her sürümde, bir .apk dosyası oluşturulacak ve indirilebilir hale getirilecektir.
