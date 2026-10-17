# ⚡ Görev 7: Gömülü Sistemler ve Araç İçi İletişim Mimarisi

## 🎯 Amaç
Gömülü sistemler; bir Formula Student yarış aracının beyni ve sinir sistemidir. Sensörlerden gelen verilerin gerçek zamanlı toplanması, kritik güvenlik kararlarının mikrosaniyeler içinde verilmesi ve aktüatörlerin kararlı şekilde sürülmesi bu sistemlerin sorumluluğundadır.

Bu görevde amacımız; 1.5 Adana Formula Student takımımıza yeni katılan gömülü sistemler üyelerimizin bir yarış aracındaki donanım ve yazılım mimarisini kavraması, araç içi haberleşme protokollerini (özellikle CAN-Bus), Formula Student kural kitapçığındaki kritik yazılımsal güvenlik isterlerini, sensör-mikrodenetleyici etkileşimini ve sürücü gösterge (dashboard) arayüzünü araştırmasıdır. Neleri araştıracağınıza ve sunumunuzda hangi konuları derinleştireceğinize büyük ölçüde kendiniz karar vereceksiniz.

## 🛠️ İstenen İçerik: Sunum Akışı
Sunumunuzda aşağıdaki ana başlıkları bir çerçeve olarak ele almanız beklenmektedir. Sunum süresi **10-15 dakikayı** geçmemelidir.

### Bölüm 1: Gömülü Sistemlere Giriş, Takım İçi Görevler ve Haberleşme
- Gömülü sistem nedir ve bir yarış aracındaki temel rolü nedir?
- Formula Student takımında Gömülü Sistemler (Embedded Systems) birimi üyelerinin görev ve sorumlulukları
- Otomotivde kullanılan temel haberleşme protokolleri (UART, SPI, I2C, CAN vb.)
- Formula Student yarış aracımızda neden CAN-Bus protokolünü tercih ediyoruz/kullanacağız? Avantajları nelerdir?

### Bölüm 2: Formula Student Kuralları ve Kritik Yazılımsal Güvenlik
- Formula Student kural kitapçığının (FS Rules) yazılımsal ve elektriksel güvenlik gereksinimleri
- **System Critical Signals (SCS):** Sistem kritik sinyalleri nedir, arıza/kopma anında nasıl yönetilmelidir?
- **APPS Plausibility (%10 Kuralı):** Gaz pedalı konum sensörlerinin (APPS) tutarlılık denetimi ve %10 sapma kuralı
- **Fren ve Gaz Çakışması (Brake System Plausibility / Implausibility):** Fren ve gaz pedalına aynı anda basılması durumunda motor gücünün kesilme mantığı ve kuralı

### Bölüm 3: Sensörler, Mikrodenetleyiciler ve Hata Yönetimi
- **Giriş / Çıkış Temelleri:** ADC (Analog-Digital Converter) nedir, analog sensör nasıl okunur, dijital giriş ve çıkışlar (GPIO) nasıl kullanılır?
- **Sinyal İşleme:** Ham ADC verisinin işlenmesi, filtreleme ve elektriksel gürültü engelleme yöntemleri
- **Hata Yönetimi ve Güvenli Durum (Failsafe):** Sensör bağlantısı koparsa, CAN mesajı kaybolursa veya beklenmeyen bir değer gelirse sistem ne yapmalı?

### Bölüm 4: Sürücü Göstergesi ve Arayüzü (Dashboard & Driver Interface)
- Sürücü arayüzü (Driver Interface) nedir ve kokpitte/direksiyonda hangi kritik bileşenler ve bilgiler yer almalıdır?
- Yarış esnasında sürücünün anlık takip etmesi gereken kritik telemetri ve durum verileri (hız, batarya durumu, sıcaklıklar, hata/arıza ikaz ışıkları vb.)
- Sürücü arayüzü ile araç kontrol ünitesi (VCU) arasındaki veri akışı ve ergonomik tasarım prensipleri

## 💡 Ek Katkılar
Yukarıdaki başlıklar sunum için bir çerçeve çizmektedir; sunumunuzu bunlarla sınırlı tutmanız gerekmez. Araştırmanızı gerçek Formula Student teknik kurallarından, otomotiv standartlarından, donanım blok diyagramlarından, akış şemalarından ve kendi teknik yorumlarınızdan örneklerle zenginleştirebilirsiniz.

## 📤 Teslim Formatı
1. Sunumunuzu PDF formatına dönüştürün. Dosya adını aşağıdaki biçimde oluşturun:

   ```
   Gomulu-Birim-[Ad]-[Soyad].pdf
   ```

2. Fork'ladığınız depoda aşağıdaki klasörü oluşturun ve PDF dosyanızı bu klasöre yükleyin:

   ```
   Submissions/Submission-07-Gomulu-Birim-[Ad]-[Soyad]/
   ```

3. Aşağıdaki commit mesajını kullanın:

   ```
   feat: Task-07 gömülü birim sunumu eklendi
   ```

4. Ana depoya bir Pull Request (PR) açın.

