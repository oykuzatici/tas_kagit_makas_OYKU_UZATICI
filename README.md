# tas_kagit_makas_OYKU_UZATICI
Taş Kağıt Makas oynunun Python'da Console şeklindeki versiyonunu yapılmıştır. Console, Jupyter Notebook'ta hazırlanmış olup .py uzantılı hali repository'e yüklenmiştir.
İlk olarak random kütüphanesi tanımlanmıştır.
Gerekli kütüphane tanımlamaları yapıldıktan sonra fonksiyon ataması yapılmıştır.
Fonksiyon atamasından sonra ilk olarak oynun kuralları ekrana getirilip oyna başlanır.Oyun kullanıcı ve bilgisayar arasında geçecektir. 
Oyun başladığı zaman oyunun kaçıncı oynanan oyun olduğu da ekrana getirlmektedir.
İlk olarak seçilebilecek 3 hareket ekrana getirilmiştir: 1. taş, 2.kağıt ve 3.makas
Daha sonra kullanıcının seçeceği hareketi seçmesi için kullanıcıdan input girmesi istenmektedir.
İnput girerken seçeceği hareketin rakamının yazılması istenmektedir. İstenen şartlara uygun olarak input girilmediği taktirde sistem hata verir. 
Kullanıcı gerekli şartlara uygun olarak input girerek hareket seçimini yaptıktan sonra bilgisayar da seçimini otomatik olarak (random kütüphanesi kullanılarak) seçmektedir.
Her bir turda kazanan yarışmacı ve yarışmacıların seçimleri ekrana getirilir.
Bu süreç bir yarışmacının 2 tur kazanmasına kadar ilerler. 2 turu kazanan oynu da kazanır.
Oyun kazanıldıktan sonra kazanan kişinin bilgisi, oyun skoru ve oyun boyunca oynanan toplam tur sayısı ekrana getirilir.
Oyun bittikten sonra ilk olarak kullanıcıya daha sonra da bilgisayara oynu tekrar oynamak isteyip istemeyecekleri sorulur.
Kullanıcı ve bilgisayar evet veya hayır cevabını verir. Kullanıcı evet veya hayır cevabını yazmadığı taktirde input hata vermiş olup sistem tekrardan soruyu sorarak evet veya hayır cevabı vermesi gerektiğini bildirir.
Her iki taraf da soruya evet der ise oyun yeniden başlar. Herhangi birisi hayır cevabını verdiği taktirde oyun sonlanır.
