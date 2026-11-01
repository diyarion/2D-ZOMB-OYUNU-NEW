# 🩸 Blood Night

Karanlık bir gecede zombi dalgalarına karşı hayatta kalmaya çalıştığın, tarayıcıda çalışan 2D nişancı oyunu. Tek dosya, kurulum yok, harici dosya yok. Hem bilgisayarda hem telefonda oynanır.

## ✨ Özellikler

- **Karanlık atmosfer:** Fenerin yalnızca önünü aydınlatır, zombileri karanlıkta yakından görürsün
- **Dalga sistemi:** Her dalgada daha çok ve daha güçlü zombi gelir, her 5. dalgada dev bir boss çıkar
- **3 zombi tipi:** Yavaş, hızlı ve dev zombi
- **3 silah:** Tabanca, SMG, pompalı tüfek. Zombilerden silah, mermi ve can düşer
- **Kalıcı kan lekeleri**, ekran sarsıntısı, hasar alınca kırmızı ekran
- **Atılma (dash)** ve dayanıklılık çubuğu
- **Mobil destek:** Çift joystick ve ekran butonları
- **Sesler:** Hepsi kodla üretilir (silah, vuruş, zombi inlemesi, korku uğultusu)
- **En yüksek skor** tarayıcıda saklanır

## 🎮 Kontroller

| Eylem | Bilgisayar | Telefon |
|---|---|---|
| Yürü | W A S D / Oklar | Sol joystick |
| Nişan al | Fare | Sağ joystick |
| Ateş | Sol tık (basılı tut) | Sağ joystick'i it (otomatik ateş) |
| Şarjör | R | 🔄 |
| Silah değiştir | Q / 1-2-3 / Fare tekerleği | 🔫 |
| Atıl | Boşluk / Shift | 💨 |

**Eşyalar:** 🔵 **W** silah · 🟡 **A** mermi · 🔴 **+** can

## ▶️ Çalıştırma

`blood-night.html` dosyasını tarayıcıda aç ve **BAŞLA**'ya bas. İnternet bağlantısı gerekmez.

**GitHub Pages ile yayınlamak için:**
1. Dosyanın adını `index.html` yap ve repoya yükle
2. Repo → **Settings** → **Pages**
3. Source: `Deploy from a branch`, branch: `main`, klasör: `/ (root)`
4. Birkaç dakika sonra `https://KULLANICI_ADIN.github.io/REPO_ADI/` adresinden oynanır

> Ses, tarayıcı kuralları gereği ilk tıklamadan veya dokunuştan sonra başlar.

## 🛠️ Teknik notlar

- Saf HTML + CSS + JavaScript, Canvas 2D, kütüphane yok
- Zemin ve kan lekeleri önceden çizilen katmanlara işlenir, böylece telefonda da akıcı çalışır
- Karanlık/fener efekti ayrı bir katmanla çizilir
- Sesler WebAudio ile koddan üretilir

## 📄 Lisans

İstediğin lisansı ekleyebilirsin (örneğin MIT).
