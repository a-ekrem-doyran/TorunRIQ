# 🕒 TorunRIQ
### Torun - Reminder Intelligence Quotient
"A Optimized, reminder and clock system designed for visually impaired seniors."

## Projenin Doğuşu / The Story
TR: Bu proje, görme engelli ve yaşlı bireylerin günlük hayatta karşılaştığı birkaç soruna pratik ve optimize bir çözüm sunmak amacıyla, ananem için başlatılmıştır.
Günümüzde akıllı telefonlar bu ihtiyacı karşılıyor gibi görünse de, pratik kullanımda yaşlı ve görme engelli bireyler için bazı kritik dezavantajlar barındırmaktadır.

- Neden akıllı telefonlar gibi sistemleri kullanmak yerine böyle ilkel bir cihaz?
Yaşamı boyunca fiziksel ve mekanik cihazlarla etkileşim kurmuş olan yaşlı bireyler, dokunmatik ekranların geri bildirimsiz yapısına adapte olmakta güçlük çekmektedir.
Dokunmatik ekranların hassasiyeti, ses seviyesinin yanlışlıkla kısılması veya konuşma hızının farkında olmadan değiştirilmesi gibi durumlar, cihazı işlevsiz hale getirmektedir.
Sesli asistanlarla yaşanan iletişim kopuklukları, kullanıcıda teknolojik bir zorluk yaratmaktadır.
Sürekli güncellenen yazılımlar ve şarj yönetimi, bu gibi kullanıcılar için akıllı sistemleri karmaşık hale getirmektedir.

TorunRIQ, bu karmaşayı ortadan kaldırarak; 
ayarı bozulmayan, fiziksel etkileşime dayalı ve tamamen bu amaca yönelik optimize yardımcı teknoloji olarak tasarlanmıştır.

## Özellikler / Features
- Sesli Saat (Talking Clock)
- Namaz Vakitleri (Prayer Times)
- Sağlık Hatırlatıcıları (Health Reminders)
- Taşınabilirlik (Portability)

## Donanım / Hardware
Projenin kalbinde şu bileşenler yer alıyor:
The project's current figures are as follows:

- Controller: Arduino Nano
- Time Keeping: DS3231 Precision RTC Module
- Audio: DFPlayer Mini (MP3-TF-16P) + 3W Speaker
- Power: 18650 Li-ion Battery + TP4056 Charger + MT3608 Boost Converter

## Dosya Yapısı / Project Structure
- /src: Arduino kaynak kodları / source codes (.ino)
- /audio: SD kart ses dosyası örnekleri / audio file samples
- /docs: Devre şemaları ve bağlantı rehberleri / Circuit diagrams and connection guides
