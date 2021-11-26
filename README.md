# Capstone-Project
Capstone Project bidang Pendidikan

1. create virtual machine menggunakan Azure Portal
2. pilih os dan size sesuai yang diinginkan
3. buat password administration yang digunakan untuk autorisasi virtual machine
4. setelah setup virtual machine sesuai dengan yang diinginkan klik review+create
5. setelah muncul "validation passed" klik create
6. setelah berhasil deployment, klik "go to resources"
7. buka virtual machine kemudian lihat bagian IP Public
8. copy paste IP Public dari virtual machine
9. buka cmd pada windows 10 kemudian masukkan "SSH username@IPPublic"
10. lakukan login menggunakan password dan username yang telah dibuat sebelumnya

# Install Moodle via docker.io
1. lakukan update pada virtual machine setelah masuk ke terminal linux menggunakan cmd dengan perintah "sudo apt update"
2. kemudian lakukan install docker dengan perintah "sudo apt install docker.io"
3. kemudian lakukan download file script Moode melalui perintah "curl -sSL https://raw.githubusercontent.com/bitnami/bitnami-docker-moodle/master/docker-compose.yml > docker-compose.yml"
4. Lakukan Instalasi tools docker-compose dengan perintah "sudo apt install docker-compose"
5. Lakukan eksekusi script dengna perintah "sudo docker-compose up -d"
6. tunggu hingga eksekusi selesai 
7. akses web LMS menggunakan IP Public dari virtual machine 
8. lakukan setup DNS menggunakan layanan penyedia DNS sesuai pilihan
