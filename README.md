# Bulutfon API

**Rest** mimarisinde tasarlanmış Bulutfon API'si, serilizasyon için **JSON**, doğrulama için **OAuth 2** kullanır.

## Request Yapmak

## Doğrulama (=authentication)

## Uygulama Kimliği (=user agent)

Bütün istekler headerında `User-Agent` etkiketine sahip olmalıdır. Diğer türlü `400 Bad Request` hatası alırsınız. `User-Agent` bilgilerinizde uygulamanın adı ve iletişim adresiniz mutlaka olmalı.

```
User-Agent: Crm (http://lab2023.com/)
User-Agent: Tayfun Erikan (tayfun.ozis.erikan@lab2023.com) 
```

## Hataları İdare Etme (=handling errors) 

Eğer Bulutfon'da bir hata olur ise, 5XX hata alırsınız. `5xx` hatası demek uygulamanın o an çöktüğü anlamına gelmesidir. Böyle durumlarda aynı isteği tekrar yapmak api ile geliştirme yapan programcının sorumluluğundadır.

## İstek Limiti

Aynı hesap için aynı ip adresinden XX saniye için XX'e kadar istek yapabilirsiniz. Eğer bu limiti aşarsanız `429 Too Many Requests` statu kodu alırsınız.

# API Kütüphaneleri

# Katkı Sağlayın

Lütfen daha iyi bir API için bizlere yardım edin. Eğer özel bir request talebiniz olur ise veya bir hata bulursanız Github'ın issue servisini kullanın. Düzeltmeleriniz için bu dökümanı çatallayın (=fork) ve pull request gönderin.
