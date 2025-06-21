
README.txt - Plantguru Bitki Takip Sistemi

PROJE ADI: Plantguru – Bitki Takip Asistanı
DERS: Web Teknolojileri Dersi
YAPANLAR:
- Alper Nafiz Alp
- Ömer Kavak
- Talha Mete Yılmaz
- Yusuf Buğra Yazar

1. PROJENİN AMACI

Bu projenin amacı, kullanıcıların evde veya iş yerinde yetiştirdikleri bitkilerin bakım süreçlerini daha düzenli ve kolay bir şekilde takip etmelerini sağlayacak, sezgisel ve kullanıcı dostu bir web uygulaması geliştirmektir.

Günümüzde bitki yetiştiren bireylerin en sık karşılaştığı sorunlardan biri, bitkilerin düzenli sulanması, gübrelenmesi veya kontrolünün unutulmasıdır. "Plantguru" bu sorunu çözmek için geliştirilmiş bir bitki takip asistanıdır.

Bu sistem ile kullanıcılar, sahip oldukları bitkileri web tarayıcısı üzerinden sisteme ekleyebilir, her bir bitkinin sulama ve gübreleme zamanını takip edebilir, gerektiğinde bitkileri sistemden kaldırabilir veya güncelleyebilir.

Mobil uyumlu olması sayesinde kullanıcılar yalnızca masaüstü değil, mobil cihazlardan da siteye erişebilir. Basit ama etkili kullanıcı arayüzüyle hem yeni başlayanlar hem de deneyimli kullanıcılar için uygundur.

2. KULLANILAN TEKNOLOJİLER

Proje tamamen istemci tarafında çalışan modern web teknolojileriyle geliştirilmiştir:

- HTML5 → Sayfa yapısını oluşturmak için kullanılmıştır.
- CSS3 → Arayüzün tüm görsel tasarımı, responsive yapı, mobil uyumluluk ve tüm kart, buton, form elementlerinin stilleri bu teknolojiyle oluşturulmuştur.
- JavaScript (Vanilla JS) → Bitki ekleme, silme, sulama, gübreleme, localStorage yönetimi gibi tüm interaktif özellikler tamamen saf JavaScript ile yazılmıştır.
- LocalStorage API → Kullanıcının eklediği bitkiler ve işlemleri tarayıcı belleğinde saklamak için kullanılmıştır. Böylece kullanıcı verileri kalıcı hale gelir.

3. PROJE ÖZELLİKLERİ

🔹 Bitki Ekleme
Kullanıcı, "Bitki Ekle" butonuna tıklayarak çıkan form aracılığıyla yeni bitkiler sisteme ekleyebilir. Bu işlem sırasında bitki ismi zorunlu, görsel URL’si ise isteğe bağlıdır. Görsel girilmezse varsayılan arka plan rengi atanır.

🔹 Sulama & Gübreleme
Her bitki kartında bulunan “Sula” ve “Güb.” butonları sayesinde kullanıcılar ilgili işlemi yaptığında sistem durumu günceller:
Örn: “Son sulama şimdi” olarak güncellenir.

🔹 Bitki Silme
Kart üzerindeki “Sil” butonu ile kullanıcı eklediği bitkileri anında sistemden kaldırabilir. Eğer tüm bitkiler silinirse, sistem otomatik olarak "Henüz hiç bitki eklemediniz" mesajını gösterir.

🔹 Bitki Kartları Dinamik
Eklenen her bitki için DOM üzerinde yeni bir kart oluşturulur. Kart içerisinde şunlar yer alır:
- Bitki adı
- Görsel (URL ile belirlenir)
- Son sulama ve gübreleme zamanı
- Butonlar: “Sula”, “Güb.”, “Sil”

🔹 Sıkça Sorulan Sorular (FAQ)
Kullanıcılar için tasarlanmış SSS bölümü, interaktif olarak açılır-kapanır kutucuklarla sunulur. Kullanıcının anlamadığı noktalar açıklanır.

🔹 Mobil Uyumluluk
Tüm tasarım responsive olacak şekilde kodlanmıştır. Mobilde hamburger menü, buton boyutları ve içerik yerleşimleri mobil ekranlara göre optimize edilmiştir.

🔹 Görsel Kalite & Marka Kimliği
- Ana sayfada özel illüstrasyonlar, Türkiye bayrağı simgesi ve farklı UI kutuları yer alır.
- Kullanılan ikonlar (örneğin Instagram SVG) modern ve minimalisttir.
- Özel logo (logo-plantguru 1.svg) projeye profesyonel bir kimlik kazandırır.

4. KOD YAPISI VE DOSYALAR

📁 index.html
Tüm sayfa iskeletini içerir. Header, Hero, Bitkilerim, SSS ve Footer bölümleri HTML5 standartları ile yapılandırılmıştır.

📁 style.css
Projenin tüm stil dosyası. Renk paletleri, buton geçişleri, responsive tasarım detayları burada yer alır.

📁 script.js
Tüm interaktif işlemler buradadır: Bitki ekleme, silme, işlem butonları, localStorage yönetimi ve dinamik DOM oluşturma.

5. GELECEKTEKİ GELİŞTİRMELER

- 🔔 Hatırlatma Bildirimleri: Bitki sulama/gübreleme zamanları geldiğinde kullanıcıya otomatik uyarı
- 📅 Zaman Takibi: Saat/gün bazlı geçmiş izleme
- 👥 Kullanıcı Girişi: Her kullanıcıya özel sistem
- ☁️ Sunucuya Bağlantı: Firebase veya benzeri servisle veri senkronizasyonu
- 📱 Mobil Uygulama: PWA olarak geliştirilebilir

6. SONUÇ

"Plantguru", bireysel bitki severler ve küçük işletmeler için tasarlanmış pratik ve kullanıcı dostu bir sistemdir. Kolay kullanımı, verilerin localStorage’da saklanması ve sezgisel arayüzü ile dikkat çeker. Gelecekte yapılacak geliştirmelerle sistem daha profesyonel hale gelebilir.

Tarih: Haziran 2025
Proje Ekibi: Yusuf Buğra Yazar, Alper Nafiz Alp, Talha Mete Yılmaz, Ömer Kavak
