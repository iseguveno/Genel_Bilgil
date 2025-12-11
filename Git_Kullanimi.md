### Git Nedir?
- GIT nedir? Bir versiyon kontrol sistemidir. Yani  Bir döküman üzerinde yaptığınız degişiklikleri adım adım izleyen, istediğinizde kayıt eden ve isterseniz bunu internet üzerindeki bir bilgisayarda veya yerel bir cihazda (respository / repo / depo) saklamanızı ve yönetmenizi sağlayan bir sistemdir. 
- Linux'un mimarı Linus Torvalds dan yazılmış. 2005
---
 ### Git Niçin Kullanılır ?
- Bilgisayarınızda ve internette (Github gibi) dosyalarınızı ve versiyon kontrol bilgilerinizi depolayabilirsiniz.
- "commit" yaparak SnapShot (anlık görüntü) ile dosyaların o anki halini kayıt altına alabilirsiniz. Böylelikle ileride bir hata ile karşılaşırsanız herhangi bir zamandaki herhangi bir versiyona dönüş yapabilirsiniz.

- Kişilerin aynı projede çalışmasını sağlar. Proje üstünde Yapılan değişiklikleri görebilirsiniz.
- Projede versiyonlanmasını istemediğiniz dosyaları belirtebilirsiniz. (key,log .. gibi)
---
### Git Komutları
- ***Git İşleyiş şeması***

 ![Git_calisma](./Dokuman/3-GitHub-cheat-sheet-graphic.jpg)

 1- **git init** 
-versiyon kontol işlemi yapmak istediğimiz dosyada bu komutu çalıştırırız.

 ![Git_calisma](./Dokuman/git_init.png)
 
 "Genel_Bilgi" klasörü için git versiyon işlemi başlamıştır.

  2- **git config**

*git*  ile ilgili konfigirasyon ayarları yapmayı sağlar.
- " *git config --list --show-origin* " komutu  Tüm ayarlarınızı ve onların nereden geldiğini görmek için şu komutu kullanabilirsiniz.
- Git’i ilk kurduğunuzda yapmanız gereken ilk şey, kullanıcı adınızı ve e-postanızı belirlemek olmalıdır. Bunu yapmak önemlidir çünkü her Git katkısı (commit) bu bilgileri kullanır ve tüm işlediğiniz katkılara değişmez bir şekilde gömülmüştür.

- " *git config --global user.name* " komutu  tanımlı olan kullanıcı ismini verir.
- " *git config --global email.name* " komutu  tanımlı olan email ismini verir.


user ve email ayarlamak için:

- " *git config --global user.name "user_name"* "
- " *git config --global email.name "email_adresi"* " komutları kullanılır.