## Laravel 9.* Türkçe dil dosyaları

> "[Laravel Türkiye](http://laravel.gen.tr/)" tarafından Laravel 9.* sürümleri için tercüme edilen ve geliştirilen Laravel Türkçe dil dosyalarıdır.


### Dil dosyası kurulumu

#### Dosyaların kopyalanması

`tr/` dizinini `/resources/lang/` dizini içerisine kopyalayınız, sonuç olarak `/resources/lang/tr/` şeklinde olacaktır.

`tr.json` dosyasını `/resources/lang/` dizini içerisine kopyalayınız, sonuç olarak `/resources/lang/tr.json` şeklinde olacaktır.

#### Laravel yazılımını Türkçe dilde kullanma

`config/app.php` dosyasındaki, `locale` kısmındaki `en` ifadesini `tr` olarak değiştiriniz. Sonuç aşağıdaki gibi olacaktır:

```php
// 'locale' => 'en',
'locale' => 'tr',
```

### Lisans

Açık kaynaklı olan bu proje [MIT lisansı][mit-url] ile lisanslanmıştır.

[mit-url]: http://opensource.org/licenses/MIT
