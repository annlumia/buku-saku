# PM2
PROCESS MANAGER FOR NODE.JS

## Install

Installasi menggunakan npm

  ```sh

  $ npm i pm2 -g

  ```

## Penggunaan

1. Menjalankan aplikasi nodejs

    ```sh

    $ pm2 start index.js --name="aplikasi_01"

    ```

2. Membuat aplikasi berjalan otomatis pada saat startup
   > Belum dicoba pada windows
   
   ```sh
   
   $ pm2 save
   $ pm2 startup
   
   ```
 
3. Membuat file konfigurasi
   
   ```sh
   
   $ pm2 ecosystem
   
   ```
 
 
4. Menjalankan aplikasi dengan ecosystem
   
   ```sh
   
   $ pm2 start
   
   ```
