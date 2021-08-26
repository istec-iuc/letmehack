# LetMeHack

- Docker based Cyber Security Training Web Platform (Docker tabanlı Siber Güvenlik Web Eğitim Platformu)

# Gereksinimler

- Docker kurulu bir işletim sistemi gereklidir. (Linux-Windows-Mac)
  
# Kurulum

  1. Öncelikle projeyi indiriniz :  ``` git clone https://github.com/istec-iuc/letmehack.git ```
 
  2. Ardından projedeki labların çalışır hale getirmek için (sql labları hariç) :
  
     - **labs** klasörü içerisine girin, içerisinde **labları ve isimlerini** göreceksiniz.
     
     - Çalıştırmak istediğiniz labın olduğu dizinde ``` docker build -t  <labismi> . ```  şeklinde çalıştırınız. Örnek : ``` docker build -t  ce1 . ``` gibi

     - **Sql Labları için :** 
  
     - _sqli1 labı için_ : İlk önce lab klasörünün( /labs/sqli1 ) içerisindeki **db** klaörünün içerisine girip ``` docker build -t sql_db . ``` komutunu çalıştırın,   daha sonra aynı lab klasörünün içerisindeki **web** klaörünün içerisine girip``` docker build -t sqli1. ``` komutlarını çalıştırınız. 


     - _sqli2 labı için_ : İlk önce lab klasörünün( /labs/sqli2 ) içerisindeki **db** klaörünün içerisine girip ``` docker build -t sql_db2 . ``` komutunu çalıştırın,   daha sonra aynı lab klasörünün içerisindeki **web** klaörünün içerisine girip``` docker build -t sqli2. ``` komutlarını çalıştırınız. 


  3. Ardından ana dizine geri dönün ( indirdiğiniz letmehack klasörünün içerisine )  
  
  4. Şu komutu çalıştırın: ``` docker compose up -d ```
  
  5. ``` Localhost:80 ``` üzerinden projeye tarayıcınızdan erişebilirsiniz.
 

# Projenin Görünümü

![Image of 1](https://cdn.discordapp.com/attachments/861169509288247296/879642386689572894/Ekran_Resmi_2021-08-24_11.19.46.png)
![Image of 3](https://cdn.discordapp.com/attachments/861169509288247296/879642177406377984/Ekran_Resmi_2021-08-24_11.19.58.png)

# Kullanıcı Kayıdı

- Projedeki lablara kayıt olmadan erişmeye çalıştığınızda aşağıdaki gibi bir görüntüyle karşılaşırsınız. LetMeHack projesinde kullanıcı kaydı olmadan lablara erişim mümkün değildir.

![Image of 4](https://cdn.discordapp.com/attachments/861169509288247296/879642178345922560/Ekran_Resmi_2021-08-24_11.21.03.png)

- Bunu çözmek için sitenin sağ üst tarafındaki kayıt butonuna tıklayıp gerekli bilgileri doldurduktan sonra ücretsiz bir şekilde kaydolabilirsiniz. Sonrasında aşağıdaki resimdeki gibi giriş ekranından kullanıcı girişinizi yapabilirsiniz.

![Image of 2](https://cdn.discordapp.com/attachments/861169509288247296/879642163460329523/Ekran_Resmi_2021-08-24_11.23.08.png)

- Artık lablara eriştiğinizde aşağıdaki resimdeki gibi lab başlat butonu aktif olacaktır. Butona tıkladığınızda size atanan **link:port** şeklindeki url ye tıklayarak labı çözmeye başlayabilirsiniz.

![Image of 6](https://cdn.discordapp.com/attachments/861169509288247296/879642188416446484/Ekran_Resmi_2021-08-24_11.22.10.png)

![Image of 7](https://cdn.discordapp.com/attachments/861169509288247296/879642198470180894/Ekran_Resmi_2021-08-24_11.21.59.png)

# İletişim

## LinkedIn:  
  - [Zeynep GÖK](https://www.linkedin.com/in/zeynepgok/)
  - [Emrah YILDIRIM](https://www.linkedin.com/in/emr4h//)
  - [Ömer KELEŞ](https://www.linkedin.com/in/%C3%B6mer-kele%C5%9F-377801175/)
  - [Tugba DÖLEK](https://www.linkedin.com/in/tu%C4%9Fba-d%C3%B6lek/)
  - [Ekin YAZICI](https://www.linkedin.com/in/ekin-yzc-0621b11b3/)
  
  
  
  
  
  
  
  
  






  

                          
                              
    
 
          
  

