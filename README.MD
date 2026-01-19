💻 Süreç ve Disk Yönetimi Uygulamaları
Bu proje, bilgisayarın anlık durumunu, çalışan programları ve sistem kaynaklarının kullanımını izlemek için kullanılan temel sistem araçlarını ve komutlarını kapsamaktadır.

🚀 Projenin Amacı
Süreç Yönetimi: CPU ve RAM kullanımına göre süreçleri sıralama ve gerektiğinde sonlandırma (kill).

Disk Analizi: Disk doluluk oranlarını görselleştirme ve sistemi yoran büyük dosyaları tespit etme.

🛠 Linux CLI Yönetim Komutları
1. top (Standart İzleme)
Hemen hemen her Linux dağıtımında yüklü gelen en temel araçtır. Sistem kaynaklarını ve en çok kaynak tüketen işlemleri canlı olarak listeler.

Kullanım: top

Kritik Kısayollar: * q: Çıkış yapar.

M: Bellek (RAM) kullanımına göre sıralar.

P: İşlemci (CPU) kullanımına göre sıralar.

2. htop (Görsel ve İnteraktif)
top komutunun çok daha gelişmiş, renkli ve kullanıcı dostu versiyonudur. İşlemci çekirdeklerini ve RAM miktarını grafiksel olarak sunar.

Kullanım: htop

Öne Çıkan Özellik: Mouse ile tıklama desteği ve F9 tuşu ile işlemleri kolayca sonlandırma yeteneği.

3. ps (Process Status)
Sistemde o an çalışan işlemlerin anlık bir fotoğrafını (snapshot) çeker. İnteraktif değildir, o saniyedeki durumu listeler.Process & Disk Management

Kullanım: ps aux Detayları:

a: Tüm kullanıcıların işlemlerini gösterir.

u: Kullanıcı tabanlı detaylandırma yapar (CPU, RAM %).

x: Bir terminale bağlı olmayan arka plan servislerini listeler.

ps -ef (UNIX Stili)
aux ile benzerdir ancak daha teknik detaylara (Parent Process ID gibi) odaklanır. Genellikle bir işlemin hangi ana işlem tarafından başlatıldığını anlamak için kullanılır.

Öne Çıkan Özellik: Sistemde o an çalışan işlemlerin (process) anlık fotoğrafını (snapshot) çeker ve listeler.



