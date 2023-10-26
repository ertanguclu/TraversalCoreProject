# TraversalCoreProje
Traversal Rezervasyon Asp.Net Core 7.0 Mini Proje 


## Proje Hakkında: 
Veri tabanı olarak SQL Server kullanılarak, BusinessLayer, DataAccessLayer, DTOLayer, EntityLayer, PresentationLayer, SignalRApiForSQL ve SingalRConsume katmanlarından oluşan N Tier Architecture mimarisi, ASP.Net Core 7.0 ve Entity Framework Core teknolojileri kullanılarak Codefirst yaklaşımı ile API'lerle desteklenmiş ve kodlanmıştır. Ayrıca MSSQL ve Postgre SQL veri tabanları da kullanılmıştır.


## Aşağıda, proje geliştirme aşamaları sıralı bir şekilde sunulmaktadır:

1. Katmanlar ve projenin genel yapısı belirlendi.
2. Veritabanı işlemleri için Context sınıfı ve migration işlemi gerçekleştirildi.
3. DataAccesLayer ve BusinessLayer Generic Interface'leri kullanılarak veri erişim yapıldı.
4. Repository Design Pattern yaklaşımı kullanılarak veritabanı işlemi gerçekleştirildi.
5. Fluent Validation kütüphanesi kullanılarak giriş yapılan verilerin doğruluğu kontrol edildi.
6. Partial Async ve View Component yapıları kullanılarak performans artırımı sağlandı.
7. MSSQL veritabanı üzerinde CRUD işlemleri yapıldı.
8. Yorumların ait olduğu rotaya göre listeleme ve yaptırma işlemleri gerçekleştirildi.
9. Identity ile kullanıcı girişi yapıldı ve kullanıcının profil bilgileri getirildi.
10. Login ve Register sayfaları oluşturuldu.
11. Custom Identity Validator işlemleri gerçekleştirildi.
12. Identity ile kullanıcı profil ve resim bilgisi güncellemesi yapıldı.
13. Giriş yapmış kullanıcıya ait aktif, onay bekleyen, geçmiş ve yeni rezervasyon sayfaları oluşturuldu.
14. Include metodu ve Ef bağımlılığının kaldırıldı.
15. Container dependencies ve startup yapıları refactoring edildi.
16. 404 not found sayfası oluşturuldu.
17. Hem dinamik hem de statik excel ve pdf raporları sayfaları oluşturuldu.
18. Mail gönderme işlemi yapıldı.
19. Ajax işlemleri yapıldı.
20. Data Transfer Object (DTO) katmanı oluşturuldu ve AutoMapper kullanılarak veri transferi optimize edildi.
21. Api Projesi ana projede kullanıldı.
22. Rapid Api Booking üzerinden otel listesi çekildi.
23. CQRS Design Pattern kullanılarak veri işlemleri ayrıştırıldı.
34. MediatR kütüphanesi kullanılarak işlemler daha düzenli bir şekilde yapıldı.
35. Unit Of Work implementasyonu yapıldı ve veritabanı işlemleri daha yönetilebilir hale getirildi.
36. Api üzerinden ziyaretçi veri seti oluşturuldu.
37. CrossTab kullanılarak ziyaretçiler için pivot tablosu oluşturuldu.
38. SignalR kullanılarak grafikte anlık veri görüntüleme yapıldı.
39. Rol CRUD işlemleri gerçekleştirildi.
40. Çoklu dil desteği ve şifremi unuttum sayfaları oluşturuldu.

## Proje Görselleri

![1](https://github.com/ertanguclu/TraversalCoreProject/assets/96473766/19b7dded-5334-494e-9704-474dd4b9d5ab)
![2](https://github.com/ertanguclu/TraversalCoreProject/assets/96473766/ec844579-5a37-4fb4-958f-8a3fb9f25002)
![3](https://github.com/ertanguclu/TraversalCoreProject/assets/96473766/02d8ff38-43fc-45bf-ac78-7baad1d979ec)
![4](https://github.com/ertanguclu/TraversalCoreProject/assets/96473766/360e6a8a-eeec-44e6-a446-00c627a23d89)
![5](https://github.com/ertanguclu/TraversalCoreProject/assets/96473766/de352fb8-9ab5-4f3e-9e29-07a5979a85af)
![6](https://github.com/ertanguclu/TraversalCoreProject/assets/96473766/47f3f73d-37af-4428-a81c-bbc937a80c9c)
![7](https://github.com/ertanguclu/TraversalCoreProject/assets/96473766/e2ca3487-468e-4292-8c0a-c9158b472626)
![8](https://github.com/ertanguclu/TraversalCoreProject/assets/96473766/51605894-0b15-4199-af42-13369e2bcf1a)
![9](https://github.com/ertanguclu/TraversalCoreProject/assets/96473766/afb1f893-4fae-49d5-9cb7-05081e1b4a1b)
![10](https://github.com/ertanguclu/TraversalCoreProject/assets/96473766/edda702b-43f1-4b8f-8dba-1eac095352d9)
![11](https://github.com/ertanguclu/TraversalCoreProject/assets/96473766/24e91e39-bd31-48ea-8285-181ffe1c29b5)
![12](https://github.com/ertanguclu/TraversalCoreProject/assets/96473766/3b5e3299-6325-4cc7-b03f-361d29e6d4aa)
![13](https://github.com/ertanguclu/TraversalCoreProject/assets/96473766/299cfccf-34de-4664-9048-86f8f5111b8f)
![14](https://github.com/ertanguclu/TraversalCoreProject/assets/96473766/d9615e9f-a783-4a20-8572-7010a7245817)
![15](https://github.com/ertanguclu/TraversalCoreProject/assets/96473766/34f9b0ba-99ff-45f8-8c44-5171b63d698f)
![16](https://github.com/ertanguclu/TraversalCoreProject/assets/96473766/7997a779-dd1a-4110-a5b3-c9b21cefaa54)
![17](https://github.com/ertanguclu/TraversalCoreProject/assets/96473766/120f3229-3673-426b-bb87-0bd4fa8fbecf)
![18](https://github.com/ertanguclu/TraversalCoreProject/assets/96473766/4422fe8f-af55-4a36-b01e-e552c5c7b85c)
![19](https://github.com/ertanguclu/TraversalCoreProject/assets/96473766/e9732c4c-7c87-44fb-af0a-b626ed1cc6ef)
