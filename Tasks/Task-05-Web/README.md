# 🌐 Görev 5: Web Teknolojileri ve İstemci-Sunucu Mimarisi

## 🎯 Amaç
Web teknolojileri; internet üzerinde gördüğümüz tüm sitelerin, kurumsal sayfaların ve web uygulamalarının temelini oluşturur. Bir Formula Student takımında web birimi; takımın dünyaya, jüriye ve sponsorlara açılan en önemli vitrini olan kurumsal web sitesini tasarlar, geliştirir ve güncel tutar.

Bu görevde amacımız; takımımıza yeni katılan üyelerimizin web geliştirmenin temel mantığını kavraması, bir tarayıcı (istemci) ile sunucunun nasıl haberleştiğini öğrenmesi ve Frontend (Arayüz) ile Backend (Arka Yüz / Veri) arasındaki iletişim köprüsünü (API) araştırmasıdır. Neleri araştıracağınıza ve sunumunuzda hangi konuları derinleştireceğinize büyük ölçüde kendiniz karar vereceksiniz.

## 🛠️ İstenen İçerik: Sunum Akışı
Sunumunuzda aşağıdaki ana başlıkları bir çerçeve olarak ele almanız beklenmektedir. Sunum süresi **10-15 dakikayı** geçmemelidir.

### Bölüm 1: Web Geliştirme Nedir ve Nasıl Çalışır?
- Web geliştirmenin temelleri: Bir web sitesi açıldığında arka planda ne olur?
- Web'in üç temel yapı taşı:
  - **HTML:** Sayfanın iskeleti ve yapısı (yazılar, butonlar, kutular)
  - **CSS:** Sayfanın tasarımı ve stili (renkler, düzen, estetik)
  - **JavaScript:** Sayfanın beyni ve hareketleri (tıklamalar, animasyonlar, etkileşimler)
- Neden günümüzde modern kütüphaneler (React, Vue vb.) tercih ediliyor?

### Bölüm 2: İstemci ve Sunucu (Client - Server) Mimarisi
- **İstemci (Client) nedir?** Tarayıcımız (Chrome, Firefox vb.) veya kullanıcı cihazları
- **Sunucu (Server) nedir?** 7/24 çalışan, web sayfalarını saklayan ve talepleri karşılayan sistemler
- **İstek ve Cevap (Request - Response) döngüsü:** Bir web sitesine tıklandığında tarayıcının sunucudan sayfa istemesi ve sunucunun yanıt dönmesi mantığı (HTTP / HTTPS temelleri)

### Bölüm 3: Frontend ve Backend Nasıl İletişim Kurar?
- **Frontend (Ön Yüz):** Kullanıcının ekranda gördüğü ve etkileşime girdiği görsel arayüz
- **Backend (Arka Yüz):** Kullanıcının görmediği iş mantığı, hesaplamalar ve veritabanı (Database)
- **Köprü Görevi: API nedir?** Frontend, sunucudaki verilere nasıl ulaşır? (Örnek: Bir restoranda müşteri ile mutfak arasındaki garson benzetmesi)
- **JSON Formatı:** Frontend ve Backend'in birbiriyle konuşurken kullandığı ortak veri dili

### Bölüm 4: Web Sitesinin Yayına Alınması ve Takım İçindeki Rolü
- **Bir site internete nasıl açılır?** Domain (alan adı), Hosting ve modern dağıtım platformları (Vercel, GitHub Pages, Netlify vb.)
- **Duyarlı (Responsive) Tasarım:** Sayfanın hem cep telefonunda hem de bilgisayar ekranında düzgün görünmesi neden önemlidir?
- Formula Student takımında web biriminin rolü: Takımın kurumsal web sitesi, sponsorluk tanıtımları, blog/haberler ve takım kimliği

## 💡 Ek Katkılar
Yukarıdaki başlıklar sunum için bir çerçeve çizmektedir; sunumunuzu bunlarla sınırlı tutmanız gerekmez. Araştırmanızı popüler web sitelerinden veya diğer Formula Student takımlarının web sitelerinden örneklerle, tarayıcı geliştirici araçları (F12 / DevTools - Network sekmesi) ekran görüntüleriyle veya kendi hazırladığınız mini arayüz örnekleriyle zenginleştirebilirsiniz.

## 💻 Uygulama Görevi: Birbuçuk Adana Formula Web Sitesi Yeni Arayüz Tasarımı (Frontend)

Araştırmalarınızı ve sunumunuzu tamamladıktan sonra, edindiğiniz teorik bilgileri pratiğe dökmeniz beklenmektedir.

Takımımızın mevcut web sitesini ([birbucukadanaformula.com](https://birbucukadanaformula.com/)) ve dünyadaki diğer Formula Student ekiplerinin web sitelerini inceleyerek; takımımız için modern, estetik ve Formula Student yarış ruhunu yansıtan **yeni bir web sitesi arayüzü (Frontend)** tasarlamanızı ve kodlamanızı istiyoruz.

### 📌 Görev Kapsamı ve İsterler:
- **Sadece Frontend:** Bu görevde backend, veritabanı veya sunucu taraflı işlemler **istenmemektedir**. Sadece tarayıcı üzerinde çalışan kullanıcı arayüzü (UI/UX) geliştirilecektir.
- **Kullanılacak Teknolojiler:** **HTML, CSS ve JavaScript (Vanilla)** kullanmanız yeterlidir. Herhangi bir karmaşık framework (React, Vue vb.) zorunluluğu yoktur; temel web teknolojileriyle temiz ve anlaşılır bir yapı kurmanız esastır.
- **İçerik ve Fotoğraflar:** Tasarımınızda kullanacağınız metinleri, takım bilgilerini, teknik detayları ve görselleri doğrudan mevcut web sitemizden ([birbucukadanaformula.com](https://birbucukadanaformula.com/)) çekip kullanabilirsiniz.
- **Renk Paleti ve Tasarım Dili:** Takımımızın kimliğini ve yarış dinamizmini yansıtacak şekilde **kırmızı, siyah ve beyaz** renklerin ön planda olduğu, modern ve estetik bir tasarım dili tercih edilmelidir.
- **Mevcut Sitenin Analizi:** Mevcut web sitemizi inceleyin; hangi alanların daha iyi tasarlanabileceğini, tipografi ve düzen uyumunu, kullanıcı deneyimini (UX) nasıl güçlendirebileceğinizi belirleyin.

## 📤 Teslim Formatı
1. Sunumunuzu PDF formatına dönüştürün. Dosya adını aşağıdaki biçimde oluşturun:

   ```
   [Ad]-[Soyad].pdf
   ```

2. Hazırladığınız yeni web sitesi arayüz dosyalarını (`index.html`, `style.css`, `script.js` ve varsa görseller için `assets/` klasörü) ile sunum PDF'inizi, fork'ladığınız depoda aşağıdaki klasör yapısına uygun şekilde yükleyin:

   ```
   Submissions/Submission-05-Web-[Ad]-[Soyad]/
   ├── [Ad]-[Soyad].pdf
   ├── index.html
   ├── style.css
   ├── script.js
   └── assets/ (varsa resim ve ikonlar)
   ```

3. Aşağıdaki commit mesajını kullanın:

   ```
   feat: Task-05 web birim sunumu ve yeni tasarim eklendi
   ```

4. Ana depoya bir Pull Request (PR) açın.



