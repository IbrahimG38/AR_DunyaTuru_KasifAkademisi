# AR_DunyaTuru_KasifAkademisi
 Bu proje, AR Foundation kullanarak bir AR eğitim uygulaması geliştirmeyi amaçlayan bir AR uygulamasıdır. Uygulama, kullanıcıların ünlü dünya yapılarını (Eyfel Kulesi, vb.) artırılmış gerçeklik (AR) ortamında keşfetmelerini sağlar. Her yapı, üzerine tıklanarak bir bilgi kartı ile açıklanır ve kullanıcı her yapıyı keşfettikçe ödüller kazanır.

## 🎯 Projenin Amacı
AR kamera kullanarak 3D modellerin gerçek dünyada görüntülenmesi.

Kullanıcı tıklama etkileşimi ile bilgi kartları gösterilmesi.

Kullanıcılar için ödül sisteminin basit bir şekilde işlenmesi.

Avatar seçimi (isteğe bağlı) ve basit bir kullanıcı arayüzü (UI).

### 📝 Kurulum ve Çalıştırma Talimatları
Adım adım projeyi bilgisayarınızda çalıştırmak için şu talimatları takip edebilirsiniz:

## 1. Gerekli Yazılımlar
Projeyi çalıştırabilmek için aşağıdaki yazılımların yüklü olması gerekmektedir:

Unity: Projenin geliştirildiği oyun motorudur. Unity İndir

AR Foundation: Unity içinde AR projeleri oluşturmak için kullanılan SDK. Bu proje için Unity'deki AR Foundation paketinin yüklü olması gerekmektedir.

Android Build: Eğer projeyi Android cihazında test etmek istiyorsanız, Android Build Support kurulmuş olmalıdır.

## 2. Projeyi İndirme ve Çalıştırma

> Not: Bu projede `Library/` klasörü depoya dahil edilmemiştir. Unity, projeyi açarken bu klasörü otomatik olarak oluşturur. İlk açılış biraz uzun sürebilir, lütfen bekleyiniz.

# Adım 1: Projeyi GitHub'dan İndirin
Github reposunu bilgisayarınıza klonlayın:

bash
Kopyala
Düzenle
git clone 

# Adım 2: Unity Projesini Açın
Unity Hub'ı açın ve AR-Dunya-Turu klasörünü seçerek projeyi açın.

# Adım 3: Gerekli Paketleri Yükleyin
Unity içinde, Package Manager aracılığıyla AR Foundation ve diğer gerekli paketleri yükleyin:

AR Foundation

ARCore XR Plugin (Android için)

ARKit XR Plugin (iOS için)

# Adım 4: Android Build Ayarlarını Yapın
Eğer Android cihazında test etmek istiyorsanız, Unity'deki Build Settings bölümünden Android platformunu seçin ve gerekli ayarları yapın.

# Adım 5: Projeyi Çalıştırın
Unity içerisinde Play butonuna tıklayarak projeyi test edebilirsiniz. Marker üzerinden 3D modellerin göründüğünden ve tıklama etkileşimlerinin doğru şekilde çalıştığından emin olun.

### ⚙️ Projeyi Kullanma
Uygulama başlatıldığında, Ana Menü ekranı açılır. Buradan "Başla" butonuna tıklayarak AR oturumunu başlatabilirsiniz.

Kamera açıldığında, marker (örneğin, bir resim) üzerine AR modelleri bindirilir. Model üzerine tıklanarak yapı hakkında bilgi kartı görüntülenir.

Yapıya tıkladığınızda, ödül sistemi devreye girer ve bir rozet kazanırsınız.

Avatar seçimi (isteğe bağlı) ve ödül kartı sistemini deneyebilirsiniz.

### 📂 Proje Dosyaları
Assets/Scenes: Projenin sahne dosyalarını içerir.

Assets/Models: 3D modellerin bulunduğu klasördür.

Assets/Scripts: Uygulama içerisindeki C# betiklerinin bulunduğu klasördür.

Assets/Prefabs: Uygulama için oluşturulan prefablar (önceden ayarlanmış objeler).

### 🔧 Konfigürasyon ve Özelleştirme
Proje, farklı marker'lar ile çalışacak şekilde özelleştirilebilir. Aşağıdaki adımları izleyerek yeni marker'lar ekleyebilir veya modelleri değiştirebilirsiniz:

Yeni Marker Eklemek: ARSession bileşenine yeni bir Image Target ekleyin ve marker resmi ile ilişkilendirin.

Yeni 3D Model Eklemek: LandmarkModel prefab'ını kullanarak farklı 3D modelleri ekleyebilirsiniz.

### 📑 Katkıda Bulunma
Eğer bu projeye katkıda bulunmak isterseniz, aşağıdaki adımları izleyebilirsiniz:

Fork işlemi gerçekleştirin.

Yeni bir branch oluşturun (git checkout -b feature-name).

Değişikliklerinizi yapın ve commit edin.

Pull Request gönderin.

### 🛠️ Sorun Giderme
Eğer AR modeli görünmüyorsa, marker’ın doğru şekilde algılandığından emin olun. Ayrıca, Unity ayarlarında AR Foundation’ın doğru şekilde yapılandırıldığından emin olun.

Eğer uygulama çalıştırılmıyorsa, platform ayarlarının doğru yapıldığını kontrol edin (Android için Build Settings).




