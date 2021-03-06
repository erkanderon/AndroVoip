# AndroVoip
This is the Simple Softphone application based on android-ngn-stack library.

###   Projenin Amacı

Bu proje VOIP teknolojisini kullanarak Muğla Üniversitesi içerisindeki öğrencilerin birbiriyle ücretsiz konuşmalarını amaçlayan kurumsal bir projedir.

###   Başlangıç

Projeyi forklayıp cloneladıktan sonra Android Studio içerisine import edebilirsiniz. Başlamadan önce lütfen https://github.com/DoubangoTelecom/imsdroid/ adresindeki dökümentasyonu inceleyiniz.

Test etmek için  adresinden bir profil oluşturunuz.

```sh
https://mdns.sipthor.net/register_sip_account.phtml
```

TODO: Mesajlaşma için XmPP server url'si gir.

```sh
127.0.0.1:8000
```

Not: Aynı kullanıcı ismiyle hesap oluşturmak zorunludur.

###   Activity Akısları

TODO: Hiyerarşi girilcek

###   Proje İçeriği

Bu proje sip2sip.info adresinin sağladığı Asterisk Server üzerinden konuşmayı gerçekleştiriyor.

Profil bilgilerinizi bir Obje içerisinde toplayıp Register etmek için server'a gönderiyor. Server'dan success cevabıyla birlikte sipSession initialize olmuş oluyor. Artık başka bir Sip adresinden gelen aramaları karşılayabilir durumda olmuş olacaksınız.

###  Yapılacaklar

> sip2sip.info ile bağımsız çalışabilmek için bir Server oluşturmak ve Muğla Üniversitelerindeki her öğrenci için bir sip adresi profili oluşturmak.

>Xmpp Server ile mesajlaşma bağımlılıklarından kurtulmak için bir Xmpp Server oluşturmak ve sip profilleri ile uyumlu profiller oluşturmak.

>Rehber oluşturmak

>GPRS ile konum bilgileri alınma.

### Uygulama Arayüzü

<img src="./UIScreen/Screenshot_2016-05-26-15-49-12.png" style="margin-left: 4px;" width="120" height="200">
<img src="./UIScreen/Screenshot_2016-05-26-15-58-05.png" style="margin-left: 4px;" width="120" height="200">
<img src="./UIScreen/Screenshot_2016-05-26-17-35-16.png" style="margin-left: 4px;" width="120" height="200">
<img src="./UIScreen/Screenshot_2016-05-26-17-35-03.png" style="margin-left: 4px;" width="120" height="200">


> **Project Owners:**
> - Hamdi Burak Dilek ---> https://github.com/hamdiburakdilek
> - Erkan Çetinkaya ---> https://github.com/erkanderon
> - Elif Türkay ---> https://github.com/cengelif
