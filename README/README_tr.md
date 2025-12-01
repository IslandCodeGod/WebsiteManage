[English](README_en.md)|[German](README_de.md)|[中文](README_zh.md)|[日本語](README_ja.md)|[Русский](README_ru.md)|[한국어](README_ko.md)|[Español](README_es.md)|[Français](README_fr.md)|[Italiano](README_it.md)|[Português](README_pt.md)|[Nederlands](README_nl.md)|[Polski](README_pl.md)|[العربية](README_ar.md)|[हिन्दी](README_hi.md)|[ไทย](README_th.md)|[Svenska](README_sv.md)|Türkçe|[Tiếng Việt](README_vi.md)

# Flask Web Uygulaması - Kurumsal web sitesi yönetim sistemi (şifreli versiyon)

## Proje Tanıtımı

Bu, Flask çerçevesine dayalı olarak geliştirilmiş kurumsal bir web sitesi yönetim sisteminin **şifrelenmiş sürümüdür**. Fikri mülkiyet haklarını korumak için çekirdek kod PyArmor tarafından gizlenmiş ve şifrelenmiştir.Sistem çoklu dili (Çince ve İngilizce), kullanıcı kimlik doğrulamasını, ürün ve haber yönetimini, şirket bilgilerinin görüntülenmesini ve diğer işlevleri destekler.

## Uygulama ekran görüntüsü

Aşağıda uygulamanın ana arayüzünün ekran görüntüsü verilmiştir:

### Ana Sayfa
![首页](screenshots/index.png)

### Yönetim geçmişi
![管理后台](screenshots/admin_dashboard.png)

## Sürüm Notları

Bu sürüm, eksiksiz kurumsal web sitesi yönetimi işlevleri sağlayan temel bir şifreleme sürümüdür.İhtiyacınız varsa:

- **Tam kaynak kodu sürümü**: İkincil geliştirmeyi kolaylaştırmak için şifrelenmemiş tam kaynak kodunu içerir
- **Özelleştirilmiş İşlev Geliştirme**: Özel ihtiyaçlarınıza göre işlevin özelleştirilmesi ve genişletilmesi
- **Teknik Destek Hizmetleri**: Profesyonel teknik destek ve bakım hizmetleri alın

Lütfen aşağıdaki iletişim bilgilerinden bizimle iletişime geçin;size detaylı planlar ve teklifler sunacağız.

## Şifreleme özellikleri

- **Kod Koruması**: Çekirdek Python dosyaları (app.py, init_db.py, models.py) gizlenmiş ve şifrelenmiştir
- **Çalışma Zamanı Koruması**: Kodun kaynak koda dönüştürülmesini önlemek için PyArmor çalışma zamanı ortamını kullanın
- **Tam işlevsellik**: Şifrelenmiş kod, tüm orijinal işlevsellik ve özellikleri korur
- **Çoklu dil desteği**: yerleşik Çince ve İngilizce geçiş işlevi

## Dosyaları dahil et

```
/
├── app.py                  # Şifreli ana uygulama girişi
├── init_db.py              # Şifreli veritabanı başlatma komut dosyası
├── models.py               # Şifrelenmiş veri modelleri
├── babel.cfg               # Babel uluslararasılaştırma yapılandırması
├── pyarmor_runtime_000000/ # PyArmor çalışma zamanı destek dosyaları
├── static/                 # Statik kaynak dosyaları (CSS, JS, resimler)
├── templates/              # HTML şablon dosyaları
├── translations/           # Çok dilli çeviri dosyaları
└── instance/               # Veritabanı dizini (ilk çalıştırmada otomatik olarak oluşturulur)
```

## Hızlı başlangıç

### Çevresel gereksinimler

- Python 3.9 veya üzeri
- Yüklü bağımlılık paketleri:
- Şişe 3.0.0+
- Flask-SQLAlchemy 3.1.1+
- Şişe-Giriş 0.6.3+
- Şişe-Babel 4.0.0+
- Werkzeug 3.0.1+

### Bağımlılıkları yükleyin

Gerekli bağımlılıklar henüz yüklenmemişse lütfen önce bunları yükleyin:

```bash
pip install flask flask-sqlalchemy flask-login flask-babel werkzeug
```

### Uygulamayı çalıştırın

1. **Veritabanını başlat**

İlk kez çalıştırmadan önce veritabanının başlatılması gerekir:

```bash
   python init_db.py
   ```

2. **Uygulamayı başlatın**

```bash
   python app.py
   ```

3. **Uygulamaya Erişim**

Tarayıcıyı açın ve şu adresi ziyaret edin: http://127.0.0.1:5000

## Kullanım talimatları

### Web sitesini ziyaret edin

1. Tarayıcıyı açın ve http://127.0.0.1:5000 adresini ziyaret edin.
2. Çince ve İngilizce arasında geçiş yapmak için sağ üst köşedeki dil değiştirme düğmesini kullanın

### Yönetim geçmişi

1. http://127.0.0.1:5000/admin/login adresini ziyaret edin
2. Yönetici hesabıyla oturum açın (varsayılan kullanıcı adı ve şifre: admin/admin123)
3. Yönetim arka planında ürünler, haberler ve şirket bilgileri yönetilebilir

## Fonksiyon açıklaması

### Ön uç işlevleri

- **Ana Sayfa**: Şirket profilini ve ana ürünleri görüntüleyin
- **Hakkımızda**: Şirket ayrıntılarını göster
- **Ürün Teşhiri**: Tüm ürün listelerine göz atın
- **Sektör Güncellemeleri**: En son haberleri ve bilgileri görüntüleyin
- **Dil değiştirme**: Çince ve İngilizce arasında geçişi destekler

### Arka plan işlevlerini yönetin

- **Ürün Yönetimi**: Ürün ekleme, düzenleme, silme
- **Haber Yönetimi**: Haberleri yayınlayın, düzenleyin, silin
- **Şirket Bilgileri**: Temel şirket bilgilerini güncelleyin
- **Kullanıcı Kimlik Doğrulaması**: güvenli oturum açma sistemi

## Ekran Görüntüsü Kılavuzu

En iyi README görüntü efektini elde etmek için aşağıdaki yönergelere göre ekran görüntüleri oluşturup eklemeniz önerilir:

1. **Ekran görüntüleri klasörü oluşturun**: `dist/` dizininde `screenshots/` klasörünü oluşturun
2. **Ekran Görüntüsü Boyutu**: İçeriğin açıkça görülebilmesini sağlamak için 1920x1080 veya 1366x768 çözünürlüklü bir ekran görüntüsü kullanın
3. **Ekran görüntüsü içeriği**:
- Ana sayfa: Gezinme çubuğu ve ana içerik alanı da dahil olmak üzere ana sayfa arayüzünün tamamını görüntüler
- Dil değiştirme: Çince ve İngilizce arasında geçişin karşılaştırmalı etkisini gösterin (bölünmüş ekran ekran görüntüleri kullanılabilir)
- Ürün ekranı: ürün listesini ve tek tek ürünlerin ayrıntılarını görüntüleyin
- Haber sayfası: haber listesini ve haber ayrıntılarını görüntüleyin
- Yönetim arka ucu: yönetici oturum açtıktan sonra kontrol panelini ve işlevsel arayüzü görüntüler
4. **Ekran Görüntüsü Formatı**: En iyi kalite için PNG formatını kullanın
5. **Dosya Adlandırma**: Ekran görüntüsünü README'de belirtilen dosya adına (index.png, language_switch.png vb.) göre kaydedin.

## Notlar

1. **Dosya Bütünlüğü**: Lütfen tüm dosyaların, özellikle de "pyarmor_runtime_000000" dizini ve içeriğinin doğru şekilde indirildiğinden emin olun.

2. **Veritabanı dosyası**:
- Veritabanı dosyası otomatik olarak 'örnek' dizininde oluşturulacaktır
- Verileri yedeklemeniz gerekiyorsa lütfen "instance/site.db" dosyasını düzenli olarak yedekleyin.

3. **Çoklu dil desteği**:
- Tüm çeviri dosyaları "çeviriler" dizininde bulunur
- Yeni çeviri dilleri eklemek için lütfen orijinal proje belgelerine bakın.

4. **Çalışma ortamı**:
- Python sürümünün 3.9'dan düşük olmadığından emin olun
- Gerekli tüm bağımlılıkların kurulu olduğundan emin olun

5. **Güvenlik İpuçları**:
- Bir üretim ortamına dağıtım yaparken lütfen varsayılan yönetici şifresini değiştirin.
- Geliştirme sunucusu yerine bir WSGI sunucusu (Gunicorn gibi) kullanmayı düşünün
- Uygun güvenlik duvarı kurallarını yapılandırın

## Dağıtım önerileri

### Geliştirme ortamı

Flask yerleşik geliştirme sunucusunu kullanın (yukarıdaki hızlı başlangıçta gösterilmiştir).

### Üretim ortamı

1. **WSGI sunucusunu kullanın**:
```bash
   pip install gunicorn
   gunicorn -w 4 -b 0.0.0.0:8000 app:app
   ```

2. **Ters proxy kullan**:
- Nginx veya Apache'yi ters proxy olarak yapılandırın
- HTTPS'yi etkinleştirmek için SSL sertifikasını ayarlayın

3. **Veritabanı Optimizasyonu**:
- SQLite yerine PostgreSQL veya MySQL kullanmayı düşünün
- Düzenli yedekleme mekanizmasını yapılandırın

## Sorun Giderme

### SSS

1. **Uygulama başlatılamıyor**:
- Python sürümünün gereksinimleri karşılayıp karşılamadığını kontrol edin
- Tüm bağımlı paketlerin doğru şekilde kurulduğunu doğrulayın
- `pyarmor_runtime_000000` dizininin var olup olmadığını ve eksiksiz olup olmadığını kontrol edin

2. **Dil değiştirme çalışmıyor**:
- 'Çeviriler' dizininin ve içeriğinin eksiksiz olduğunu doğrulayın
- Tarayıcı Çerez ayarlarına izin verilip verilmediğini kontrol edin

3. **Veritabanı bağlantı hatası**:
- "Örnek" dizininin mevcut olduğunu ve yazma izinlerine sahip olduğunu doğrulayın
- Veritabanını başlatmak için `init_db.py`yi yeniden çalıştırmayı deneyin

### Günlük Görünümü

Uygulama başlatıldığında, günlük bilgileri konsola aktarılacaktır. Sorunla karşılaşırsanız daha fazla bilgi için bu günlükleri kontrol edebilirsiniz.

## Lisans

[MIT License](LICENSE)

## İletişim bilgileri

Herhangi bir sorunuz, öneriniz varsa veya tam sürüm/özelleştirilmiş işlev geliştirmeye ihtiyacınız varsa, lütfen aşağıdaki yöntemlerle iletişime geçin:

- **E-posta**: austinlive666@gmail.com (önerilir)
- **Discord**:[https://discord.gg/7AN9PuGn](https://discord.gg/7AN9PuGn)

---

Bu projeyi kullandığınız için teşekkür ederiz!