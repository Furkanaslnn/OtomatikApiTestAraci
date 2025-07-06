# Otomatik API Test Aracı 🧪

OtomatikApiTestAraci, RESTful API'leri otomatik olarak test etmek için geliştirilmiş bir Python tabanlı test aracıdır. JSON formatında belirlenen test senaryolarına göre HTTP istekleri gönderir, gelen yanıtları doğrular ve sonuçları raporlar.

## 🎯 Temel Amaç

- API uç noktalarının doğruluğunu hızlıca test edebilmek
- Yanıt kodlarını ve içeriklerini otomatik şekilde kontrol etmek
- Geliştirme ve QA süreçlerini hızlandırmak

## 🧰 Özellikler

- JSON dosyasına tanımlı test senaryolarını çalıştırma
- Her bir istek için:
  - HTTP metodu (GET, POST, PUT, DELETE, vb.)
  - Endpoint ve parametre desteği
  - Beklenen yanıt kodu kontrolü
  - Beklenen içerik doğrulaması
- Sonuçları terminale açık ve okunabilir şekilde yazdırır

## 🔧 Kurulum

```bash
git clone https://github.com/Furkanaslnn/OtomatikApiTestAraci.git
cd OtomatikApiTestAraci
python3 -m venv venv
source venv/bin/activate  # Windows için: venv\Scripts\activate
pip install -r requirements.txt
