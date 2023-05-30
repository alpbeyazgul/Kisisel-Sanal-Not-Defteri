# Sanal Not Defteri

Sanal Not Defteri, kullanıcıların notlarını kaydedebileceği, düzenleyebileceği ve paylaşabileceği bir web uygulamasıdır.

## Dosyalar

- `index.html`: Ana sayfa HTML dosyası.
- `notes.html`: Notların listelendiği HTML dosyası.
- `js/main.js`: Ana JavaScript dosyası, not ekleme ve düzenleme işlevlerini içerir.
- `js/storage.js`: Tarayıcı yerel depolama işlevlerini içeren JavaScript dosyası.
- `css/style.css`: Uygulama için CSS dosyası, görünüm ve düzenlemeleri içerir.
- `images/`: Uygulama için kullanılan görsellerin bulunduğu klasör.
- `database/connection.php`: Veritabanı bağlantısı için PHP dosyası.
- `database/create_table.php`: Notlar tablosunu oluşturmak için PHP dosyası.
- `database/insert_note.php`: Not eklemek için PHP dosyası.
- `database/get_notes.php`: Tüm notları getirmek için PHP dosyası.
- `readme.md`: Proje hakkında bilgi ve açıklamaların yer aldığı Markdown dosyası.
- `installation_guide.md`: Detaylı kurulum rehberini içeren Markdown dosyası.

## Kurulum

1. Projeyi indirin veya klonlayın.
2. Web sunucusunda projenin kök dizinini belirleyin.
3. Veritabanı bağlantısı için `database/connection.php` dosyasında gerekli yapılandırmaları yapın.
4. Notları saklamak için gereken veritabanı tablosunu oluşturmak için `database/create_table.php` dosyasını çalıştırın.
5. Projenin ana sayfası olan `index.html` dosyasını tarayıcınızda açarak uygulamayı başlatın.

Aşağıda proje için gereken dosya ve klasör yapısını ve içeriklerini bulabilirsiniz:

├── index.html
├── notes.html
├── js/
│   ├── main.js
│   ├── storage.js
│   └── ...
├── css/
│   ├── style.css
│   └── ...
├── images/
│   ├── note.png
│   └── ...
├── database/
│   ├── connection.php
│   ├── create_table.php
│   ├── insert_note.php
│   ├── get_notes.php
│   └── ...
├── readme.md
└── installation_guide.md
