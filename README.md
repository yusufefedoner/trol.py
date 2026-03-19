# 🤖 Troll Hatırlatma Discord Botu

Bu bot, arkadaşlarınıza eğlenceli ve “troll” hatırlatmalar göndermek için tasarlanmıştır 😈
Belirli bir süre sonra bir kullanıcıya mesaj gönderir ve kalan süreyi takip etmenizi sağlar.

---

## 🚀 Özellikler

* ⏳ Belirli bir süre sonra mesaj gönderme
* 👤 Kullanıcı etiketleyerek hedef seçme
* 📅 Gün / saat / dakika bazlı zaman ayarlama
* ⏱️ Kalan süreyi öğrenme komutu
* 😂 Troll mesajlar için ideal kullanım

---

## 📌 Komutlar

### 1. Hatırlatma Oluşturma

```bash
!kur <@kullanıcı> <gün> <saat> <dakika> <mesaj>
```

**Örnek:**

```bash
!kur @ali 1 2 30 Tuvaleti temizle 😈
```

➡️ 1 gün 2 saat 30 dakika sonra bot, @ali'ye mesaj gönderir.

---

### 2. Kalan Süreyi Öğrenme

```bash
!kalan <@kullanıcı>
```

**Örnek:**

```bash
!kalan @ali
```

➡️ Bot, kalan süreyi ETİKETLENEN KULLANICIYA gönderir:

> "Senin için 3 saat 12 dakika kaldı."

---

### 3. Hatırlatma İptal Etme

```bash
!iptal <@kullanıcı>
```

➡️ Belirlenen görevi siler.

---

## ⚙️ Kurulum

1. Python yükle (3.10+ önerilir)
2. Gerekli kütüphaneleri yükle:

```bash
pip install discord.py
```

3. Bot token al:

* Discord Developer Portal’a gir
* Bot oluştur
* Token’ı kopyala

4. Kodu çalıştır:

```bash
python bot.py
```

---

## 🧠 Nasıl Çalışır?

* Kullanıcı komut girer
* Bot zamanı saniyeye çevirir
* Arka planda süreyi takip eder
* Süre dolunca hedef kullanıcıya mesaj gönderir

---

## ⚠️ Notlar

* Botun çalışır durumda olması gerekir
* Çok uzun süreler için veri kaydı (database) eklenebilir
* Restart atılırsa süreler sıfırlanabilir (geliştirilebilir)

---

## 💡 Geliştirme Fikirleri

* 📁 SQLite ile kalıcı veri kaydı
* 🔔 DM (özel mesaj) gönderme
* 🎨 Embed mesajlar
* 📊 Birden fazla görev desteği
* 🧾 Listeleme komutu (!liste)

---

## 😎 Örnek Kullanım Senaryosu

```bash
!kur @mehmet 0 0 10 Ders çalış 😏
```

10 dakika sonra:

> @mehmet → "Ders çalış 😏"

---

## 👑 Amaç

Arkadaş ortamında eğlence, küçük şakalar ve hatırlatmalar 😄

---

İstersen sana bunun **tam çalışan bot kodunu** da yazabilirim (direkt kopyala-çalıştır). 🚀
