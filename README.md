# Smartlead AI

Smartlead AI, işletmelerin müşterileriyle olan iletişim süreçlerini daha düzenli ve verimli bir şekilde yönetebilmesi amacıyla geliştirilmiş Python tabanlı bir uygulamadır.

Proje kapsamında Python, Flask ve Wix arasında haberleşme sağlanması ve işletme bilgilerinin sistem içerisinde kullanılabilmesi amaçlanmaktadır.

## Projenin Amacı

Bu projenin temel amacı, işletmelerden alınan bilgilerin Python tabanlı bir sistem tarafından işlenmesi ve yapay zekâ destekli iletişim süreçlerinde kullanılabilecek bir yapının oluşturulmasıdır.

Sistem ile;

- İşletme bilgilerinin alınması
- İşletme verilerinin işlenmesi
- Python ve Wix arasında veri alışverişi yapılması
- Web tabanlı bir arayüz üzerinden sisteme erişilmesi
- İşletme bilgilerinin yapay zekâ destekli işlemlerde kullanılabilmesi

hedeflenmektedir.

## Kullanılan Teknolojiler

Projede aşağıdaki teknolojiler kullanılmıştır:

- Python
- Flask
- Requests
- HTML
- Wix
- GitHub
- Visual Studio Code

## Proje Yapısı

```text
Smartlead_ai/
│
├── app/
│   ├── modules/
│   │   └── assistant.py
│   │
│   ├── templates/
│   │   ├── dashboard.html
│   │   └── index.html
│   │
│   ├── __init__.py
│   ├── app.py
│   ├── database.py
│   └── routes.py
│
├── .env
├── .gitignore
├── config.py
├── requirements.txt
├── run.py
└── README.md
