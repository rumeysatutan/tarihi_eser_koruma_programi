# tarihi_eser_koruma_programi

 **Bu projenin amacı tarihi eserlerin korunması için bulunduğu ortamın sıcaklık,basınç verilerinin kontrol edilip belli bir aralıkta tutulması ayrıca hareket algıladığında tarihi eserin bulunduğu yerden alındığına dair uyarı vermesidir. Bu projede Arduino UNO, PIR sensörü, BMP180 basınç sensörü, jumper kablolar ve breadboard kullanılmıştır.**
 
 
 *Ölçme ve Enstrümantasyon Laboratuvar Ödevi
 Rumeysa Tutan 170519030*
 
 
## Arduino Kodu ve Elektronik Bağlantıları

sicaklik_basinc_hareket_sensoru dosyasındaki kodu ve aşağıdaki şekilde bağlantıları yaptığımızda, serial porttan resimde görüldüğü gibi basınç ve sıcaklık sensörlerini okuyabiliyoruz ve eğer hareket algılanırsa kesme gerçekleşiyor ve hareket algılandığına dair uyarı vererek döngüden çıkıyor.

![WhatsApp Image 2022-06-05 at 20 56 54](https://user-images.githubusercontent.com/98033221/172064732-74f5cfc7-844a-4561-8efd-6e2f2ed024a4.jpeg)

Aşağıda serial port çıktısını görebiliriz. Basınç ve sıcaklık verilerini düzenli olarak alırken hareket sensöründen herhangi bir hareket algıladığı zaman döngüden çıkıyor ve uyarı veriyor.

![Ekran görüntüsü 2022-06-05 212159](https://user-images.githubusercontent.com/98033221/172064906-05d94f99-f407-4941-8add-067d2bae1854.jpg)

## Arayüz Hakkında

Labview ile seri haberleştirmeyi gerçekleştiremedim.Aşağıdaki uyarıyı aldım.

![Ekran görüntüsü 2022-06-05 124008](https://user-images.githubusercontent.com/98033221/172067799-f9fbfb80-4d6b-483c-972b-e1f9128808fe.jpg)

Forumlardan araştırdıktan sonra eksik olan NI VISA ve NI SERIAL dosyalarını da yüklediğimde de aşağıdaki gibi hata aldım. Saatlerce araştırmama rağmen sorunu bulamadım.

![Ekran görüntüsü 2022-06-05 162011](https://user-images.githubusercontent.com/98033221/172067925-00c2be40-f006-4057-ac01-48af11297b8e.jpg)
