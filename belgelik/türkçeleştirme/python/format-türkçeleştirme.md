# Ön Bilgiler
**Amaç:** Türkçeleştirme

**Dil:** Python

**Konu:** format()

**Başlangıç Güngeni:** 20 11 2020

**Düzey:** Başlangıç 

# "format" Sözcüğünün Kökeni
![Görsel](/belgelik/görseller/kökenbilim/format.png)

- **formare**(Latince) > **formatus liber**(Latince) > **format**(Fransızca+Almanca)

# format() Kullanımı

**AÇIKLAMA**
`format()`yöntemi, verilen dizeyi Python'da daha güzel bir çıktıya biçimlendirir.`format()` yöntemi, biçimlendirme için basit yer tutucuların kullanılmasına izin verir.

**GİRDİ**
```
# default arguments
print("Hello {}, your balance is {}.".format("Adam", 230.2346))

# positional arguments
print("Hello {0}, your balance is {1}.".format("Adam", 230.2346))

# keyword arguments
print("Hello {name}, your balance is {blc}.".format(name="Adam", blc=230.2346))

# mixed arguments
print("Hello {0}, your balance is {blc}.".format("Adam", blc=230.2346))
```
**ÇIKTI**
```
Hello Adam, your balance is 230.2346.
Hello Adam, your balance is 230.2346.
Hello Adam, your balance is 230.2346.
Hello Adam, your balance is 230.2346.
```

# "format" Sözcüğünü Türkçeleştirme
**Format** sözcüğü Türkçede **biçim,boyut** gibi anlamlara gelir.

# format() Kullanımının Türkçeye Uyarlanması

**AÇIKLAMA**
`bicim()`yöntemi, verilen dizeyi Python'da daha güzel bir çıktıya biçimlendirir.`bicim()` yöntemi, biçimlendirme için basit yer tutucuların kullanılmasına izin verir.

**GİRDİ**
```
# varsayılan argüman
yazdir("Merhaba {}, senin bakiyen {}.".bicim("Ahmet", 230.2346))

# konumsal argüman
yazdir("Merhaba {0}, senin bakiyen {1}.".bicim("Ahmet", 230.2346))

# anahtar kelime argümanı
yazdir("Merhaba {isim}, senin bakiyen {bakiye}.".bicim(isim="Ahmet", bakiye=230.2346))

# karışık argüman
yazdir("Merhaba {0}, senin bakiyen {bakiye}.".bicim("Ahmet", bakiye=230.2346))
```
**ÇIKTI**
```
Merhaba Ahmet, senin bakiyen 230.2346.
Merhaba Ahmet, senin bakiyen 230.2346.
Merhaba Ahmet, senin bakiyen 230.2346.
Merhaba Ahmet, senin bakiyen 230.2346.
```
# Ek Bilgiler - Nedenler - Açıklamalar
