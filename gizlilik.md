---
title: USB e-İmza Girişi — Gizlilik Politikası
---

# Gizlilik Politikası

Son güncelleme: 16 Eylül 2026

**USB e-İmza Girişi** uygulaması kişisel veri **toplamaz, saklamaz ve üçüncü taraflara aktarmaz.** Uygulamanın kendi sunucusu yoktur; analitik, reklam veya çökme raporlama SDK'sı içermez.

## İşlenen veriler ve nereye gittiği
- **Kart PIN'i:** Yalnız cihaza takılı akıllı karta gönderilir. Bellekte tutulmaz, kaydedilmez, hiçbir ağa gönderilmez; imza işlemi biter bitmez silinir.
- **Sertifika ve T.C. Kimlik Numarası:** Karttaki nitelikli sertifikadan okunur ve yalnız sizin seçtiğiniz portalın (UYAP, e-Devlet, UETS, PTT KEP) kendi giriş servisine, o portalın protokolü gereği gönderilir. Uygulama ekranında kimlik numarası maskelenir.
- **İşlem kodu ve imzalanan metin:** Portal sayfasından okunur ve yalnız aynı portala geri gönderilir.
- **Belge imzalama (UDF):** Seçtiğiniz belge cihazda imzalanır ve yeni dosya olarak yine sizin seçtiğiniz yere kaydedilir. Belge hiçbir sunucuya gönderilmez.

## Ağ iletişimi
Uygulama yalnız sizin seçtiğiniz portalın alan adlarına, yalnız sizin tetiklediğiniz anda (İşlemi getir / İmzala) bağlanır. Otomatik veya arka planda istek yapmaz. Çerez ve önbellek tutulmaz.

## Üçüncü taraflar
Portallar ilgili kurumlar tarafından işletilir; o sitelerdeki veri işleme kurumların kendi gizlilik politikalarına tabidir. Uygulama bu kurumlarla bağlantılı değildir ve onları temsil etmez.

## İletişim
[GitHub Issues](https://github.com/saidsurucu/usb-eimza-girisi/issues)
