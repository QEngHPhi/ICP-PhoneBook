# ICP-PhoneBook

Merhaba,

2025 Patika.dev Web3 Stajı programına katılmak istiyorum. Hacettepe Üniversitesi Endüstri Mühendisliği 2. sınıf öğrencisiyim ve Ankara'da yaşıyorum. Web3 teknolojileri konusunda çok heyecanlıyım; özellikle Internet Computer Protokolü (ICP) ve Motoko dili ile merkeziyetsiz uygulamalar geliştirme konusunda kendimi geliştirmek istiyorum.

Patika.dev'in sunduğu workshoplar ve topluluk etkinliklerinin bilgi birikimimi artırırken, pratik deneyim kazanmamı da sağlayacağına inanıyorum. Ekip çalışmasına yatkın ve öğrenmeye açık biri olarak bu programa değer katabileceğime inanıyorum.

Bu fırsatın bir parçası olma şansını elde etmek benim için çok önemli. Değerlendirme sürecinde zaman ayırdığınız için şimdiden teşekkür ederim.

Sevgilerimle,
[Metin Bera Süslü]


Staja başvuru için yaptığım PhoneBook projesinde, Motoko dilinde yazdığım basit bir telefon rehberi ve mesaj sistemi uygulaması. Telefon kayıtlarını ve mesajları düzenli bir yapıda saklamaya olanak tanıyor. Kısaca neler yaptığından bahsetmek isterim:

Neler Kullanılıyor?

Map Modülü: Telefon rehberi ve mesaj geçmişini saklamak için kullandım. Anahtar-değer çifti mantığıyla bilgiler tutuluyor.

Text Modülü: İsimler, telefon numaraları ve mesajlar gibi tüm metin bilgilerini temsil ediyor.

Hangi Veriler Tanımlı?

Name: Kışinin ismini ifade ediyor.

Phone: Telefon numarasını metin olarak saklıyor.

Entry: Telefon rehberi kaydını temsil ediyor; açıklama (desc) ve telefon numarasından (phone) oluşuyor.

Message: Mesaj bilgisi; mesajın alıcısı (recipient) ve içeriği (message) var.

Veriler Nereye Kaydediliyor?

phoneBook: Telefon rehberi kayıtlarının saklandığı yer. Burada isimleri anahtar olarak kullandım.

MessageHistory: Gönderilen mesajların kaydedildiği yer. Mesajlar, hangi telefon numarasından gönderildiğini de tutuyor.

Fonksiyonların Yaptıkları:

insert(name : Name, entry : Entry)

Rehbere yeni bir kişi eklemek için kullanılıyor.

Mesela, "Ali" isminde bir kişi eklemek istediğinizde bu fonksiyon yardımcı oluyor.

sendMessage(senderPhone : Phone, message : Message)

Bir mesajı, gönderenin telefon numarasıyla birlikte kaydediyor.

getPhone(name : Name)

Belirli bir ismi arayarak rehberden kaydı getiriyor. Eğer kayıt yoksa null dönüyor.

getMessage(senderPhone : Phone)

Bir telefon numarasına ait gönderilmiş mesajı sorguluyor. Bulursa getiriyor, bulamazsa yine null dönüyor.

Genel Olarak:

Bu kod, telefon rehberi ve mesaj sistemini kolayca birleştiriyor. Yeni kayıt eklemek, mesaj göndermek ve sorgulamalar yapmak basit ve kullanışlı hale geliyor. Kodun yazımı hem öğretici hem de eğlenceli oldu diyebilirim. 😊
