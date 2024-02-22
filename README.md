# http_get
# HTTP GET Örneği

Bu örnek uygulama, Texas Instruments Tiva C Series TM4C1294XL mikrodenetleyici kartı üzerinde çalışan bir HTTP istemcisi örneğidir. Bu uygulama, belirtilen bir URL'ye HTTP GET isteği gönderir ve yanıtı alır. İletişim için bir HTTP istemcisi kullanılarak TCP/IP üzerinden HTTP protokolü kullanılır.

## Kod Açıklaması

Bu kod bloğu aşağıdaki işlevleri gerçekleştirir:

- Belirtilen bir URL'ye HTTP GET isteği gönderir.
- HTTP yanıtını alır ve yanıt metnindeki sıcaklık verisini arar.
- Sıcaklık verisini bulduğunda, bu veriyi bir değişkene kopyalar ve konsola yazdırır.
- Belirli bir süre sonra tekrar HTTP GET isteği gönderir ve işlemi tekrarlar.

## Kullanılan Donanım ve Kütüphaneler

- Texas Instruments Tiva C Series TM4C1294XL mikrodenetleyici kartı
- TI-RTOS (TI Gerçek Zamanlı İşletim Sistemi)
- TI-DRIVERS Kütüphanesi
- TI-NET Kütüphanesi
- TI-HTTP Kütüphanesi


