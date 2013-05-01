Simple Catalog Engine - Based On CakePHP
========================================

Dibuat untuk Dashboard [PHP Indonesia](http://phpindonesia.net) Regional Jogja

INSTALASI
=========

1. Clone/Download
2. [Setup framework](http://book.cakephp.org/2.0/en/installation.html) (CakePHP)
3. Import database: `app/Config/Schema/phpjogja_catalog.sql`. Atau run this command `php app/Console/cake schema create`
4. LOGIN ADMIN > u: manager, p: 123
5. Selesai

FITUR
=====

1. Product
2. Contact
3. User
4. Language (po mo)

PHING
=====

Sudah disediakan `build.xml` untuk 'automate build' menggunakan [phing](http://phing.info), clear cache & update language.
