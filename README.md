# TGFlix - Telegram Video Streaming Service

TGFlix, Telegram kanalınızdaki video içeriklerini alarak bir web sayfası üzerinden kullanıcıların izlemesine olanak sağlayan bir platformdur. Telegram botu kullanarak, kanalınızdaki video içerikleri çekilir ve bunlar, kullanıcıların başlıklarına göre arama yaparak görüntüleyebileceği şekilde web üzerinde listelenir.

---

## Özellikler

- **Telegram Kanalı Entegrasyonu**: Telegram botu ile kanalınızdaki videoları alır.
- **Arama ve Listeleme**: Web sayfası üzerinden başlıklar ile videolar aranabilir.
- **Video İzleme**: Kullanıcılar, videoları doğrudan web sayfasında izleyebilirler.
- **Veritabanı Desteği**: Videoların başlıkları ve dosya yolları bir veritabanında saklanır.
- **Kolay Kurulum**: VPS üzerinde kolayca kurulum yapabilir ve çalıştırabilirsiniz.

---

## Gereksinimler

- Python 3.7+ veya PHP
- MySQL/MariaDB Veritabanı
- Telegram Bot API
- VPS veya Web Sunucu
- Web Tarayıcısı

---

## Kurulum

### 1. Telegram Botu Oluşturun
Telegram'da **BotFather** kullanarak yeni bir bot oluşturun ve token alın. Bu token, botunuzu Telegram kanalınıza entegre etmek için gereklidir.

### 2. VPS veya Web Sunucusuna Bağlanın
VPS'nize SSH ile bağlanın ve aşağıdaki yazılımları yükleyin:
```bash
sudo apt update
sudo apt install python3 python3-pip mysql-server
