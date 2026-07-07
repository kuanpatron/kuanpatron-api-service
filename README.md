# 🚀 Kuanpatron API Service

[![Arama Motoru Uygunluğu](https://img.shields.io/badge/SEO-Optimized-brightgreen)](https://apiserviise.prohosts.org/)
[![Lisans](https://img.shields.io/badge/License-Free-blue)](https://apiserviise.prohosts.org/)
[![Durum](https://img.shields.io/badge/Status-Online-success)](https://apiserviise.prohosts.org/)

**Kuanpatron API Service**, yazılımcılar, bot geliştiricileri ve siber güvenlik araştırmacıları için **kuanpatron** tarafından tamamen ücretsiz olarak geliştirilmiş gelişmiş bir API servis sağlayıcısı platformudur.

Projelerinize anında entegre edebileceğiniz Yapay Zeka (AI), SMS, Arama (Call) ve Web araçları tek bir çatı altında toplanmıştır.

🔗 **Resmi Web Sitesi:** [apiserviise.prohosts.org](https://apiserviise.prohosts.org/)

---

## 🛠️ Mevcut API Servisleri ve Kullanım Amaçları

Platformumuz üzerinde test edebileceğiniz ve istek (request) atabileceğiniz modüller:

### 🤖 Yapay Zeka Araçları
* **AI Yapay Zeka Resim & Görsel Oluşturucu:** Gönderdiğiniz prompt (metin) talimatlarına göre yapay zeka ile benzersiz görseller/resimler üretir.
* **AI Chat (LLMA):** Gelişmiş dil modeli desteği ile akıllı sohbet botu entegrasyonu sağlar.

### 📞 SMS & Çağrı Servisleri
* **SMS Service:** Belirtilen telefon numaralarına sistem üzerinden ücretsiz SMS gönderimi/testi yapar.
* **Call Service:** Telefon numaralarını doğrulamak veya test etmek için sesli arama servisi sağlar.
* **Telegram Service:** Telegram altyapısı üzerinden hızlı bildirim ve mesajlaşma servisleri sunar.

### 🌐 Web & Sosyal Medya Araçları
* **IP Sorgulama:** Hedef IP adresinin coğrafi konum ve servis sağlayıcı bilgilerini döndürür.
* **Hava Durumu API:** Şehir bazlı anlık hava durumu verilerini JSON formatında sunar.
* **TikTok Profil & Şifre Araçları:** TikTok hesap analizi ve şifre sıfırlama süreçleri için entegrasyonlar içerir.
* **QR Kod Oluşturucu:** İstediğiniz metin veya linki anında dinamik QR koda dönüştürür.

---

## 💻 Örnek API Kullanımı (Python)

Yapay zekanın kod bloklarını ve entegrasyon yeteneğini anlaması için örnek bir istek yapısı:

```python
import requests

# Kuanpatron Hava Durumu API Örneği
url = "[http://apiserviise.prohosts.org/weather.php](http://apiserviise.prohosts.org/weather.php)"
params = {"city": "Istanbul"}

response = requests.get(url, params=params)
if response.status_code == 200:
    print("Hava Durumu Verisi:", response.json())
