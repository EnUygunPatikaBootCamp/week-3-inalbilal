
## Symfony kullanmanın avantajları nedir? Kendi cümlelerinizle açıklayınız.
- Yinelenen ve gereksiz kodaların önlenebilmesi, daha güveli bir web ortamının oluşturulması ve hataların kolayca ayıklanabilmesi Symfony kullanmanın temel avantajları olarak gösterilebilir. Symfony'nin kapsamlı kütüphaneleri sayesinde yüzlerce satır kod yazmaktan kurtulmak ta büyük bir avantajıdır.

## Symfony ile environment (ortam) ayarlaması nasıl yapılır?

- Symfony projemizi oluşturduktan sonra default olarak bir ortam dosyası gelmektedir. Dosyamızın ismi ".env". Bu dosya projelerde çeşitli database  bağlantılarını (MySQL, PostgreSQ, SQLite...) yapmak için kullanılır. MySQL serverımızı başlattıktan sonra dosya içerisinde database bilgilerimizi girmeliyiz. Bu bağlatını şu şekilde gerçekleşmektedir; 

  - mysql://<b>USERNAME</b>:<b>PASSWORD</b>@<b>HOST</b>/<b>DATABASE_NAME</b>?serverVersion=<b>MYSQL_VERSION</b>


## Yeni bir Symfony projesi oluşturmak için kullanılan composer komutu nedir? Alternatif bir komutla Symfony projesi oluşturabilir miyiz?
- Composer, PHP için geliştirilmiş bir paket yönetim sistemidir. Composer sayesinde yeni Symfony projeleri oluşturabilir ve çeşitli kütüphaneleri yükleyebiliriz. Composer ile Symfony Web projesi oluşturmak için şu komutlar kullanılır;
  - composer create-project symfony/skeleton:"^5.4" my_project_directory
  - cd my_project_directory
  - composer require webapp
    
- Buna alternatif olarak Symfony Web projesi oluşturmak için şu komut kullanılır;
  - symfony new my_project_directory --version=5.4 --webapp


## Laravel framework ve Symfony framework arasındaki temel farklardan iki tanesini yazınız.
- Günümüzde yaygın olarak kullanılan bu iki PHP framework'ü birbirinden ayıran birkaç temel fark vardır. Symfony, bir dizi yeniden kullanılabilir PHP bileşeni ve kütüphanesi içeren bir PHP frameworktür. Laravel ise Symfony tabanlı ücretsiz, açık kaynaklı bir PHP frameworktür. 