C programlama dilini daha iyi anlayabilmek için öncelikle basit bir c programı mimarisine bakalım.

# Structure
Bir c programı temel olarak şu kısımlardan oluşur:

<ul>
  <li>Preprocessor Commands (önişlemci komutları)</li>
  <li>Functions (Fonksiyonlar)</li>
  <li>Variables (Değişkenler)</li>
  <li>Statements & Expressions (ifadeler)</li>
  <li>Comments (yorumlar)</li>
</ul>

```
#include <stdio.h>  

int main() {
   /* my first program in C */
   printf("Hello, World! \n");
   
   return 0;
}
```
Yukardaki programımızın farklı bölümlerini inceleyelim. <br>
- İlk satırımız include <stdio.h> Preprocessor komutudur, C compiler'a derlemeden önce stdio.h dosyasını eklemesini söylüyor.
- Sonraki satır olan int main() Programın execute (çalıştırma) işleminin başladığı ana fonksiyonumuzdur.
- Sonraki satır /*...*/ compiler tarafdından yok sayılır. Bunlar yorum satırıdır. Daha sonra kodumuzu tekrar inceleedeğimizde anlayabilmemiz için notlar bırakmamıza olanak sağlar.
- Sonraki satır printf(), C'de terminalde çıktı oluşturmamızı sağlayan bir fonksiyondur.Burada "Hello, World!" Çıktısı oluşturacaktır.
- Sonraki satır main fonksiyonunu sonlandırır ve 0 döner.

# Compile and execute C program (C programını derle ve çalıştır.)
Kaynak kodu bir dosyaya nasıl kaydedeceğimizi ve nasıl compile edip çalıştıracağımızı inceleyelim.

## Windows için :
### 1- Bir text editor kullanıyoruz ve yukardaki kodumuzu yapıştırıyoruz.
![image](https://user-images.githubusercontent.com/73015593/185923678-048f97c2-f37e-4dbe-80fa-65a34bd9662c.png)

### 2- Dosyamızı helloworld.c olarak kaydediyoruz.
![image](https://user-images.githubusercontent.com/73015593/185924123-0b92442f-adad-446b-905e-cba21fb2a878.png)

### 3- cmd veya windows powershell kullanarak dosyamızın bulunduğu satıra gidiyoruz.
![image](https://user-images.githubusercontent.com/73015593/185924442-86dcd5cf-5b7a-42c5-8a62-350998622104.png)

### 4- gcc compiler ile helloworld.c dosyasını compile ediyoruz.
```
gcc .\helloworld.c -o hellworld
```
![image](https://user-images.githubusercontent.com/73015593/185925479-12f97559-d710-4b39-a33c-abbca7f2ca2e.png)

### 5- Compile sonrası oluşan helloworld.exe dosyasını çalıştırıyoruz ve "Hello, World!" çıktısı alıyoruz.
![image](https://user-images.githubusercontent.com/73015593/185926028-22ce2a0f-38a5-4357-b2c2-99229224f632.png)

## Ubuntu için :
### 1- Bir text editor kullanıyoruz ve yukardaki kodumuzu yapıştırıyoruz.
![image](https://user-images.githubusercontent.com/73015593/185926765-6f642fe4-6ebf-4022-9719-2cf63d055ab1.png)

### 2- Dosyamızı helloworld.c olarak kaydediyoruz.
![image](https://user-images.githubusercontent.com/73015593/185926893-688a0813-8eb5-482a-b0f8-57f06a47c7d4.png)

### 3- terminal kullanarak dosyamızın bulunduğu satıra gidiyoruz.
![image](https://user-images.githubusercontent.com/73015593/185926990-57082e99-ca89-4f3a-91f6-b5d3c2ac3c0b.png)

### 4- gcc compiler ile helloworld.c dosyasını compile ediyoruz.
![image](https://user-images.githubusercontent.com/73015593/185927199-30a140eb-824a-40d9-91c8-4b3acad90920.png)

### 5- Compile sonrası oluşan executuble helloworld dosyasını çalıştırıyoruz ve "Hello, World!" çıktısı alıyoruz.
![image](https://user-images.githubusercontent.com/73015593/185927811-d7a28c59-d575-41cb-942b-ebbd491e01b3.png)


































