# tas_kagit_makas_ELIF_HANEDAN

# Taş, Kağıt, Makas Oyunu

Bu Python projesi, klasik "Taş, Kağıt, Makas" oyununu konsol tabanlı bir uygulama olarak şeklinde sunar. Kullanıcı ile bilgisayar arasında oynanan bu oyunun kuralları şu şekildedir; oyuncular sırayla taş, kağıt veya makas seçer ve kurallara göre bir kazanan belirlenir.

## Özellikler

- **Zorluk Seviyeleri**:Bu oyunda kolay, orta ve zor olmak üzere üç zorluk seviyesi vardır. Her seviyede oyuncunun bir turu tamamlaması için farklı süre sınırları bulunur.
- **ASCII Sanatı**: Seçilen taş, kağıt veya makas seçeneklerinin ASCII sanatını gösterir, bu da oyuna görsel bir keyif katmaktadır.
- **Tur ve Oyun Galibiyetleri**: Oyun, oyuncu veya bilgisayar iki tur kazanana kadar devam eder. Her iki oyuncu da bir tur kazandığında, son tur için özel bir mesaj gönderilmektedir.
- **Sonuçlar**: Oyun bitiminde kullanıcıya genel skorlar (kazanılan ve kaybedilen oyunlar) sunulur.
- **Tekrar Oynama**: Oyuncu, oyunun sonunda tekrar oynamayı tercih edebilir.

## Kullanım

### Kurulum

Projeyi çalıştırmadan önce gerekli olan `pygame` modülünü yüklemeniz gerekebilir. Yüklemek için aşağıdaki komutu kullanabilirsiniz:

pip install pygame


### Oyun Nasıl Oynanır?

1. Oyunu başlattıktan sonra, zorluk seviyenizi seçin.
2. Her turda, size verilen süre içinde "Taş", "Kağıt" veya "Makas" seçeneklerinden birini seçip, yazın.
4. Seçiminizi yaptıktan sonra, bilgisayarın seçimi ile karşılaştırılır ve tur sonucu ekranda gösterilir.
5. İlk iki turu kazanan oyunu kazanır. Eğer bir tur berabere biterse, o tur tekrarlanır.
6. Oyun sonunda kazanan açıklanır ve tekrar oynamak isteyip istemediğiniz sorulur.

### Oyun Kuralları

- **Taş**: Makas'ı yener.
- **Kağıt**: Taş'ı yener.
- **Makas**: Kağıt'ı yener.

## Katkıda Bulunma

Bu projeye katkıda bulunmak için lütfen bir `pull request` gönderin veya herhangi bir sorunuz varsa [issue](#) açın.

## Lisans

Bu proje MIT Lisansı ile lisanslanmıştır. Daha fazla bilgi için [LICENSE](LICENSE) dosyasına bakabilirsiniz.
