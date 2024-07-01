# Healthy Life

HealthyLife, kullanıcılarına sağlıklı yaşam tarzını teşvik eden çeşitli özellikler sunan bir web uygulamasıdır. 
Healthy Life projesi, kullanıcıların sağlıklı beslenme alışkanlıkları geliştirmelerine yardımcı olan yenilikçi bir yaklaşım sunmaktadır. AI tabanlı önerileri ile kullanıcıların günlük kalori hedeflerine uygun yemek seçenekleri sunarak kişiselleştirilmiş bir deneyim sağlar. Bu proje, teknolojinin sağlık ve beslenme alanındaki potansiyelini gösterirken, aynı zamanda AI'nın sınırlamalarını ve kullanıcı geri bildirimi öneminin altını çizmektedir. Healthy Life, sağlık ve teknoloji alanlarını bir araya getirerek kullanıcıların daha sağlıklı bir yaşam sürdürmelerine yardımcı olmaktadır.

Backend kısmı Django framework'ü kullanılarak geliştirilmiştir. Veritabanı işlemleri MySQl kullanılarak yapılmıştır. Kullanıcıların yemek önerileri sayfası gibi özelliklere erişebilmesi için gerekli olan tüm backend işlemleri sağlanmıştır.

Frontend kısmında tüm sayfalar HTML, CSS ve JavaScript kullanılarak kodlanmıştır. Bu sayfalar kullanıcı dostu ve etkileşimli olacak şekilde tasarlanmıştır.

## Kurulum Adımları

1. Depoyu İndirin:

Proje dosyalarını bilgisayarınıza indirin ve proje dizinine gidin.

2. Veritabanı Migrations Uygulayın:

```bash
python manage.py makemigrations
python manage.py migrate
```

3. Geliştirme Sunucusunu Çalıştırın:

```bash
python manage.py runserver
```

4. Uygulamayı Açın:

Web tarayıcınızı açarak http://127.0.0.1:8000/ adresine gidin.

