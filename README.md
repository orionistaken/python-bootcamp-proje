# Taş, Kağıt, Makas, Su, Ateş Oyunu
Bu proje, klasik taş-kağıt-makas oyununu genişleterek "su" ve "ateş" seçeneklerini ekleyen bir Python uygulamasıdır. Bu oyun, oyuncunun bilgisayara karşı oynadığı eğlenceli bir oyunu simüle eder. Oyunun amacı, iki raunt kazananın oyunu kazanmasıdır.

### Oyun Kuralları 
  * Taş: Makası ve ateşi yener.
  * Kağıt: Taşı ve suyu yener.
  * Makas: Kağıdı ve suyu yener.
  * Su: Taşı ve ateşi yener.
  * Ateş: Kağıdı ve makası yener.

İlk olarak 2 raunt kazanan oyuncu oyunun galibi olur.

### Nasıl Oynanır?
  * Oyunu başlatmak için tas_kagit_makas_BURHAN_KORKMAZ() fonksiyonunu çalıştırın.
  * Oyun başladığında, sizden taş, kağıt, makas, su veya ateş seçeneklerinden birini seçmeniz istenecek.
  * Bilgisayar rastgele bir seçim yapacak ve sonuçlar değerlendirilecek.
  * İlk olarak iki galibiyete ulaşan taraf oyunu kazanır.
  * Oyun sonunda, başka bir oyun oynamak isteyip istemediğiniz sorulacaktır. İsterseniz oyun tekrar başlayabilir.

### Teknik Detaylar
Bu projede aşağıda belirtilen fonksiyonlar kullanılmıştır.
  * 'oyun_aciklamalari()': Oyunun kurallarını ekrana yazdırır.
  * 'oyuncu_secenek_girdisi(secenekler)': Oyuncudan geçerli bir seçenek alır.
  * 'kazanani_sec(oyuncu_secimi, bilgisayar_secimi)': Yapılan seçimlere göre turu kimin kazandığını belirler.
  * 'oyuna_devam_girdisi()': Oyuncuya başka bir oyun oynamak isteyip istemediğini sorar.
  * 'tas_kagit_makas_BURHAN_KORKMAZ()': Ana oyun döngüsünü içerir ve oyunun akışını kontrol eder.

### Önemli Noktalar
 * Rastgele Seçim: Bilgisayarın her tur için rastgele bir seçim yapması sağlanır.
 * Çıkış Koşulu: Oyuncu istediği zaman 'q' tuşuna basarak oyundan çıkabilir.
 * Oyun Döngüsü: Oyun, oyuncu ve bilgisayarın devam etmek istemediği noktaya kadar devam eder.

