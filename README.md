# ChatB929M

Bu proje, ChatB929M adlı özel bir sohbet uygulamasını içerir. Kullanıcılar, anlık mesajlaşma, oda oluşturma ve diğer kullanıcılarla sohbet etme gibi işlevlerle etkileşime geçebilirler.

## Kullanım

Bu uygulamayı yerel bir makineye kurmak için aşağıdaki adımları izleyin:

1. Projeyi bilgisayarınıza klonlayın veya ZIP dosyası olarak indirin.
2. Gerekli Python kütüphanelerini yükleyin:
    ```bash
    pip install Flask flask_socketio flask_login Flask-Session mysql-connector-python
    ```
3. MySQL veritabanını kurun ve bağlantı bilgilerini `config.py` dosyasında yapılandırın.
4. Veritabanı tablolarını oluşturmak için `database.sql` dosyasını kullanın.
5. Flask uygulamasını başlatın:
    ```bash
    python app.py
    ```
6. Tarayıcınızda `http://localhost:5000` adresine giderek uygulamaya erişebilirsiniz.

## Özellikler

- Kullanıcılar, kayıt olabilir ve giriş yapabilir.
- Kullanıcılar, mevcut odalara katılabilir veya yeni odalar oluşturabilir.
- Kullanıcılar, odalarda birbiriyle anlık mesajlaşabilir.
- Odalarda yönetici olan kullanıcılar, odaları düzenleyebilir veya odalardan diğer üyeleri çıkarabilir.
- Oturum bilgileri Flask-Session kullanılarak saklanır.

## Bağlantı Bilgileri

Uygulama, MySQL veritabanını kullanır. Bağlantı bilgileri `config.py` dosyasında yapılandırılmalıdır.

## İletişim

Herhangi bir sorunuz veya geri bildiriminiz varsa, lütfen bize ulaşın veya GitHub üzerinden bir konu başlatın.
