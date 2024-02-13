# E-Ticaret Projesi
Projemde, .Net kullanarak geliştirilmiş MVC yapısını kullanan bir web uygulamasıdır. Projemin amacı, ürün satışı gerçekleştirmek ve müşterilerimize kolay ve güvenli bir alışveriş deneyimi sunmaktır. 

Projemde Account, Admin, Home ve Shop adlı dört controller bulunmaktadır. Bu controllerlar, projemin farklı işlevlerini yönetmektedir. Örneğin, Account controllerı, üyelik işlemlerini; Admin controllerı, ürün ekleme ve çıkarma işlemlerini; Home controllerı, ana sayfa ve kategori görüntüleme işlemlerini; Shop controllerı ise, sepete ekleme ve satın alma işlemlerini gerçekleştirmektedir.
Projemizin veri tabanı olarak SQL kullanmaktayız. Veri ilişkileri ise 4 katman olarak tasarlanmıştır. Bu katmanlar şunlardır:

- **Business**: Bu katmanda, projemin iş kuralları tanımlanmıştır. Örneğin, üye olma, giriş yapma, ürün ekleme, çıkarma, güncelleme, satın alma gibi işlemlerin nasıl yapılacağı bu katmanda belirlenmiştir.
Data: Bu katmanda, projemizin veri erişim işlemleri gerçekleştirilmiştir. Örneğin, veri tabanı bağlantısı, sorgu çalıştırma, veri ekleme, silme, güncelleme gibi işlemler bu katmanda yapılmıştır.



