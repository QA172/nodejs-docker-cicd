<h1 align="center">🚀 Node.js + Docker + GitHub Actions CI/CD</h1>

<p align="center">
  Basit bir Node.js uygulamasını, Docker ile container'layıp GitHub Actions ile otomatik olarak DockerHub’a gönderen bir DevOps projesi 💻🐳
</p>

---

## 📌 Proje Hakkında

Bu proje, Express.js kullanarak geliştirilmiş basit bir web API'dir.  
Amaç, yazılımın değişiklik sonrası otomatik olarak:

1. Docker image olarak build edilmesi
2. GitHub Actions üzerinden otomatik olarak DockerHub’a gönderilmesi

🔁 Yani full otomatik bir **CI/CD pipeline** kurulmuştur.

---

## ⚙️ Kullanılan Teknolojiler

![Node.js](https://img.shields.io/badge/-Node.js-339933?style=flat&logo=node.js&logoColor=white)
![Docker](https://img.shields.io/badge/-Docker-2496ED?style=flat&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/-GitHub%20Actions-2088FF?style=flat&logo=github-actions&logoColor=white)
![Linux](https://img.shields.io/badge/-Linux-FCC624?style=flat&logo=linux&logoColor=black)

---

## 🛠️ Proje Yapısı

```bash
.
├── app.js                   # Express sunucusu
├── Dockerfile              # Docker image tarif dosyası
├── package.json            # Node.js proje konfigürasyonu
├── .github/workflows/
│   └── nodejs.yml          # GitHub Actions workflow dosyası
└── README.md               # Bu dosya 
