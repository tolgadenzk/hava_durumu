🌦 Hava Durumu Veri Alma Projesi
Bu proje, OpenWeatherMap API kullanarak belirli bir şehrin hava durumu verilerini çeker, analiz eder ve CSV dosyasına kaydeder.

📌 Özellikler
Şehir bazlı hava durumu verisi çekme
Sıcaklık, nem, hissedilen sıcaklık, rüzgar hızı gibi bilgileri gösterme
Verileri CSV dosyasına kaydetme
Verileri grafikler ile analiz etme
🚀 Kurulum
Projeyi klonlayın
bash
Kopyala
Düzenle
git clone https://github.com/tolgadenzk/hava_durumu.git
cd hava_durumu
Gerekli kütüphaneleri yükleyin
nginx
Kopyala
Düzenle
pip install -r requirements.txt
OpenWeatherMap API anahtarınızı ekleyin
config.py dosyasına API anahtarınızı girin.
 Kullanım
Python betiğini çalıştırarak hava durumu verilerini alın:
nginx
Kopyala
Düzenle
python hava_durumu.py
Yeni verileri GitHub'a yükleyin:
sql
Kopyala
Düzenle
git add hava_durumu.csv
git commit -m "Yeni hava durumu verisi eklendi"
git push origin main
📈 Veri Analizi
Projede toplanan hava durumu verileri matplotlib ve pandas kullanılarak analiz edilir.
Örnek grafik: (Buraya grafik görseli ekleyebilirsin)

🤝 Katkıda Bulunma
Eğer projeye katkıda bulunmak istersen:

Depoyu fork'la
Yeni bir özellik ekleyerek PR (Pull Request) aç
 Lisans
Bu proje MIT Lisansı ile lisanslanmıştır.

