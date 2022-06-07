Final Project Tahap 1

Axel Gavan (1202190004)

Install Laravel 8 

- Sebelum install Laravel pastikan sudah menginstall XAMPP & Composer sebagai aplikasi pendukung

- Masuk ke Command Prompt

![image-20220607185419268](C:\Users\axel\AppData\Roaming\Typora\typora-user-images\image-20220607185419268.png)

- Masuk ke folder XAMPP

  ```
  cd \xampp\htdocs
  ```

  ![image-20220607185838890](C:\Users\axel\AppData\Roaming\Typora\typora-user-images\image-20220607185838890.png)

- Install Laravel dengan perintah berikut ("integratif" sebagai nama file)

  ```
  composer create-project --prefer-dist laravel/laravel integratif
  ```

   ![image-20220607190049298](C:\Users\axel\AppData\Roaming\Typora\typora-user-images\image-20220607190049298.png)

- Cek instalasi Laravel di file explorer dengan nama "integratif"

  ![image-20220607190256019](C:\Users\axel\AppData\Roaming\Typora\typora-user-images\image-20220607190256019.png)

- Kemudian cek instalasi Laravel dengan perintah

  ```
  php artisan serve
  ```

  ![image-20220607192612055](C:\Users\axel\AppData\Roaming\Typora\typora-user-images\image-20220607192612055.png)

- Kemudian cek di web dengan memasukkan

  ```
  http://127.0.0:8000
  ```

  ![image-20220607192909368](C:\Users\axel\AppData\Roaming\Typora\typora-user-images\image-20220607192909368.png)