# Bulutfon API

**Rest** mimarisinde tasarlanmış Bulutfon API'si, serilizasyon için **JSON**, doğrulama için **OAuth 2** kullanır.

## Request Yapmak

## Doğrulama (=authentication)

## Hataları İdare Etme (=handling errors) 

Eğer Bulutfon'da bir hata olur ise, 5XX hata alırsınız. `5xx` hatası demek uygulamanın o an çöktüğü anlamına gelmesidir. Böyle durumlarda aynı isteği tekrar yapmak api ile geliştirme yapan programcının sorumluluğundadır.

## İstek Limiti

Aynı hesap için aynı ip adresinden XX saniye için XX'e kadar istek yapabilirsiniz. Eğer bu limiti aşarsanız `429 Too Many Requests` statu kodu alırsınız.

# API Kütüphaneleri

# Katkı Sağlayın

Lütfen daha iyi bir API için bizlere yardım edin. Eğer özel bir request talebiniz olur ise veya bir hata bulursanız Github'ın issue servisini kullanın. Düzeltmeleriniz için bu dökümanı çatallayın (=fork) ve pull request gönderin.
