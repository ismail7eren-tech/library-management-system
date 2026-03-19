📚 Kütüphane Yönetim Sistemi (Flask & SQLite)
Bu proje; kitap envanterini tutmak, üye kayıtlarını yönetmek ve ödünç alma/iade süreçlerini dijital ortamda takip etmek için geliştirilmiş bir web uygulamasıdır.

Projenin temel amacı, kütüphane görevlisinin iş yükünü azaltmak ve verilerin (kitap durumu, üye bilgileri vb.) güvenli bir şekilde depolanmasını sağlamaktır.

🚀 Projenin Temel Özellikleri
📊 Canlı İstatistik Paneli
Sistemin en üstünde yer alan panel sayesinde; toplam kaç kitabın kayıtlı olduğunu, kaç aktif üyenin bulunduğunu ve o an kaç kitabın ödünçte (dışarıda) olduğunu anlık olarak görebilirsiniz.

👤 Detaylı Üye ve Kitap Yönetimi
Üye Kaydı: Sadece isim değil; TC Kimlik No ve Telefon numarası gibi gerçek dünya verileriyle kayıt yapılır.

Kitap Yönetimi: Kitap adı ve yazar bilgisiyle sisteme yeni kitaplar dahil edilir.

Durum Takibi: Bir kitap ödünç verildiğinde sistem otomatik olarak durumunu "Ödünç" olarak günceller ve tekrar verilmesini engeller.

📥 Ödünç ve İade Döngüsü
Ödünç verme ekranında sadece kütüphanede o an "Mevcut" olan kitaplar listelenir.

Kitap iade edildiğinde, tek tıkla ödünç listesinden düşer ve kitap tekrar "Mevcut" hale gelir.

🛠️ Teknik Detaylar
Bu proje modern ve hafif bir teknoloji yığını (stack) üzerine inşa edilmiştir:

Backend: Python dilinin popüler mikro-framework'ü olan Flask kullanılmıştır. Tüm yönlendirmeler ve veritabanı sorguları burada yönetilir.

Veritabanı: İlişkisel veri saklama için SQLite3 tercih edilmiştir. Kurulum gerektirmez ve verileri dosya bazlı saklar.

Frontend: Arayüz için standart HTML5 ve modern CSS3 kullanılmıştır. Tasarım, kullanıcıyı yormayan sade bir yapıdadır.

Dinamik Veri: Python tarafındaki veriler, Jinja2 motoru aracılığıyla HTML şablonlarına aktarılır.

Çalıştırma Komutu
py app.py
