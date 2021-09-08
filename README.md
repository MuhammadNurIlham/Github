# Github Test Technical Dumbways.id DevOps
# Apa itu DevOps - Devops Dumbways.id
DevOps merupakan singkatan dari dua kata yaitu Development dan Operation. Di mana kedua kata tersebut bermakna menggabungkan proses development/pengembangan dari sebuah sistem/aplikasi dengan operation/operasional. Seperti yang disebutkan sebelumnya, DevOps adalah sebuah prinsip developer untuk mengkoordinasikan antar tim yaitu tim development dengan tim operations dengan efektif dan efisien. Pola pikir yang dibentuk oleh DevOps adalah koordinasi antar tim yang dapat dilakukan dengan cara singkat sehingga tidak membutuhkan banyak pertanyaan. Tim operation atau development cukup mengonfigurasi beberapa komponen yang dibutuhkan melalui prosedur yang dibuat.
# Apa itu CI/CD - DevOps Dumbways.id
CI/CD atau Continues Integration/Continues Deployment adalah “jembatan” antara tim operasional dan development dengan melakukan automasi pembangunan, testing, dan perilisan aplikasi. CI/CD juga berguna dalam membantu developer dan tester dalam melakukan rilis dan update aplikasi atau software dengan lebih cepat dan aman, terutama karena CI/CD dilakukan dalam ‘environment’ yang terstruktur.
# Apa itu Jenkis - DevOps DumbWays.id
Jenkins X adalah sebuah solusi open-source yang menyediakan continuous integration dan continuous delivery (CI/CD) secara otomatis dan sebagai tools pengujian otomatis untuk aplikasi cloud-native di Kubernetes. Jenkins X support untuk semua platform cloud seperti AWS, Google Cloud, IBM Cloud, Microsoft Azure, Red Hat OpenShift, dan Pivotal. Jenkins X adalah sub-proyek Jenkins yang menggunakan otomatisasi sebagai best practices DevOps serta tools untuk meningkatkan kecepatan pengembangan dan meningkatkan keseluruhan proses CI / CD.
# Kelebihan Jenkins : 
Mudah disetup, mempromosikan Environment baru melalui GitOps, Recovery cepat, isolasi, kecepatan, rilis lebih cepat.
# Kekurangan Jenkins : 
Terbatas pada Kubernets. Aspek deploy Jenkins X yang berkelanjutan ditujukan untuk namespace Kubernets, memerlukan akses ke level cluster admin kubernets. jenkins memerlukan akses clusteer admin untuk menentukan dan mengelola sumber daya kubernets. jenkins terbatas pada proyek Git. Jenkins berasumsi bahwa semua pengembang ingin menggunakan Kubernets untuk deploy dan run perangkat lunak meereka serta menggunakan Git untuk kode sumber mereka dan mendifinisikan environment. selain itu fitur tanpa server jenkins hanya berfungsi dengan GitHub untuk saar ini.
# Network Monitoring logs Aplikasi - DevOps DumbWays.id
Netmonk, karena Netmonk merupakan jasa pengembang monitoring jaringan pertama di Indonesia yang dibangun dengan bahasa pemrograman Golang dengan menggunakan React js. Dalam implementasinya yaitu on Cloud system.
Pada on Cloud system, aplikasi Netmonk dan server/VM akan di install ke cloud yang sudah team
siapkan sebelumnya. Sehingga pelanggan hanya memanfaatkan akses aplikasi secara tampilan tanpa repot
untuk me-manage server maupun cloud-nya.
Fiturnya pun terbilang cukup lengkap, di antaranya Dashboard Managerial, Dashboard Operasional, Dashboard Network Map hingga fitur notifikasi melalui Telegram dan email guna mendukung terciptanya pro active monitoring. Fitur ini bisa jadi pembeda Netmonk dengan layanan monitoring lainnya. 
Netmonk basic hadir untuk mempercepat proses pembuatan reporting yang sebelumnya manual (mengolah data excel) menjadi otomatis karena di lengkapi fitur reporting automation. Sekali klik, laporan dapat dilaporkan ke management
# Script installer docker pada Ubuntu - DevOps DumbWays.id
sudo curl -L "https://github.com/docker/compose/releases/download/1.26.0/docker-compose-$(uname -s)-$(uname -m)" -o /usr/local/bin/docker-compose
sudo chmod +x /usr/local/bin/docker-compose
docker-compose --version
