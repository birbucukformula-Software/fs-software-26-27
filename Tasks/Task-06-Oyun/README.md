# 🎮 Görev 6: Oyun Geliştirme Süreçleri ve Performans Temelleri

## 🎯 Amaç
Oyun geliştirme; hayal gücü ile yazılım mühendisliğini bir araya getiren, hem görsel hem de teknik açıdan çok keyifli bir alandır. Ancak bir oyunun güzel görünmesi kadar, akıcı çalışması ve donanımı gereksiz yere yormadan yüksek kare hızlarında (FPS) oynanabilmesi de bir mühendis için en temel hedeftir.

Bu görevde amacımız; takımımıza yeni katılan üyelerimizin bir oyunun fikir aşamasından oynanabilir hale gelene kadar hangi adımlardan geçtiğini öğrenmesi, oyun motorlarının temel mantığını kavraması ve oyun dünyasında performansı artırmak (oyunun kasmasını engellemek) için kullanılan pratik yöntemleri araştırmasıdır. Neleri araştıracağınıza ve sunumunuzda hangi konuları derinleştireceğinize büyük ölçüde kendiniz karar vereceksiniz.

## 🛠️ İstenen İçerik: Sunum Akışı
Sunumunuzda aşağıdaki ana başlıkları bir çerçeve olarak ele almanız beklenmektedir. Sunum süresi **10-15 dakikayı** geçmemelidir.

### Bölüm 1: Bir Oyun Nasıl Yapılır? (Oyun Yapım Süreci)
- Fikirden oyuna giden yol: Oyun fikri, görsel tasarım/modelleme, mekaniklerin kodlanması ve test aşamaları
- Oyun motoru (Unity, Unreal Engine vb.) nedir, neden sıfırdan her şeyi yazmak yerine bir oyun motoru kullanırız?
- Oyunun kalbi: Temel oyun döngüsü mantığı (Game Loop - Girdiyi al -> Dünyayı güncelle -> Ekrana çiz)

### Bölüm 2: Oyunlarda Performans: Neden Kasar ve FPS Neden Düşer?
- FPS (Kare/Saniye) nedir ve oyunun akıcı hissettirmesi için neden önemlidir?
- CPU (İşlemci) ve GPU (Ekran Kartı) arasındaki iş bölümü: Oyun çalışırken hangisi ne yapar?
- Darboğaz (Bottleneck) nedir: Oyun takılıyorsa sorun işlemcide mi, yoksa ekran kartında mıdır?

### Bölüm 3: Oyunu Rahatlatacak Temel Yöntemler (Performans Optimizasyonu)
- **Görünmeyen nesneleri çizmemek (Culling):** Kameranın görmediği veya duvarın arkasında kalan nesneleri ekrana çizmemek neden önemlidir?
- **Uzaktaki detayları sadeleştirmek (LOD - Level of Detail):** Oyuncudan çok uzakta duran bir araba veya ağaç neden daha az poligonla çizilmelidir?
- **Nesneleri sürekli silip yeniden yaratmamak (Object Pooling):** Ateş edilen mermileri her seferinde hafızadan silip baştan yaratmak yerine bir kenarda saklayıp tekrar kullanma mantığı
- **Gereksiz kod tekrarlarından kaçınmak:** Her karede (Update döngüsünde) sürekli ağır işlemler çalıştırmaktan neden kaçınmalıyız?

### Bölüm 4: Oyun Dünyasından Gerçek Örnekler ve Simülasyonlar
- Bir oyundaki donma ve kasmaları tespit etmek için kullanılan ölçüm/profilleme (Profiler) araçları
- Oyun teknolojilerinin yarış takımlarındaki rolü: Formula Student simülatörleri ve gerçekçi araç sürüş dinamikleri

## 💡 Ek Katkılar
Yukarıdaki başlıklar sunum için bir çerçeve çizmektedir; sunumunuzu bunlarla sınırlı tutmanız gerekmez. Araştırmanızı sevdiğiniz oyunlardan örneklerle, Unity veya Unreal Engine arayüzünden ekran görüntüleriyle veya yarış simülasyonlarıyla zenginleştirebilirsiniz.

## 📤 Teslim Formatı
1. Sunumunuzu PDF formatına dönüştürün. Dosya adını aşağıdaki biçimde oluşturun:

   ```
   [Ad]-[Soyad].pdf
   ```

2. Fork'ladığınız depoda aşağıdaki klasörü oluşturun ve PDF dosyanızı bu klasöre yükleyin:

   ```
   Submissions/Submission-06-Oyun-[Ad]-[Soyad]/
   ```

3. Aşağıdaki commit mesajını kullanın:

   ```
   feat: Task-06 oyun birim sunumu eklendi
   ```

4. Ana depoya bir Pull Request (PR) açın.


