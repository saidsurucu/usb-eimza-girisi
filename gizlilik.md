---
title: USB e-İmza Girişi — Gizlilik Politikası
---

# Gizlilik Politikası

Son güncelleme: 7 Kasım 2026 · iPhone/iPad ve Android sürümleri için geçerlidir.

**USB e-İmza Girişi** uygulaması kişisel veri **toplamaz ve geliştiriciye hiçbir veri iletmez.** Uygulamanın kendi sunucusu yoktur; analitik, reklam veya çökme raporlama SDK'sı içermez.

## İşlenen veriler ve nereye gittiği
- **Kart PIN'i:** Yalnız cihaza takılı akıllı karta gönderilir. Kaydedilmez, hiçbir ağa gönderilmez, günlüğe yazılmaz; imza işlemi biter bitmez bellekten silinir. PIN her zaman uygulamanın kendi ekranında sorulur, portalın web sayfasına yazılmaz.
- **Sertifika ve T.C. Kimlik Numarası:** Karttaki nitelikli sertifikadan okunur ve yalnız sizin seçtiğiniz portalın kendi giriş servisine, o portalın protokolü gereği gönderilir. Uygulama ekranlarında kimlik numarası maskelenir.
- **İşlem kodu ve imzalanan içerik:** Portal sayfasından ya da portalın imza isteğinden alınır, kartla imzalanır ve yalnız aynı portala geri gönderilir. İmzalanacak içerik imzadan önce ekranda gösterilir.
- **Belge imzalama (UDF ve PDF):** Seçtiğiniz belge cihazda okunur ve imzalanır; sonuç yeni dosya olarak sizin seçtiğiniz yere kaydedilir. Kaynak dosyaya yazılmaz. Belge hiçbir sunucuya gönderilmez.
- **Portaldan indirilen belgeler:** Portalın indirmenize sunduğu belgeler yalnız uygulamanın kendi geçici alanında tutulur; siz "Kaydet" ya da "Belge İmzala'da aç" demedikçe başka yere gitmez ve uygulamanın bir sonraki açılışında silinir.

## Desteklenen portallar
Uygulama içinde açılan portallar: avukat portalı, merkezi kamu hizmet kapısı (ve ona bağlı hizmetler), ulusal elektronik tebligat sistemi, kayıtlı elektronik posta (KEP) web postası, hekimler için e-reçete portalı, sosyal güvenlik kurumunun çevrim içi hizmetleri ve (iPhone/iPad'de) kurum içi elektronik belge yönetim sistemleri. Hangi portallara bağlanılacağı uygulamaya gömülüdür; başka uygulamalardan ya da bağlantılardan gelen bir adres kabul edilmez. Yalnız belge yönetim sisteminde kurumunuzun `gov.tr` adresini kendiniz yazabilirsiniz.

## Ağ iletişimi
- Uygulama yalnız sizin seçtiğiniz portalın alan adlarına ve yalnız sizin tetiklediğiniz anda bağlanır. Otomatik veya arka planda istek yapmaz.
- Uygulamanın kendi gönderdiği imza istekleri çerez ve önbellek kullanmaz.
- Portal sayfaları uygulama içindeki tarayıcıda açılır. Her tarayıcıda olduğu gibi portalın oturum çerezleri cihazda, uygulamanın kendi özel alanında saklanabilir; uygulamayı kaldırdığınızda silinir.
- Kart okuyucuyla iletişim USB üzerinden, cihazın içinde yapılır.

## Üçüncü taraflar
Portallar ilgili kurumlar tarafından işletilir; o sitelerdeki veri işleme kurumların kendi gizlilik politikalarına tabidir. Uygulama bu kurumlarla bağlantılı değildir ve onları temsil etmez.

## İletişim
[GitHub Issues](https://github.com/saidsurucu/usb-eimza-girisi/issues)
