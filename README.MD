# 💻 Süreç ve Disk Yönetimi Uygulamaları

Bilgisayarın anlık durumunu, çalışan programları ve sistem kaynaklarının kullanımını izlemek için kullanılan temel sistem araçlarını ve komutlarını kapsamaktadır.

## 🚀 Projenin Amacı
* **Süreç Yönetimi:** CPU ve RAM kullanımına göre süreçleri sıralama ve gerektiğinde sonlandırma (kill).
* **Disk Analizi:** Disk doluluk oranlarını görselleştirme ve sistemi yoran büyük dosyaları tespit etme.

---

## 🛠 Linux CLI Yönetim Komutları

### 1. `top` (Standart İzleme)
Hemen hemen her Linux dağıtımında yüklü gelen en temel araçtır. Sistem kaynaklarını ve en çok kaynak tüketen işlemleri canlı olarak listeler.

* **Kullanım:** `top`
* **Kritik Kısayollar:** * `q`: Çıkış yapar.
    * `M`: Bellek (RAM) kullanımına göre sıralar.
    * `P`: İşlemci (CPU) kullanımına göre sıralar.

### 2. `htop` (Görsel ve İnteraktif)
`top` komutunun çok daha gelişmiş, renkli ve kullanıcı dostu versiyonudur. İşlemci çekirdeklerini ve RAM miktarını grafiksel olarak sunar.

* **Kullanım:** `htop`
* **Öne Çıkan Özellikler:** Mouse ile tıklama desteği ve `F9` tuşu ile işlemleri kolayca sonlandırma yeteneği.

### 3. `ps` (Process Status)
Sistemde o an çalışan işlemlerin anlık bir fotoğrafını (snapshot) çeker. İnteraktif değildir, o saniyedeki durumu listeler.

* **`ps aux`**: Tüm kullanıcıların işlemlerini detaylı listeler.
* **`ps -ef`**: İşlemleri ana işlem kimlikleri (PPID) ile birlikte gösterir.

---

## 📂 Disk Yönetimi
* **`df -h`**: Disk doluluk oranlarını görselleştirir.
* **`du -sh *`**: Büyük dosyaları ve klasör boyutlarını tespit etmek için kullanılır.

## Projenin amacı

###CPU ve RAM kullanımına göre süreçleri sıralama ve sonlandırma (kill).

###Disk doluluk oranlarını görselleştirme.

###Büyük dosyaları bulma.



