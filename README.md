# PlaneConsole
Genel Bakış
PlaneRez uygulaması, kullanıcılara uçakları, lokasyonları, uçuşları ve rezervasyonları yönetme imkanı sunan konsol tabanlı bir uçuş rezervasyon sistemi olarak tasarlanmıştır. Kullanıcılara uçak ekleme, lokasyon ekleme, uçuş ekleme, rezervasyon yapma gibi çeşitli işlemleri gerçekleştirebilmeleri için basit bir menü tabanlı arayüz sağlar.

İçindekiler
Başlangıç
Önkoşullar
Kurulum
Kullanım
Özellikler
Dosya Yapısı
Katılım
Lisans
Kullanım
Uygulamayı derlenmiş ikiliyi çalıştırarak veya geliştirme ortamınızın "Çalıştır" komutunu kullanarak başlatın. Uygulama, uçakları, lokasyonları, uçuşları ve rezervasyonları yönetme seçeneklerini içeren bir menü sunacaktır.

Ana Menü Seçenekleri:
Uçak Ekle

Sisteme yeni bir uçak eklemenizi sağlar.
Lokasyon Ekle

Sisteme yeni bir lokasyon eklemenizi sağlar.
Uçuş Ekle

Yeni bir uçuş eklemek için kılavuz sağlar, kalkış ve varış lokasyonlarını, zamanı ve ilişkilendirilmiş uçağı belirtir.
Belirtilen uçak modelinin varlığını kontrol eder ve bulunursa uçuş ekler.
Uçuş verilerini bir JSON dosyasına kaydeder.
Rezervasyon Yap

Müşteri bilgilerini (ad, soyad, yaş) ve uçuş zamanını yakalar.
Belirtilen uçuşun koltuklarının müsait olup olmadığını kontrol eder.
Rezervasyonu ekler ve ilişkili uçağın koltuk kapasitesini günceller.
Rezervasyon verilerini bir JSON dosyasına kaydeder.
Özellikler
Uçak Ekle:

Uçak modeli, marka, seri numarası ve koltuk kapasitesi gibi uçakla ilgili bilgileri toplar.
Uçak verilerini bir JSON dosyasına kaydeder.
Lokasyon Ekle:

Ülke, şehir, havaalanı ve aktif durum gibi lokasyonla ilgili bilgileri alır.
Lokasyon verilerini bir JSON dosyasına kaydeder.
Uçuş Ekle:

Kalkış ve varış lokasyonlarını, zamanı ve uçak modelini belirterek yeni bir uçuş eklemenize rehberlik eder.
Belirtilen uçak modelinin varlığını kontrol eder ve uçuşu ekler.
Uçuş verilerini bir JSON dosyasına kaydeder.
Rezervasyon Yap:

Müşteri bilgilerini (ad, soyad, yaş) ve uçuş zamanını yakalar.
Belirtilen uçuşun koltuklarının müsait olup olmadığını kontrol eder.
Rezervasyonu ekler ve ilişkili uçağın koltuk kapasitesini günceller.
Rezervasyon verilerini bir JSON dosyasına kaydeder.
Dosya Yapısı
PlaneRez:

Ana uygulama mantığını içeren Program.cs dosyasını içerir.
PlaneRez.Services:

FileService sınıfını içerir, bu sınıf dosya işlemleri için hizmet sağlar.
