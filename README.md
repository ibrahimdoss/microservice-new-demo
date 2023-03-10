# microservice-new-demo

# Product Service With SpringBoot Microservices

    1- Product Service : Ürünlerin oluşturulup görüntülendiği bir ürün kataloğu görevi gören servis. 
    2- Order Service : Ürünlerin sipariş edilebildiği servis.
    3- Inventory Service : Ürünlerin stokta olup olmadığını kontrol eden servis. 
    4- Notification Service : Sipariş verildikten sonra bildirim gönderebilir (e-mail gibi)

    * Order Service, Inventory Service ve Notification Service birbiriyle etkileşimde olacaklardır.

   <hr> <br>

 ## Projenin Diagramı : 
    
   ![sttt](https://user-images.githubusercontent.com/96151920/176319634-fc40477c-f40e-4304-bb74-555b03d5ed96.JPG)
    
    * Product Service (MongoDb)
    * Order Service (PostgreSQL)
    * Order Service ile Notification Service arasındaki ilişli Asenkron olacak. (RabbitMQ)
    * Order Service ile Inverntory Service arasındaki ilişli Senkronize olacak. (PostgreSQL)

<hr> <br>

## PRODUCT-SERVICE

* Product Katmanlı Mimari tabanları oluşturuldu. 
  * Model -> Product
  * Dao -> ProductRepository 
  * Dto -> ProductRequest
  * Controller -> ProductController
  * Service -> ProductService 

<hr><br>

   ![sttt](https://github.com/ibrahimdoss/microservice-new-demo/blob/main/images/github_add.png)
   ![sttt](https://github.com/ibrahimdoss/microservice-new-demo/blob/main/images/Screenshot%202023-01-29%20153858.png)
   ![sttt](https://github.com/ibrahimdoss/microservice-new-demo/blob/main/images/Screenshot%202023-01-29%20153814.png)
   ![sttt](https://github.com/ibrahimdoss/microservice-new-demo/blob/main/images/Screenshot%202023-01-29%20153802.png)
   ![sttt](https://github.com/ibrahimdoss/microservice-new-demo/blob/main/images/Screenshot%202023-01-29%20153639.png)
  


