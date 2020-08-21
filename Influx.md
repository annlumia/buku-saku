# Influx DB
 
## 1. CLI - Command line interface

1. Menyambungkan ke server

   ```
   
   > influx -host=192.168.0.1 -port=8086 -username=admin -password=admin
   
   ```
   
2. Menyambungkan ke server dengan format waktu yang mudah dibaca

   ```
   > influx -host=192.168.0.1 -port=8086 -username=admin -password=password -precision rfc3339
   
   ```
  
 3. Menambahkan user

    ```

    > CREATE USER admin WITH PASSWORD 'password' WITH ALL PRIVILAGE

    ```
   
 4. Menampilkan daftar database

    ```

    > SHOW DATABASES

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
