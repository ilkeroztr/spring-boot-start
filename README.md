# SPRING-BOOT PROJE
Bu proje, Spring Boot ile oluşturulmuş basit bir web uygulamasıdır. Uygulamanın amacı, temel bir REST endpoint'ini çalıştırarak Spring Boot ortamını test etmektir.
##  Proje Hakkında

- `Spring Boot` framework’ü ile geliştirilmiştir.
- Ana endpoint: `/`
- Tarayıcıdan veya Postman üzerinden `http://localhost:8080/` (ya da benim örneğimde `8088`) adresine GET isteği gönderildiğinde şu mesaj döner:
  Proje test, başarıyla çalışıyor. İlker Öztürk
  ##  Kullanılan Teknolojiler

- Java 17
- Spring Boot 3.2.4
- Maven

##  Çalıştırma

Projeyi kendi bilgisayarınızda çalıştırmak için:

1. Maven yüklü olduğundan emin olun.
2. Terminalde proje klasörüne gidin.
3. Aşağıdaki komutu çalıştırın:

```bash
mvn spring-boot:run
```
Alternatif olarak farklı bir portta çalıştırmak için:
```bash
mvn spring-boot:run -Dspring-boot.run.arguments=--server.port=8088
```
📁 Proje Yapısı
springboot-ex-05/
├── pom.xml
└── src/
    └── main/
        └── java/
            └── com/
                └── example/
                    └── demo/
                        └── DemoApplication.java
Test
	•	Uygulama başlatıldığında loglarda Tomcat’in başlatıldığını görebilirsiniz.
	•	Tarayıcınızda belirtilen adrese giderek uygulamanın çalışıp çalışmadığını test edebilirsiniz.
