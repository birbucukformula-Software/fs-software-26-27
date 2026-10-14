# 🤖 Görev 8: Otonom Sürüş Sistemleri ve Teknolojileri

## 🎯 Amaç
Otonom sürüş; sensör teknolojilerinden yapay zekaya, veri işlemeden kontrol teorisine kadar birçok mühendislik disiplininin kesiştiği kapsamlı bir alandır.

Bu görevde amacımız; takımımıza yeni katılan üyelerimizin otonom bir sistemin temel çalışma prensiplerini kavraması, bir aracın çevresini nasıl algıladığını ve bu verilerle nasıl kararlar aldığını araştırmasıdır. Neleri araştıracağınıza ve sunumunuzda hangi konuları derinleştireceğinize büyük ölçüde kendiniz karar vereceksiniz.

## 🛠️ İstenen İçerik: Sunum Akışı
Sunumunuzda aşağıdaki ana başlıkları bir çerçeve olarak ele almanız beklenmektedir. Sunum süresi **10-15 dakikayı** geçmemelidir.

### Bölüm 1: Otonom Sürüşe Giriş ve Otonomi Seviyeleri
- Otonom sistemlerin temel mantığı (Algıla -> Karar Ver -> Uygula / Sense -> Plan -> Act)
- SAE Seviye 0'dan Seviye 5'e otonomi dereceleri ve günümüzdeki durumu

### Bölüm 2: Çevreyi Algılama ve Sensör Teknolojileri (Perception)
- Otonom araçlarda kullanılan temel sensörler (Kamera, LiDAR, Radar vb.) ve çalışma prensipleri
- Sensör füzyonunun (Sensor Fusion) önemi ve Bilgisayarlı Görme (Computer Vision) kavramı

### Bölüm 3: Konumlandırma, Haritalama ve Yol Planlama (Localization & Planning)
- Aracın nerede olduğunu bilmesi: Konumlandırma ve SLAM (Eşzamanlı Konumlandırma ve Haritalama)
- Rota oluşturma ve yol planlama (Path Planning) temelleri

### Bölüm 4: Sistem Mimarisi, Güvenlik ve Tepki Süresi
- Otonom sistemlerde yazılım ve haberleşme altyapısı (örneğin ROS ekosistemi)
- Güvenlik, kararlılık ve gecikme süresinin (Latency / Real-Time) kritik önemi

## 💡 Ek Katkılar
Yukarıdaki başlıklar sunum için bir çerçeve çizmektedir; sunumunuzu bunlarla sınırlı tutmanız gerekmez. Araştırmanızı güncel otonom araç teknolojilerinden (Tesla, Waymo vb.) veya yarış dünyasından (Formula Student Driverless vb.) örneklerle, blok diyagramlarla ve kendi yorumlarınızla zenginleştirebilirsiniz.

## 📤 Teslim Formatı
1. Sunumunuzu PDF formatına dönüştürün. Dosya adını aşağıdaki biçimde oluşturun:

   ```
   Otonom-Birim-[Ad]-[Soyad].pdf
   ```

2. Fork'ladığınız depoda aşağıdaki klasörü oluşturun ve PDF dosyanızı bu klasöre yükleyin:

   ```
   Submissions/Submission-08-Otonom-Birim-[Ad]-[Soyad]/
   ```

3. Aşağıdaki commit mesajını kullanın:

   ```
   feat: Task-08 otonom birim sunumu eklendi
   ```

4. Ana depoya bir Pull Request (PR) açın.
