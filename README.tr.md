[🇹🇷 Türkçe](README.md) | [🇬🇧 English](README.en.md)
# 🐳 Dockerized Node.js App  

Bu proje, Docker kullanarak bir **Node.js** uygulamasını konteynerize etmeyi göstermektedir. **MongoDB ve Redis** entegrasyonu ile modern ve taşınabilir bir geliştirme ortamı sunar.  

## Proje Hakkında  
Bu repo, **Docker ve Docker Compose** kullanarak bir **Node.js uygulamasının nasıl çalıştırılacağını** anlatmaktadır. Projede şu bileşenler bulunmaktadır:  
- **Node.js** - Backend geliştirme  
- **Docker & Docker Compose** - Konteyner yönetimi  
- **MongoDB** - Veritabanı yönetimi  
- **Redis** - Önbellekleme  

---

## Kurulum  

### Gereksinimler  
Bu projeyi çalıştırmadan önce aşağıdaki araçların sisteminizde kurulu olması gerekmektedir:  
- [Node.js](https://nodejs.org/)  
- [Docker](https://www.docker.com/)  
- [Docker Compose](https://docs.docker.com/compose/)  

### Projeyi Klonlama  
```sh
git clone https://github.com/sevginuroksuz/simple-item-manager.git
cd simple-item-manager
```

### Bağımlılıkları Yükleme  
```sh
npm install
```

---

## Çalıştırma  

### Docker ile Çalıştırma  
Docker kullanarak tüm servisleri başlatmak için:  
```sh
docker-compose up -d
```

### Manuel Çalıştırma  
Docker olmadan çalıştırmak için:  
```sh
node server.js
```

Uygulamayı **localhost:3000** üzerinden ziyaret edebilirsiniz. 🎉

---

## Dosya Yapısı  

```plaintext
 simple-item-manager
 ├ 📂 src
 ┃ ├ 📄 server.js          # Ana backend dosyası
 ┃ ├ 📄 database.js        # MongoDB bağlantısı
 ┃ └ 📄 cache.js           # Redis entegrasyonu
 ├ 📄 Dockerfile           # Docker yapılandırma dosyası
 ├ 📄 docker-compose.yml   # Çoklu konteyner yönetimi
 ├ 📄 package.json         # Bağımlılıklar
 ├ 📄 README.md            # Proje açıklaması
 └ 📄 .gitignore           # Gereksiz dosyaları hariç tutar
```

---

## Lisans  
Bu proje **MIT Lisansı** ile sunulmaktadır. Daha fazla bilgi için [LICENSE](LICENSE) dosyasını inceleyebilirsiniz.  

---

**Projeyi beğendiyseniz, ⭐ vererek destek olabilirsiniz!**  

