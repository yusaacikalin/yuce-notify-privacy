# Yuce Notify Gizlilik Politikası

**Son güncelleme: 27 Ekim 2026**

Yuce Notify, **Yuşa Açıkalın** tarafından sunulan, bildirim kurallarını cihaz üzerinde çalıştıran bir Android bildirim yönetimi uygulamasıdır.

Bu Gizlilik Politikası, Yuce Notify uygulamasının hangi verilere eriştiğini, bu verileri nasıl kullandığını ve nasıl sakladığını açıklamaktadır.

## 1. Genel ilke

Bildirim filtreleme, kurallar ve yerel geçmiş internet olmadan çalışır. Bildirim içerikleri, telefon numaraları, kişi bilgileri, kural ve grup adları reklam veya analiz hizmetlerine gönderilmez.

Uygulama reklamlar için Google AdMob ve gizlilik tercihleri için Google User Messaging Platform (UMP) kullanır. Yayın sürümü ayrıca Firebase Analytics ve Crashlytics kullanır. Kullanıcı geri bildirim göndermeyi seçerse formdaki bilgiler Firebase Firestore üzerinden geliştiriciye iletilir. Bu çevrimiçi hizmetler internet bağlantısı gerektirir; ayrıntıları aşağıdadır.

## 2. Bildirim verileri

Kullanıcı bildirim erişimini etkinleştirdiğinde Yuce Notify, cihazda görüntülenen bildirimlere erişebilir.

Erişilebilen bilgiler şunları içerebilir:

- Bildirimi gönderen uygulamanın adı ve paket kimliği
- Bildirim başlığı ve metni
- Genişletilmiş bildirim metni
- Mesajlaşma bildirimlerindeki mesaj içerikleri
- Bildirim zamanı
- Bildirim kanalı ve grup bilgileri
- Kişisel veya iş profili bağlamı
- Bildirime uygulanan işlemin sonucu

Bu bilgiler yalnızca:

- Kullanıcının oluşturduğu bildirim kurallarını uygulamak,
- Eşleşen bildirimleri kaldırmak,
- Kullanıcıya yerel bildirim geçmişini göstermek ve
- Uygulamanın temel işlevlerini yerine getirmek

amacıyla kullanılır.

Bildirim verileri yalnızca kullanıcının cihazındaki uygulamaya özel depolama alanında tutulur. Geliştiriciye veya üçüncü taraflara gönderilmez.

## 3. Yüklü uygulama bilgileri

Yuce Notify, kullanıcının bildirim kuralı oluşturacağı uygulamayı seçebilmesi için cihazdaki başlatılabilir uygulamaların adlarını, simgelerini ve paket kimliklerini görüntüleyebilir.

Uygulama, cihazdaki bütün paketlere sınırsız erişim istemez. Erişilebilen uygulama bilgileri yalnızca cihaz üzerinde işlenir ve başka bir yere gönderilmez.

## 4. Telefon numaraları ve kişi seçimi

Telefon yönetimi özelliğinin desteklendiği ve kullanıcı tarafından etkinleştirildiği durumlarda kullanıcı bir telefon numarasını elle girebilir veya Android sisteminin kişi seçicisini kullanarak bir kişi seçebilir.

Kişi seçici kullanıldığında Yuce Notify yalnızca kullanıcının açıkça seçtiği kişinin görünen adını ve telefon numarasını okur. Uygulama rehberin tamamını okumaz.

Seçilen ad ve telefon numarası, kullanıcının oluşturduğu yerel telefon kuralının parçası olarak cihazda saklanabilir.

Yuce Notify varsayılan telefon uygulaması olarak seçilirse gelen veya giden çağrının telefon numarası, çağrı işlevini gerçekleştirmek amacıyla cihaz üzerinde geçici olarak işlenebilir. Uygulama sistem çağrı geçmişini okumaz ve geliştiriciye ait bir çağrı geçmişi sunucusu oluşturmaz.

Telefon numaraları ve kişi bilgileri geliştiriciye veya üçüncü taraflara gönderilmez.

## 5. İzinler ve özel erişimler

Yuce Notify, kullanılan özelliklere bağlı olarak aşağıdaki izin veya özel erişimleri isteyebilir:

### Bildirim erişimi

Bildirim kurallarını uygulamak, bildirim metinlerini eşleştirmek ve yerel bildirim geçmişini oluşturmak için kullanılır.

### Bildirim gönderme izni

Telefon yönetimi özelliği kullanılıyorsa gelen, devam eden veya cevapsız çağrı bildirimlerini göstermek için kullanılabilir.

### Telefon araması izni

Kullanıcının normal bir telefon araması başlatabilmesi için kullanılabilir.

### Varsayılan telefon uygulaması rolü

Telefon yönetimi özelliği etkinleştirilirse normal gelen ve giden çağrı arayüzünü sağlamak için kullanılabilir.

### Tam ekran bildirim erişimi

Desteklenen telefon işlevlerinde, cihaz kilitliyken normal gelen çağrı ekranını göstermek için kullanılabilir.

Bu erişimler kullanıcı tarafından Android ayarlarından verilebilir veya geri alınabilir.

Yuce Notify; konum, kamera, mikrofon, dosyalar, SMS mesajları, sistem çağrı geçmişi veya kullanıcının bütün kişi listesi için geniş kapsamlı erişim istemez.

## 6. Verilerin saklanması

Bildirim geçmişi, kullanıcının Ayarlar bölümünde seçtiği süre boyunca cihazda tutulur.

Kullanılabilir saklama süreleri:

- 1 gün
- 1 hafta
- 1 ay
- 3 ay
- 6 ay
- 1 yıl

Varsayılan saklama süresi 3 aydır. Seçilen süreden eski kayıtlar uygulamanın düzenli bakım işlemleri sırasında cihazdan silinir. Android işletim sistemi arka plan işlemlerini geciktirebileceği için silme işlemi seçilen sürenin dolduğu anda gerçekleşmeyebilir.

Kullanıcının oluşturduğu gruplar, bildirim kuralları, telefon kuralları ve tercihler kullanıcı tarafından silinene, uygulama verileri temizlenene veya uygulama kaldırılana kadar cihazda saklanabilir.

Android'in otomatik bulut yedeklemesi ve otomatik cihaz aktarımı kapalıdır. Kullanıcı veritabanını kendisi dışa aktarırsa seçtiği dosya veya depolama sağlayıcısında bir kopya oluşur; bu kopyaların saklanması, paylaşılması ve silinmesi kullanıcının kontrolündedir.

## 7. Verilerin silinmesi

Kullanıcı aşağıdaki yöntemlerle verilerini silebilir:

- Uygulamanın Ayarlar bölümündeki geçmiş temizleme seçeneğini kullanarak bildirim geçmişini silmek
- Oluşturduğu kuralları veya grupları uygulama içinden silmek
- Android uygulama ayarlarından Yuce Notify verilerini temizlemek
- Yuce Notify uygulamasını cihazdan kaldırmak

Yuce Notify kullanıcı hesabı oluşturmaz. Yerel verilerin silinmesi daha önce gönderilen geri bildirimleri veya hizmet sağlayıcıların tuttuğu reklam, kullanım ve hata kayıtlarını otomatik olarak silmez. Gönderdiğiniz geri bildirimle ilgili erişim veya silme talepleri için aşağıdaki iletişim adresini kullanabilirsiniz. Üçüncü taraf hizmetlerdeki veriler ilgili hizmetin saklama ve gizlilik uygulamalarına tabidir.

## 8. Reklamlar ve gizlilik tercihleri

Google AdMob, alt banner ve uygulamaya dönüşte açılış reklamları sunar. Google Mobile Ads SDK; IP adresi (yaklaşık konum çıkarımı dahil), reklam ve uygulama etkileşimleri, tanılama bilgileri ve reklam kimliği/uygulama kümesi kimliği gibi cihaz tanımlayıcılarını reklam sunumu, ölçüm ve kötüye kullanımın önlenmesi amacıyla işleyebilir. Yuce Notify, bildirim metinlerini, kişi bilgilerini veya kuralları bu SDK'ya aktarmaz; hassas konum izni istemez.

Gereken bölgelerde Google UMP gizlilik mesajı gösterilir ve reklam istekleri UMP'nin izin durumuna göre başlatılır. Sunulduğu durumlarda Ayarlar > Reklam gizlilik tercihleri üzerinden tercihlerinizi değiştirebilirsiniz. Kişiselleştirmeye izin vermemek bütün reklamları kaldırmak anlamına gelmez; uygun olduğunda sınırlı veya kişiselleştirilmemiş reklamlar sunulabilir. Android'in reklam ayarlarından reklam kimliğinizi yönetebilirsiniz.

Debug sürümü Google'ın test reklam birimlerini kullanır. Test reklamları da Google hizmetlerine ağ isteği gönderir. Yayın sürümünde uygulamaya ait reklam birimleri kullanılır.

[Google Gizlilik Politikası](https://policies.google.com/privacy), [Google hizmetlerini kullanan uygulamalardaki veriler](https://policies.google.com/technologies/partner-sites) ve [Mobile Ads SDK veri açıklamaları](https://developers.google.com/admob/android/privacy/play-data-disclosure).

## 9. Güvenlik

Veriler Android'in uygulamaya özel depolama alanında saklanır. Diğer uygulamaların bu alana normal koşullarda erişmesi Android işletim sistemi tarafından sınırlandırılır.

Hassas içerik gösteren uygulama ekranlarında ekran görüntüsü ve ekran kaydı gibi işlemleri sınırlandırmaya yönelik Android güvenlik özellikleri kullanılabilir.

Hiçbir elektronik saklama veya aktarım yöntemi mutlak güvenlik garantisi sağlamaz. Bildirim ve telefon kuralları yerel olarak işlenir; çevrimiçi hizmetler için yalnızca bu politikada belirtilen veriler kullanılır.

## 10. Çocukların gizliliği

Yuce Notify özellikle çocuklara yönelik olarak tasarlanmamıştır. Reklam, analiz ve geri bildirim hizmetlerinin veri uygulamaları bu politikada açıklanmıştır. Bir çocuğun geri bildirim yoluyla kişisel bilgi gönderdiğini düşünüyorsanız aşağıdaki adresten iletişime geçebilirsiniz.

## 11. Analiz, hata raporları ve isteğe bağlı geri bildirim

**Firebase Analytics ve Crashlytics:** Yayın sürümünde ekran ve oturum kullanımı, uygulama/Android sürümü, cihaz bilgileri, kullanım ve hata tanılama verileri Google Firebase tarafından işlenebilir. Uygulamanın günlük özeti yalnızca grup, kural, etkin kural, geçmiş kaydı ve işlenen bildirim sayılarını gönderir. Özel olaylara bildirim içeriği, telefon numarası, kişi adı, kural/grup adı, hedef uygulama paketi veya dosya yolu eklenmez. Debug sürümünde Analytics ve Crashlytics SDK'ları bulunmaz.

**Geri bildirim:** Kullanıcı gönder düğmesine bastığında seçilen konu, yazdığı açıklama, isteğe bağlı e-posta adresi, uygulama ve Android sürümü, cihaz modeli, uygulama/cihaz dili ve gönderim zamanı Yuce Notify'ye ait Firebase Firestore projesine iletilir. Bildirim geçmişi veya telefon rehberi otomatik olarak eklenmez. Açıklama alanına gereksiz hassas bilgi yazmayın. Veriler geri bildirimi değerlendirmek ve gerekirse yanıtlamak için kullanılır.

Google hizmetleri verileri kullanıcının ülkesi dışındaki sunucularda işleyebilir. Hizmet sağlayıcıların saklama uygulamaları ve kullanılabilir kontrolleri kendi politikalarında açıklanır: [Firebase gizlilik ve güvenlik](https://firebase.google.com/support/privacy).

Uygulama güncelleme kontrolü ve mağaza sayfaları için Google Play hizmetlerini kullanabilir. Android sistem bileşenleri ve açık kaynak kütüphaneler temel işlevleri destekler.

## 12. Gizlilik Politikasındaki değişiklikler

Bu Gizlilik Politikası uygulamadaki, yasal gereksinimlerdeki veya Google Play politikalarındaki değişikliklere bağlı olarak güncellenebilir.

Politikanın güncel sürümü bu sayfada yayımlanır ve “Son güncelleme” tarihi değiştirilir.

## 13. İletişim

Bu Gizlilik Politikası veya Yuce Notify uygulamasındaki veri uygulamaları hakkında sorularınız için:

**Geliştirici:** Yuşa Açıkalın  
**E-posta:** yucenotify@gmail.com

