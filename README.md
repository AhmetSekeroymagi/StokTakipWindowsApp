# 📦 Basit Stok Takip Web Uygulaması (.NET Framework & MSSQL)

Bu proje, .NET Framework ve MSSQL kullanılarak geliştirilmiş, localde çalışan bir **stok takip web uygulamasıdır**.  
Ürün ve kategori bazlı stok işlemleri kolayca yönetilebilir. Küçük işletmeler veya bireysel kullanıcılar için uygundur.

---

## 🚀 Özellikler

### Ürün İşlemleri
- ✅ **Ürün Ekleme**
- 🗑️ **Ürün Silme**
- 🔄 **Ürün Güncelleme**
- 🔍 **Ürün Arama** (Ürün adı veya kategoriye göre)

### Kategori İşlemleri
- ✅ **Kategori Ekleme**
- 🗑️ **Kategori Silme**
- 🔄 **Kategori Güncelleme**
- 🔍 **Kategori Arama**

---

## 🛠️ Kullanılan Teknolojiler

- ASP.NET Framework
- C# (Backend)
- MSSQL (Veritabanı)
- ADO.NET (Veritabanı bağlantısı)
- HTML / CSS (Web arayüzü)

---

## 💻 Kurulum

1. Bu repoyu klonlayın:  
   `git clone https://github.com/AhmetSekeroymagi/StokTakipApp.git`
2. `StokTakipApp` klasörünü açın.
3. `APP` klasörü içindeki `setup.exe` dosyasını çalıştırarak uygulamayı kurun.
4. Kurulum tamamlandıktan sonra uygulamayı başlatabilirsiniz.

### ❗ Hata Alırsanız
- `Web.config` dosyasındaki **veritabanı bağlantı cümlesini** kendi sunucunuza göre güncelleyin.
- Veritabanını manuel oluşturup gerekli tabloları (`Ürünler`, `Kategoriler`) ekleyin.
- MSSQL Server aktif olduğundan ve bağlantı bilgilerinin doğru olduğundan emin olun.
- Gerekirse projeyi Visual Studio'da açıp `F5` ile çalıştırabilirsiniz.

---

## 🧱 Veritabanı Yapısı

**Veritabanı tablolarının yapısını** aşağıdaki görsellerden inceleyebilirsiniz:

- ![MSSQL Products Table](Products-1.png)  
- ![MSSQL Categories Table](Categories-1.png)

---

## 📸 Uygulama Görselleri

- **Kategori Sayfası**  
  ![Kategori Sayfası](KatagoriSayfası-1.png)

- **Ürün Sayfası**  
  ![Ürün Sayfası](UrunSayfası-1.png)

- **Ürün Ekleme**  
  ![Ürün Ekleme](UrunSayfasıEkleme-1.png)

- **Ürün Güncelleme**  
  ![Ürün Güncelleme](UrunSayfasıGuncelle-1.png)

- **Ürün Silme**  
  ![Ürün Silme](UrunSayfasıSil-1.png)

---

## 📌 Notlar

- Uygulama **yalnızca localde** çalışacak şekilde yapılandırılmıştır.
- Veritabanı bağlantı ayarlarını doğru yapılandırmayı unutmayın.
- Küçük işletmeler veya bireysel kullanım için uygundur.

---

## 👤 Geliştirici

**Ahmet Şekeroymağı**  
🔗 GitHub: [github.com/AhmetSekeroymagi](https://github.com/AhmetSekeroymagi)
