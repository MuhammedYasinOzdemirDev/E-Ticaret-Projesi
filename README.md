![image](https://github.com/MuhammedYasinOzdemirDev/E-Ticaret-Projesi/assets/94251353/4b18b63d-8f8e-4492-82ce-19d5c8c59162)![image](https://github.com/MuhammedYasinOzdemirDev/E-Ticaret-Projesi/assets/94251353/50f4dd67-10f2-4198-beab-a9571a1052b8)# E-Ticaret Projesi
Projemde, .Net kullanarak geliştirilmiş MVC yapısını kullanan bir web uygulamasıdır. Projemin amacı, ürün satışı gerçekleştirmek ve müşterilerimize kolay ve güvenli bir alışveriş deneyimi sunmaktır. 

Projemde Account, Admin, Home ve Shop adlı dört controller bulunmaktadır. Bu controllerlar, projemin farklı işlevlerini yönetmektedir. Örneğin, Account controllerı, üyelik işlemlerini; Admin controllerı, ürün ekleme ve çıkarma işlemlerini; Home controllerı, ana sayfa ve kategori görüntüleme işlemlerini; Shop controllerı ise, sepete ekleme ve satın alma işlemlerini gerçekleştirmektedir.
Projemizin veri tabanı olarak SQL kullanmaktayız. Veri ilişkileri ise 4 katman olarak tasarlanmıştır. Bu katmanlar şunlardır:

- **Business**: Bu katmanda, projemin iş kuralları tanımlanmıştır. Örneğin, üye olma, giriş yapma, ürün ekleme, çıkarma, güncelleme, satın alma gibi işlemlerin nasıl yapılacağı bu katmanda belirlenmiştir.
- **Data**: Bu katmanda, projemizin veri erişim işlemleri gerçekleştirilmiştir. Örneğin, veri tabanı bağlantısı, sorgu çalıştırma, veri ekleme, silme, güncelleme gibi işlemler bu katmanda yapılmıştır.
- **Entity**: Bu katmanda, projemin veri modelleri tanımlanmıştır. Örneğin, User, Product, Category, Order gibi sınıflar bu katmanda oluşturulmuştur. Bu sınıfların özellikleri ve ilişkileri de bu katmanda belirtilmiştir.
- **WEBUI**: Bu katmanda ise, projemin arayüz tasarımı ve kullanıcı etkileşimi gerçekleştirilmiştir. Örneğin, HTML, CSS, JavaScript gibi teknolojiler kullanılarak projemizin görünümü ve işlevselliği sağlanmıştır.
Projemin birçok özellik bulunmaktadır. Bunlardan bazıları şunlardır:
- **Üyelik**: Kullanıcılarımız projemin üye olabilir veya varsa mevcut hesaplarıyla giriş yapabilirler. Üyelik işlemleri için Account controllerını kullanmaktayım.
- **Ürün ekleme ve çıkarma**: Admin yetkisine sahip olan kullanıcılarımız projeme yeni ürünler ekleyebilir veya mevcut ürünleri çıkarabilirler. Ürün ekleme ve çıkarma işlemleri için Admin controllerını kullanmaktayım.
![image](https://github.com/MuhammedYasinOzdemirDev/E-Ticaret-Projesi/assets/94251353/e58a47ab-37b9-4eaa-a4a6-d285d72551fe)



  



