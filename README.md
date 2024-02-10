## PROJEK MONITORING MENGGUNAKNA GRAFANA DAN PROMETEUS DENGAN DOCKER 
# BELUM MENGGUNAKNA NODE EXPORTER

1. INSTALL DOCKER
2. BUAT CODE.yml -> copy config docker-compose.yml
3. BUAT CODE.yml -> prometheus.yml pada direktori prometheus (seperti pada sintak di docker-compose yang dibuat sebelumnya)
4. Command DOCKER : 
    1. docker-compose up -d --> untuk running docker-compose.yml 
    2. docker ps --> untuk melihat apakah image yang dibuat sudah berhasil running atau tidak 
    3. docker logs {image} --> untuk melihat log
    4. docker-compose restart {image} --> untuk melakukan restart image
    5. docker stop {container ID} --> untuk melakukan stop container

## SETTING PADA GRAFANA 
1. add connection dan add data source prometheus 
2. image.png
3. lalu save dan test
4. Selanjutnya import dashboard dan masukan ID dashboard yang didapat dari grafana.com
5. Pilih victoria matrics pada nama connection sebelumnya
6. Berhasil 
