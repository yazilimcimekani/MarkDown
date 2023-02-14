<h1 align="center">MarkDown Rehberi</h1>

MarkDown ve Html syntaxlarını birleştirerek, daha güzel gözüken ve kullanışlı MarkDown dosyaları oluşturma rehberi.

- [Başlıklar](#başlıklar)
- [Sırasız Listeler](#sırasız-listeler)
- [Sıralı Listeler](#sıralı-listeler)
- [Yazı Stilleri](#yazı-stilleri)
    - [İtalik yazı](#i̇talik-yazı)
    - [Kalın yazı](#kalın-yazı)
    - [Üstü çizili yazı](#üstü-çizili-yazı)

# Başlıklar

MarkDown ile Yazımı: 

```md
# Başlık
```

Html ile Yazımı:

```html
<h1>Başlık</h1>
```

Çıktı:

![Başlık Çıktısı](./assets/baslik-0.png)

# Sırasız Listeler

MarkDown ile Yazımı: 

```md
- Madde 1
- Madde 2
- Madde 3
```
> `-` Yerine `*` veya `+` işaretleri de kullanabilir.

Html ile Yazımı:

```html
<ul>
    <li>Madde 1</li>
    <li>Madde 2</li>
    <li>Madde 3</li>
</ul>
```

Çıktı:

![Sırasız Liste Çıktısı](./assets/liste-0.png)

# Sıralı Listeler

MarkDown ile Yazımı: 

```md
1. Madde 1
2. Madde 2
3. Madde 3
```

Html ile Yazımı:

```html
<ol>
    <li>Madde 1</li>
    <li>Madde 2</li>
    <li>Madde 3</li>
</ol>
```

Çıktı:

![Sıralı Liste Çıktısı](./assets/liste-1.png)

# Yazı Stilleri

## İtalik yazı

MarkDown ile Yazımı: 

```md
*İtalik Yazı*
```

Html ile Yazımı:

```html
<i>İtalik Yazı</i>
```

Çıktı:

![İtalik Yazı Çıktısı](./assets/yazi-stilleri-0_italik.png)

## Kalın Yazı

MarkDown ile Yazımı: 

```md
**Kalın Yazı**
```

> Hem italik hem kalın yazı için `***Hem Kalın Hem İtalik Yazı***`

Html ile Yazımı:

```html
<b>Kalın Yazı</b>
```

> Hem italik hem kalın yazı için `<i><b>Hem Kalın Hem İtalik Yazı</b></i>`

Çıktı:

![Kalın Yazı Çıktısı](./assets/yazi-stilleri-1_kalin.png)

## Üstü Çizili Yazı

MarkDown ile Yazımı: 

```md
~~Üstü çizili yazı örneği~~
```

Html ile Yazımı:

```html
<strike>Üstü çizili yazı örneği</strike>
```

Çıktı:

![Üstü Çizili Yazı Çıktısı](./assets/yazi-stilleri-2_ustu-cizili.png)
