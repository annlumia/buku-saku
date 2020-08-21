# Influx DB
 
## 1. CLI - Command line interface

1. Menyambungkan ke server

   ```sh
   
   $ influx -host=192.168.0.1 -port=8086 -username=admin -password=admin
   
   ```
   
2. Menyambungkan ke server dengan format waktu yang mudah dibaca

   ```sh
   
   $ influx -host=192.168.0.1 -port=8086 -username=admin -password=password -precision rfc3339
   
   ```
  
 3. Menambahkan user

    ```sh

    $ CREATE USER admin WITH PASSWORD 'password' WITH ALL PRIVILAGE

    ```
   
 4. Menampilkan daftar database

    ```sh

    $ SHOW DATABASES

    ```

 5. Menampilkan daftar pengguna

    ```

    > SHOW USERS

    ```
  
 6. Menampilkan measurements atau dalam istilah lain tabel
 
    ```

    > USE nama_database
    > SHOW MEASUREMENTS

    ```
