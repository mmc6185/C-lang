# **<h1 align="center">MinGW Yükleme</h1>**

# MinGW nedir ? 
MinGW; C/c++, Fortran ve Ada gibi dil derleyicilerini içeren GCC Derleyici Paketinin Windows üzerinde çalışan versiyonudur.

# MinGW kurulumu: 
## 1- [Sourceforge](https://sourceforge.net/projects/mingw/) sitesine gidiyoruz ve MinGW indiriyoruz.
![image](https://user-images.githubusercontent.com/73015593/185190065-3cdb95eb-140c-4199-a892-2fdb1ba2b5cc.png)

## 2- İndirilen mingw-get-setup.exe dosyasını çift tıklayarak çalıştırıyoruz ve install yapıyoruz.
![image](https://user-images.githubusercontent.com/73015593/185191648-043da5c8-3588-4036-9894-cd5b0b1c2070.png)

## 3- Kurulum tamamlandıktan sonra Continue diyerek devam ediyoruz. MinGW installation Manager açıyoruz.

## 4- mingw32-base, mingw32-gcc-g++, msys-base seçeneklerine sağ tıklayarak Mark for installation diyoruz.
![image](https://user-images.githubusercontent.com/73015593/185197639-b72caed8-ebc8-43f8-b9a8-98b02f7c34d3.png)

## 5- installation kısmından Apply Changes seçeneğini seçiyoruz ve Apply diyoruz. Ardından tüm dosyaları indirmeye başlayacaktır.
![image](https://user-images.githubusercontent.com/73015593/185198035-73078399-1f9f-4bb3-92f5-d2ce4bea4821.png)

## 6- Kurulumu yaptığımız sürücümüzün altında MinGW altında bin klasörünün dizini kopyalıyoruz. (Benim C:\ atlında) 
![image](https://user-images.githubusercontent.com/73015593/185246490-22e26d6d-1d50-422a-bdb9-b0b57d7a42f0.png)

## 7- Denetim masasını açıyoruz. Sistem ve güvenlik ardından sistem kısımlarını seçiyoruz.
![image](https://user-images.githubusercontent.com/73015593/185246766-74b9366a-47ac-4ba8-bf93-18731aaa4843.png)

## 8- Gelişmiş sistem ayarlarına geliyoruz.
![image](https://user-images.githubusercontent.com/73015593/185246973-41cb3c95-11d2-417b-a67f-9eb6688db251.png)

## 9- Ortam değişkenleri kısmını seçiyor ardından Path kısmına geliyoruz.
![image](https://user-images.githubusercontent.com/73015593/185247143-5789a989-efb2-4d57-9e64-b11825e3834e.png)

## 10- Yeni diyoruz ardından kopyaladığımız dizini yapıştırıyoruz ve tamam diyerek kaydediyoruz.
![image](https://user-images.githubusercontent.com/73015593/185247409-15a9b782-1c1f-420b-a8b1-41be23625216.png)

## 11- Komut istemcisi açıyoruz (cmd) ve gcc versiyonu kontrol ediyoruz.
```
gcc -v
```
![image](https://user-images.githubusercontent.com/73015593/185247826-1f0b1af3-2b7c-401b-b485-1d5a0c4a0a48.png)







