# Uzay Savaşı 2D

**[▶ Oyna](https://claude.ai/artifact/GXjc7JFcHrf8eH5HSg49YQ)** · GitHub Pages açıksa: https://hamikumbasae.github.io/uzay-savasi/

Hikâye modu, endless mod ve XP sistemiyle 2D uzay savaşı. Tarayıcıda oynanır; bilgisayarda da telefonda da çalışır, kurulum gerekmez.

## Özellikler

- Beş bölümlük hikâye modu ve sonsuz Endless modu
- Oyuncu seviyesi ve XP: seviye atladıkça çift mermi, üçlü mermi, lazer ve takip füzesi açılır
- Normal, hızlı, zırhlı, zikzak ve ateşçi düşmanlar; her bölüm sonunda boss
- Dört farklı gemi, coin ile kalıcı geliştirmeler, üç zorluk seviyesi
- Güçlendirmeler, mega bomba, patlama ve ekran sarsıntısı efektleri

## Kontroller

| | Bilgisayar | Telefon |
|---|---|---|
| Hareket | `WASD` / ok tuşları | Parmakla sürükle |
| Ateş | `SPACE` | Parmak ekrandayken otomatik |
| Mega bomba | `B` | Sağ alttaki `B` düğmesi |
| Duraklat | `P` | Sağ üstteki `II` düğmesi |
| Ses | `M` | Menüden |
| Menüye dön | `ESC` | Ekrandaki düğmeler |

İlerleme ve skorlar tarayıcıda saklanır.


## İki sürüm

- **Web sürümü** (`index.html`, `css/`, `js/`): tarayıcıda, bilgisayarda ve telefonda oynanır. Kurulum gerekmez. Telefonda parmakla sürükle, ateş otomatik; `II` duraklatır, `B` bomba atar. Kayıtlar tarayıcıda tutulur.
- **Java sürümü** (`src/main/java/uzaysavasi/`, `pom.xml`): Java Swing masaüstü uygulaması. Çalıştırmak için: `mvn package` ve ardından `java -cp target/classes uzaysavasi.Main`. Kayıtlar `~/.uzay_savasi_2d` klasöründe tutulur.

İki sürüm aynı oyun kurallarını kullanır. (Eski `uzay-savasi-2d` deposu bu depoyla birleştirildi.)
