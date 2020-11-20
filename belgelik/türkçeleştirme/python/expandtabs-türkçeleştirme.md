# Ön Bilgiler
**Amaç:** Türkçeleştirme

**Dil:** Python

**Konu:** expandtabs()

**Başlangıç Güngeni:** 20 11 2020

**Düzey:** Başlangıç 

# "expand" Sözcüğünün Kökeni
![Görsel](/belgelik/görseller/kökenbilim/expand.png)

- **ex**(Latince) + **pandere**(Latince) > **expandere**(Latince) > **expand**(Orta İngilizce)

# "tab" Sözcüğünün Kökeni
![Görsel](/belgelik/görseller/kökenbilim/tab.png)

- **tag**(İngilizce) > **tab**(Orta İngilizce)

# "expandtabs" Sözcüğünün Kökeni

- **expand** + **tag** + **s**

# expandtabs() Kullanımı

**AÇIKLAMA**
`expandtabs()` yöntemi, tabsize parametresinin bir sonraki katına kadar tüm sekme karakterleri '\ t' beyaz boşluk karakterleriyle değiştirilmiş bir dize kopyası döndürür.

**GİRDİ**
```
str = 'xyz\t12345\tabc'
# Varsayılan sekme sayısı 8'dir.
result = str.expandtabs()

print(result)
```
**ÇIKTI**
```
xyz     12345   abc
```

# "expandtabs" Sözcüğünü Türkçeleştirme
**expandtabs** sözcüğü Türkçede **genişletme sekmeleri** gibi anlamlara gelir.

# expandtabs() Kullanımının Türkçeye Uyarlanması

**AÇIKLAMA**
`sekmegenislet()` yöntemi, tabsize parametresinin bir sonraki katına kadar tüm sekme karakterleri '\ t' beyaz boşluk karakterleriyle değiştirilmiş bir dize kopyası döndürür.

**GİRDİ**
```
dizi = 'xyz\t12345\tabc'
# Varsayılan sekme sayısı 8'dir.
sonuc = dizi.sekmegenislet()

yazdir(sonuc)
```
**ÇIKTI**
```
xyz     12345   abc
```
# Ek Bilgiler - Nedenler - Açıklamalar
