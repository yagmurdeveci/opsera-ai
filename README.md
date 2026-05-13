# 🤖 Opsera AI

AI Destekli KOBİ Sipariş, Stok, Kargo ve Operasyon Yönetim Platformu

---

## 🚀 Proje Hakkında

Opsera AI, küçük ve orta ölçekli işletmelerin operasyon süreçlerini yapay zekâ destekli şekilde yönetebilmesi için geliştirilmiş modern bir operasyon yönetim platformudur.

Sistem;

* 📦 Sipariş yönetimi
* 🛒 Stok takibi
* 🚚 Kargo süreçleri
* 📊 Operasyon analizi
* 🤖 AI destekli öneri sistemi

gibi süreçleri tek merkezden yönetmeyi amaçlamaktadır.

---

## ✨ Özellikler

### 📦 Sipariş Yönetimi

* Sipariş oluşturma
* Sipariş sorgulama
* Sipariş durumu güncelleme

### 🛒 Stok Yönetimi

* Ürün ekleme
* Stok güncelleme
* Kritik stok analizi

### 🚚 Kargo Yönetimi

* Kargo takip sistemi
* Gecikme riski analizi

### 🤖 AI Operasyon Asistanı

Doğal dil ile operasyon yönetimi:

```bash
128 numaralı siparişim nerede?
Bugünkü operasyon risklerini analiz et
Organik Domates stoğunu 100 yap
129 numaralı siparişi teslim edildi yap
```

### 📊 Dashboard

* Operasyon grafikleri
* AI operasyon skoru
* Kritik stok uyarıları
* Gerçek zamanlı analiz ekranları

---

## 🧠 AI Özellikleri

Opsera AI içerisinde bulunan AI katmanı:

* operasyonel riskleri analiz eder,
* kritik stokları tespit eder,
* gecikme riski olan kargoları belirler,
* işletme için öneriler üretir.

### AI Operasyon Skoru

Sistem;

* kritik stok,
* geciken kargo,
* bekleyen sipariş

verilerini analiz ederek işletme için operasyon sağlığı skoru oluşturur.

---

## 🏗️ Sistem Mimarisi

```text
Frontend (Streamlit)
        ↓
FastAPI Backend
        ↓
AI Agent Layer
        ↓
SQLite Database
```

---

## ⚙️ Kullanılan Teknolojiler

### Backend

* Python
* FastAPI
* SQLAlchemy
* SQLite

### Frontend

* Streamlit
* Plotly
* Pandas

### AI

* Gemini API
* NLP tabanlı AI Agent sistemi

---

## 📂 API Endpointleri

| Endpoint           | Açıklama                   |
| ------------------ | -------------------------- |
| `/orders`          | Siparişleri getir          |
| `/products`        | Ürünleri getir             |
| `/shipments`       | Kargo bilgilerini getir    |
| `/dashboard`       | Dashboard verilerini getir |
| `/chat`            | AI asistan endpointi       |
| `/operation-score` | Operasyon skor analizi     |
| `/ai-summary`      | Günlük AI operasyon özeti  |

---

## 🔐 Giriş Bilgileri

```text
Kullanıcı Adı: admin
Şifre: 1234
```

---

# 🚀 Kurulum

## 1️⃣ Repository Clone

```bash
git clone https://github.com/kullaniciadi/opsera-ai.git
```

---

## 2️⃣ Backend Kurulumu

```bash
cd backend
pip install -r requirements.txt
```

### Backend Başlat

```bash
uvicorn main:app --reload
```

Backend:

```text
http://127.0.0.1:8000
```

---

## 3️⃣ Frontend Kurulumu

Yeni terminal aç:

```bash
cd frontend
pip install -r requirements.txt
```

### Frontend Başlat

```bash
streamlit run app.py
```

Frontend:

```text
http://localhost:8501
```

---

## 🔑 Gemini API Ayarı

Backend klasöründe `.env` dosyası oluştur:

```env
GEMINI_API_KEY=BURAYA_API_KEY
```

---

## 📈 Gelecek Geliştirmeler

* React tabanlı web arayüzü
* Mobil uygulama
* ERP entegrasyonları
* AI tahminleme sistemi
* Çoklu kullanıcı desteği
* Yetkilendirme sistemi
* PDF rapor üretimi
* Gerçek zamanlı bildirim sistemi

---

## 🎯 Proje Amacı

Opsera AI, KOBİ operasyonlarını daha:

* akıllı,
* hızlı,
* verimli,
* veri odaklı

hale getirmeyi hedeflemektedir.

---

# 👨‍💻 Geliştirici

## Yağmur Deveci

Yazılım Mühendisliği Öğrencisi

AI • Backend • Full Stack Development

---

# ⭐ Opsera AI

AI destekli yeni nesil operasyon yönetimi.
