Hava Durumu Veri Alma Projesi

Bu proje, OpenWeatherMap API kullanarak belirli şehirlerin hava durumu verilerini çeker, analiz eder ve CSV dosyasına kaydeder.

 Özellikler
	•	Şehir bazlı hava durumu verisi çekme
	•	Sıcaklık, nem, hissedilen sıcaklık, rüzgar hızı gibi bilgileri gösterme
	•	Verileri CSV dosyasına kaydetme
	•	Verileri grafikler ile analiz etme

 Kurulum
	1.	Projeyi klonlayın
 git clone https://github.com/tolgadenzk/hava_durumu.git
cd hava_durumu


2.	Gerekli kütüphaneleri yükleyin
	pip install -r requirements.txt


3.	OpenWeatherMap API anahtarınızı ekleyin
	•	config.py dosyasına API anahtarınızı girin.

 Kullanım
	•	Python betiğini çalıştırarak hava durumu verilerini alın:
 python hava_durumu.py

•	Yeni verileri GitHub’a yükleyin:
git add hava_durumu.csv
git commit -m "Yeni hava durumu verisi eklendi"
git push origin main

Veri Analizi

Projede toplanan hava durumu verileri matplotlib ve pandas kullanılarak analiz edilir.
Örnek grafik: (Buraya grafik görseli ekleyebilirsin)

🤝 Katkıda Bulunma

Eğer projeye katkıda bulunmak istersen:
	1.	Depoyu fork’la
	2.	Yeni bir özellik ekleyerek PR (Pull Request) aç

 Lisans:

Bu proje MIT Lisansı ile lisanslanmıştır.

Bu içeriği README.md dosyana ekleyip kaydedebilirsin.
Eğer GitHub üzerinden eklemek istersen:
	1.	GitHub deposuna gir, “Add a README” butonuna bas.
	2.	Yukarıdaki içeriği kopyalayıp yapıştır.
	3.	“Commit changes” butonuna basarak kaydet.

Veya terminalden düzenlemek istersen:
cho "# Hava Durumu Veri Alma Projesi" > README.md
git add README.md
git commit -m "README dosyası eklendi"
git push origin main
