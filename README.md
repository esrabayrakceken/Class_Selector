# Class_Selector
## Another variant of Css selector is class selector(Css selectorun başka bir çeşidi class selector)
- CSS de öğelere stil vermek için kanca amacıyla kullanılır. Bir class birden fazla öğeye uygulanabilir.
- Öncellikle stil vermek istediğimiz öğelere .html dosyasında class tanımlaması yapıyoruz. Class isimleri anlaşılır ve kısa olmalıdır.
```html
<span class="tag">arms</span>
<span class="tag">gunners</span>
```
- __class="tag":__ arms &gunners kelimeleri için tag adında sınıf tanımlaması yapar.
---
- Daha sonra .css dosyasında class için stil ayarlaması yapıyoruz.
- Verdiğimiz stil hem __arms__ hem de __gunners__ için uygulanır.
```css
.tag {
      background-color:red;
      color:black;
      font-size: 20px; 
}
```
- __.tag:__ "." ve "class ismi" ile birlikte kullanılarak class selector hazırlanır.
- __background-color:__ arms ve gunners kelimelerinin arka planını kırmızı yapar.
- __color:__ kelimelerin text rengini siyaha ayarlar.
- __font-size:__ kelimelerin boyutunu 20px olarak ayarlar.

_iyi kodlamalar.._

