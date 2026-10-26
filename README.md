# Ytranslator v1.4 - Windows Hızlı ve Akıllı Çeviri Asistanı

<p align="center">
  <img src="https://raw.githubusercontent.com/yunusbbayram/Ytranslator/main/globe_icon.png" alt="Ytranslator Logo" width="100" />
</p>

<p align="center">
  <strong>Windows 10 ve Windows 11 için Ultra Hızlı, Pano Korumalı, 7 Çeviri Modlu ve Yapay Zekâ Destekli Masaüstü Çeviri Asistanı</strong>
</p>

<p align="center">
  <a href="https://github.com/yunusbbayram/Ytranslator/releases/latest"><img src="https://img.shields.io/github/v/release/yunusbbayram/Ytranslator?color=38bdf8&label=S%C3%BCr%C3%BCm&logo=github" alt="GitHub Release"></a>
  <img src="https://img.shields.io/badge/Platform-Windows%2010%20%7C%2011%20(64--bit)-0078d4?logo=windows" alt="Platform">
  <img src="https://img.shields.io/badge/Diller-93%20Dil%20Destekli-34d399" alt="93 Dil">
  <img src="https://img.shields.io/badge/RAM%20Kullan%C4%B1m%C4%B1-~50%20MB-blue" alt="RAM Usage">
  <img src="https://img.shields.io/badge/Lisans-%C3%9ccretsiz%20%26%20A%C3%A7%C4%B1k%20Kaynak-purple" alt="License">
</p>

---

## 📌 İçindekiler
- [Hakkında](#-hakk%C4%B1nda)
- [İndirme Bağlantıları (v1.4)](#-i%CC%87ndirme-ba%C4%9Flant%C4%B1lar%C4%B1-v14)
- [v1.4 ile Eklenen Yeni Özellikler](#-v14-ile-eklenen-yeni-%C3%B6zellikler)
- [7 Standart Çeviri Gösterim Modu](#-7-standart-%C3%A7eviri-g%C3%B6sterim-modu)
- [6 Çeviri Tetikleme Yöntemi](#-6-%C3%A7eviri-tetikleme-y%C3%B6ntemi)
- [Öne Çıkan Başlıca Yetenekler](#-öne-%C3%A7%C4%B1kan-ba%C5%9Fl%C4%B1ca-yetenekler)
- [Klavye Kısayolları](#-klavye-k%C4%B1sayollar%C4%B1)
- [Kaynak Koddan Çalıştırma ve Derleme](#-kaynak-koddan-%C3%A7al%C4%B1%C5%9Ft%C4%B1rma-ve-derleme)
- [Sıkça Sorulan Sorular (SSS)](#-s%C4%B1k%C3%A7a-sorulan-sorular-sss)
- [Geliştirici & İletişim](#-geli%C5%9Ftirici--i%CC%87leti%C5%9Fim)

---

## 📖 Hakkında

**Ytranslator**, geleneksel web çeviri sayfalarına gitme, kopyala-yapıştır yapma ve sekme değiştirme zahmetini tamamen ortadan kaldıran bağımsız bir Windows masaüstü çeviri aracıdır. 

PDF okurken, Chrome/Edge tarayıcısında gezinirken, Word belgesinde çalışırken veya herhangi bir masaüstü uygulamasında metin seçtiğiniz anda çeviri anında yanınızda belirir veya doğrudan seslendirilir. 

Tıpkı *voidtools Everything* felsefesinde olduğu gibi asgari sistem kaynağı kullanımı ilkesiyle geliştirilmiştir; boşta beklerken %0 CPU ve ortalama yalnızca ~50 MB RAM tüketir.

---

## 📥 İndirme Bağlantıları (v1.4)

| Dosya | Tür | Açıklama |
| :--- | :--- | :--- |
| [**Ytranslator_Setup_v1.4.exe**](https://github.com/yunusbbayram/Ytranslator/releases/download/v1.4/Ytranslator_Setup_v1.4.exe) | **Kurulum Sürümü (Setup)** | Inno Setup ile 48 dilde otomatik işletim sistemi dilini algılayan sihirbaz. Masaüstü kısayolu, Başlat menüsü ve Windows ile başlatma ayarlarını otomatik yapar. |
| [**Ytranslator.exe**](https://github.com/yunusbbayram/Ytranslator/releases/download/v1.4/Ytranslator.exe) | **Taşınabilir Sürüm (Portable)** | Kurulum gerektirmez, yönetici izni istemez. USB belleklerde taşınabilir ve çift tıklamayla doğrudan çalışır. |

---

## 🚀 v1.4 ile Eklenen Yeni Özellikler

1. **7 Standart Çeviri Gösterim Modu:** Tüm arayüzde standartlaştırılmış 7 farklı çalışma modu (*Popup, Popup + Sesli, Popup Minimal, Popup Minimal + Ses, Çeviri Penceresi, Sesli, Sesli Play*).
2. **Tekrar Çeviri (Re-Translate / 3. Çeviri Kartı):** Çeviri Penceresi'nde hedef dildeki metni tekrar orijinal kaynak dile (Türkçe'ye) geri tercüme eden 3. panel; çevirinin doğruluğunu ve deyim sağlamasını yapmanızı sağlar.
3. **Akıllı Çift Dilli Takas ve Sistem Diline Dönüş (Smart Auto-Switch):** Hedef dil ile seçilen kaynak metin aynıysa alternatif dile (İngilizce); metin alternatif dille de aynıysa otomatik olarak Windows sistem diline (Türkçe) dönerek metnin tekrarlanmasını engeller.
4. **Mod 6 (Sesli) ve Mod 7 (Sesli Play) Ayrımı:**
   - *Mod 6 (Sesli):* Metin seçildiği anda otomatik telaffuz başlar, play butonu ve minimal popup varsayılan olarak kapalıdır; sağ üstteki `[✕]` ile hemen durdurulabilir.
   - *Mod 7 (Sesli Play):* Metin seçilince yeşil **Play (▶)** butonu aktif olur. Basıldığında sesli okur ve altta minimal popup açılır. Okuma esnasında kırmızı **Stop (■)** butonuna dönüşerek sesi anında durdurma imkânı sunar. İlk açılışta ekranın tam merkezinde 1 saniye yumuşakça yanıp söner ve raptiye (📌) ile pinlenebilir.
5. **Dinamik Okuma Süresi (Akıllı Kapanma Zamanı):** Popup ve Minimal Popup'ların ekranda kalma süresi sabit saniyeler yerine seçilen metnin kelime ve karakter uzunluğuna göre dinamik hesaplanır (4 sn ila 35 sn).
6. **Güçlendirilmiş Sol Çift Tık Motoru:** Windows düşük seviyeli fare kancası (mouse hook) optimize edilerek ardışık çift tıklamalarda oluşan algılama kaçırma sorunu tamamen çözülmüş, %100 kararlılık sağlanmıştır.
7. **Çeviri Penceresinde Satır Katlama (Word-Wrap):** Uzun paragraflar yapıştırıldığında yatay kaydırma çubuğu çıkması engellenmiş, metinler otomatik olarak alta katlanıp ferah bir dikey kaydırma sunulmuştur.
8. **Varsayılan Ayarlara Sıfırla (Reset) & Koyu Temalı Onay Penceresi:** Ayarları fabrika değerlerine döndüren buton ve koyu cam temalı özel onay popup'ı eklenmiştir.
9. **93 Dilde %100 Eksiksiz Yerelleştirme:** Sistem tepsisi menüsü, Ayarlar, Çeviri Penceresi, tüm tooltip'ler ve sistem tepsisindeki "Hakkında" penceresinin detaylı içeriği 93 dilde eksiksiz tercüme edilmiştir.
10. **CJK (Çince, Japonca, Korece) Tipografi İyileştirmesi:** Doğu Asya logografik alfabeleri için font ağırlıkları dengelenmiş, `Microsoft YaHei` ve `PingFang SC` font aileleriyle kristal netliğinde tipografi sağlanmıştır.

---

## 🎛️ 7 Standart Çeviri Gösterim Modu

| No | Mod Adı | Çalışma Prensibi | En Uygun Senaryo |
| :---: | :--- | :--- | :--- |
| **1** | **Popup (Varsayılan)** | Seçimin yanında açılan zarif, pinlenebilir, kopyalama, dinleme ve mikrofonlu yüzen pencere. | Web okumaları, makale taramaları ve kelime incelemeleri. |
| **2** | **Popup + Sesli** | Hem açılır popup görüntülenir hem de çevrilen metin aynı anda hoparlörden seslendirilir. | Yabancı dil öğrenenler, telaffuz ve yazılışı eş zamanlı takip edenler. |
| **3** | **Popup Minimal** | Butonsuz, ultra sade, yalnızca çeviri metnini gösteren kompakt kutucuk. Sağ üstteki `[✕]` butonuyla kapatılabilir. | Dikkat dağıtmadan hızlıca çeviriyi görüp okumaya devam etmek isteyenler. |
| **4** | **Popup Minimal + Ses** | Kompakt minimal metin kutusu açılırken çeviri aynı zamanda seslendirilir. | Sade görünüm eşliğinde işitsel çeviri deneyimi. |
| **5** | **Çeviri Penceresi** | Bağımsız çift panelli stüdyo, sözlük detayları, yazı boyutu ölçekleme ve 3. panel **Tekrar Çeviri (Re-Translate)** desteği. | Uzun metinler, e-posta tercümeleri ve detaylı çalışma seansları. |
| **6** | **Sesli (Normal)** | Ekranda büyük pencere açılmaz; seçim yapıldığı anda altta hoparlör açılır ve anında seslendirir. | Ekranı kaplamadan kulaklıkla sadece dinlemek isteyenler. |
| **7** | **Sesli Play** | Metin seçildiğinde yeşil **Play (▶)** aktif olur. Basıldığında seslendirilir ve altta minimal kart açılır; çalarken kırmızı **Stop (■)** butonuna dönüşür. | Her seçimde otomatik ses çıkmasını istemeyen, kontrollü dinlemek isteyenler. |

---

## 🎯 6 Çeviri Tetikleme Yöntemi

Ayarlar panelinden veya sistem tepsisinden çevirinin hangi hareketle başlatılacağını belirleyebilirsiniz:
1. **Tuşsuz (Seçimde / Fare Bırakıldığında):** Farenizle metni tarayıp bıraktığınız anda çeviri tetiklenir.
2. **Sol Çift Tık (Kelime Seçimi):** Herhangi bir kelimeye fare sol tuşuyla çift tıklandığında anında tercüme edilir.
3. **Çift Ctrl:** `Ctrl` tuşuna peş peşe 2 kez hızlıca basıldığında seçili metin çevrilir.
4. **Seçim + Ctrl:** `Ctrl` tuşu basılı tutularak metin seçildiğinde tetiklenir.
5. **Seçim + Alt:** `Alt` tuşu basılı tutularak metin seçildiğinde tetiklenir (tarayıcılarda menü odağı kaybını engelleyen donanım filtresi mevcuttur).
6. **Seçim + Shift:** `Shift` tuşu basılı tutularak metin seçildiğinde tetiklenir.

---

## 🌟 Öne Çıkan Başlıca Yetenekler

### 🖱️ Çift Sağ Tık Menüsü (Context Menu)
- Windows'ta herhangi bir metin seçilip **peş peşe iki kez sağ tıklandığında** imlecin yanında modern koyu temalı Ytranslator menüsü açılır:
  - 📋 *Metni Kopyala*
  - 🔊 *Sesli Çevir*
  - ⚡ *Çeviri Penceresi ile Çevir*
  - 💬 *Popup Translator ile Çevir*
  - 🌐 *Hedef Dil Açılır Menüsü (16 popüler ve 90+ dil)*
- **Windows Standart Menüsüne Saygı:** Tek sağ tık tamamen Windows'a aittir; Windows'un kendi kopyala-yapıştır menüsü asla ezilmez.

### 🛡️ Gelişmiş Pano (Clipboard) Koruması
- Ytranslator seçili metni elde etmek için arka planda hızlı bir kopyalama simülasyonu yaparken, panonuzdaki mevcut verileri (önceden kopyalanmış metin, görsel veya dosya bağlantıları) işlem öncesinde belleğe yedekler ve çeviri metnini aldıktan sonra panoyu anında orijinal haline geri yükler. Panonuz asla bozulmaz.

### 🌐 93 Dil, Orijinal Alfabeler ve Tam Arayüz Çevirisi
- Google Translate altyapısındaki tam **93 dil** eksiksiz desteklenir.
- Tüm diller kendi orijinal alfabeleriyle listelenir (`العربية`, `Русский`, `简体中文`, `हिन्दी`, `Ελληνικά`, `한국어`, `日本語` vb.).
- Arapça, Farsça, İbranice ve Urduca gibi diller seçildiğinde pencereler otomatik olarak **RTL (Right-to-Left)** moduna geçer.
a
### ⚡ 0 Milisaniye SHA-256 Önbellek
- Gün içinde sıkça baktığınız kelimeler bellek içinde SHA-256 hash özetleriyle saklanır. İkinci kez seçildiğinde internete çıkmadan **0.0 milisaniyede** önbellekten ekrana gelir.

### ✨ Google Gemini (AI) Entegrasyonu
- Gemini API anahtarı girmek **zorunlu değildir**; Google Translate varsayılan olarak ömür boyu sınırsız ve ücretsizdir.
- Dileyen kullanıcılar Google AI Studio'dan aldıkları ücretsiz API anahtarını girerek Gemini motorunu aktif edebilir:
  - **Dinamik Model Keşfi:** Kod içerisine model adı sabitlenmez; hesabınızdaki en yeni modeller (`gemini-2.5-flash`, `flash-lite` vb.) dinamik olarak keşfedilir.
  - **Sıfır Düşünme Gecikmesi (`thinkingBudget = 0`):** Modelin gereksiz akıl yürütme beklemesi engellenerek popup yanıt hızı yarı yarıya düşürülür.
  - **HTTP 429 Kota Aşımı Koruması (Fallback):** Dakikalık kota dolarsa otomatik olarak sıradaki modele, gerekirse Google Translate'e geçerek çevirinin kesintisiz sürmesini sağlar.

### 🌐 Chrome ve Edge Sağ Tık Eklentisi
- Kurulum dizininde yer alan `chrome_extension` klasörü Chrome/Edge'de "Geliştirici modu" ile yüklenerek tarayıcının kendi sağ tık menüsüne doğrudan Ytranslator alt menüleri eklenebilir.

---

## ⌨️ Klavye Kısayolları

| Kısayol | İşlev |
| :--- | :--- |
| `Alt + Q` | Seçili metni anında çevirir ve varsayılan modda gösterir. |
| `Alt + W` | Bağımsız Çeviri Penceresi'ni açar veya gizler. |
| `Esc` | Açık olan tüm çeviri pencerelerini ve popup'ları derhal kapatır; çalan sesi susturur. |

---

## 💻 Kaynak Koddan Çalıştırma ve Derleme

### Gereksinimler
- Python 3.10 veya üzeri (64-bit Windows)
- Git

### Kurulum Adımları
```powershell
# 1. Depoyu klonlayın
git clone https://github.com/yunusbbayram/Ytranslator.git
cd Ytranslator

# 2. Gerekli kütüphaneleri yükleyin
pip install -r requirements.txt

# 3. Uygulamayı başlatın
python main.py
```

### Exe Olarak Derleme (PyInstaller)
```powershell
pyinstaller Ytranslator.spec
```
Derlenen çalıştırılabilir dosya `dist/Ytranslator.exe` dizininde oluşturulur.

---

## ❓ Sıkça Sorulan Sorular (SSS)

Detaylı sorular, ayar rehberleri ve sorun giderme adımları için [Sıkça Sorulan Sorular (SSS) Sayfasını](https://ytranslatorpro.blogspot.com/p/sss.html) veya proje içindeki [blogger_sss_sayfasi.html](file:///d:/Projeler/Ytranslate/blogger_sss_sayfasi.html) belgesini inceleyebilirsiniz.

---

## 👨‍💻 Geliştirici & İletişim

- **Geliştirici:** Yunus Büyükbayram (📍 Konya - Türkiye)
- **Resmi Web Sitesi:** [ytranslatorpro.blogspot.com](https://ytranslatorpro.blogspot.com/p/ytranslator-1.html)
- **Geliştirici Web Sitesi:** [yunusbuyukbayram.blogspot.com](https://yunusbuyukbayram.blogspot.com/)
- **E-Posta:** [yunusbbayram@gmail.com](mailto:yunusbbayram@gmail.com)

> 🤲 *"Bu küçük araç işinizi kolaylaştırdıysa, bir 'Allah razı olsun' deseniz yeter."*
