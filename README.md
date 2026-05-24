# 🔍 Agent Taylor — İnteraktif Gerilim Oyunu

> *"Her karar iz bırakır. Her seçim bir bedeli var."*

🎮 **Oyna:** https://clampgod1.github.io/agent-taylor-my-first-game-/

---

## 📖 Hakkında

Agent Taylor, MI6 dedektifi Taylor olarak oynadığınız tamamen Türkçe ve İngilizce destekli bir interaktif gerilim oyunudur. Üç farklı vakada onlarca karar verin — her seçim hikâyeyi değiştirir ve bazı kararların geri dönüşü yoktur.

---

## 🗺️ Vakalar

### VAKA 01 — Dark London
Thames Rıhtımları'nda üç ölü polis. Tek kurşun, tek nişancı.
İçimizden biri mi?

### VAKA 02 — Ghost Protocol
Beş yıl önce öldüğü sanılan bir ajan Berlin'den mesaj gönderdi.
ARACHNE nedir? Finch nereye kadar gidiyor?

### VAKA 03 — Neon Reckoning
Los Angeles. Axis Pacific. SUNFALL operasyonu.
Satın alınan kararlar, satılan insanlar.

---

## ✨ Özellikler

- 🎭 **71 sahne** — 3 chapter, onlarca dal
- 🔚 **13 farklı son** — her oynanışta farklı sonuç
- 🌐 **Tam TR/EN dil desteği** — oyun içinden değiştirilebilir
- 🎵 **Atmosferik müzik** — chapter'a göre değişen ambient
- 💾 **Kayıt sistemi** — kaldığın yerden devam et
- 📱 **Mobil uyumlu** — telefon ve tablette sorunsuz çalışır
- 🚫 **Reklam yok, ücret yok**

---

## 🛠️ Kullanılan Teknolojiler

| Teknoloji | Kullanım |
|-----------|----------|
| HTML5 | Oyun yapısı |
| CSS3 | Animasyonlar, tema, responsive tasarım |
| Vanilla JavaScript (ES5) | Oyun motoru, dil sistemi, kayıt sistemi |
| Web Audio API | Prosedürel ambient müzik |
| Canvas API | Sahne animasyonları, atmosfer efektleri |
| localStorage | Oyun ilerlemesi kaydetme |

**Dış bağımlılık yok.** Tek HTML dosyası, framework kullanılmadı.

---

## 📁 Proje Yapısı

```
agent-taylor/
├── index.html          ← Tüm oyun (HTML + CSS + JS tek dosya)
├── android/            ← Android Studio projesi
│   └── app/
│       └── src/main/
│           ├── assets/public/index.html
│           ├── java/com/agenttaylor/MainActivity.java
│           └── res/
├── ios/                ← Xcode projesi
│   └── App/App/
│       ├── AppDelegate.swift
│       ├── ViewController.swift
│       └── Info.plist
└── README.md
```

---

## 📊 İstatistikler

```
Toplam kod satırı  : ~2.700
Toplam sahne       : 71
Toplam son         : 13
Ortalama oyun süresi: 2-3 saat (tüm sonlar: 8+ saat)
Dosya boyutu       : ~250 KB (sıkıştırılmamış)
```

---

## 🚀 Kurulum

### Web (tarayıcı)
Sadece `index.html` dosyasını tarayıcıda aç. İnternet gerekmez.

### Android
```
1. android/ klasörünü Android Studio'da aç
2. Build → Generate Signed App Bundle
3. app-release.aab → Play Store'a yükle
```

### iOS
```
1. ios/App/ klasörünü Xcode'da aç
2. index.html'yi Bundle Resources'a ekle
3. Product → Archive → App Store Connect
```

---

## ✍️ Geliştirici

**Mustafa Bademci**  
📧 [e-posta]  
🌐 https://clampgod1.github.io/agent-taylor-my-first-game-/

---

## 📜 Lisans

Bu proje tamamen orijinal içerik barındırmaktadır.  
Senaryo, diyaloglar ve oyun tasarımı © 2026 Mustafa Bademci  
Tüm hakları saklıdır.
