# Ön Bilgiler
**Amaç:** Türkçeleştirme

**Dil:** Python

**Konu:** encode()

**Başlangıç Güngeni:** 19 11 2020

**Düzey:** Başlangıç | Askıda | Bütülmüş

# "???????" Sözcüğünün Kökeni
![Görsel](/belgelik/görseller/kökenbilim/encode.png)

- **codex**(Latin) + **codic**(Latin) > **codex**(İngilizce) > **en** + **code**(Orta İngilizce) > **encode**

# encode() Kullanımı

**AÇIKLAMA**
`encode()` yöntemi, verilen dizenin kodlanmış sürümünü döndürür.

**GİRDİ**
```
string = 'pythön!'

print('The string is:', string)

string_utf = string.encode()

print('The encoded version is:', string_utf)
```
**ÇIKTI**
```
The string is: pythön!
The encoded version is: b'pyth\xc3\xb6n!'
```

# "encode" Sözcüğünü Türkçeleştirme
**encode** sözcüğü Türkçede **kodlamak,şifrelemek** gibi anlamlara gelir.

# encode() Kullanımının Türkçeye Uyarlanması

**AÇIKLAMA**
`sifreleme()` yöntemi, verilen dizenin kodlanmış sürümünü döndürür.

**GİRDİ**
```
dizi = 'pythön!'

yazdir('Dize:', dizi)

dizi_utf = dizi.sifreleme()

yazdir('Şifrelenmiş sürümü:', dizi_utf)
```
**ÇIKTI**
```
Dize: pythön!
Şifrelenmiş sürümü: b'pyth\xc3\xb6n!'
```
# Ek Bilgiler - Nedenler - Açıklamalar
