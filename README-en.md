# StegAndro's Image Quality Test Result

> The StegAndro Android application can be found [here](https://github.com/GTHGHT/StegAndro)

> Hasil pengujian dalam Bahasa Indonesia bisa dilihat [disini](/README.md)

Testing is done on 45 images comprising 15 BMP files, 15 JPG files, and 15 PNG files. The variety of formats is intended to test the quality of steganography based on the format. The images are obtained from sources such as:

* [Standard Test Images](https://www.kaggle.com/datasets/saeedehkamjoo/standard-test-images)
* [Mini-ImageNet](https://www.kaggle.com/datasets/deeptrial/miniimagenet)
* [Paired landscape and Monet-Stylized image](https://www.kaggle.com/datasets/shcsteven/paired-landscape-and-monetstylised-image)
* [Informatika Unmul](https://informatika.ft.unmul.ac.id/front/img/logo/unmul450.png)

The selected images used in this test are in the ["original"](/original) folder. We also have the text testing data, which came from [lipsum generator](https://www.lipsum.com) with lengths 50, 300, 600, and 1200
characters. Every image testing data is embedded with text testing data as the message. The result will be evaluated using Mean Square Error (MSE) and Peak Signal-to-Noise Ratio (PSNR) metrics. Below are the results (C stands for characters):

| No | MSE 50C | PSNR 50C | MSE 300C | PSNR 300C | MSE 600C | PSNR 600C | MSE 1200C | PSNR 1200C | Image Quality | Format |
|--|-----|------|-----|------|-----|------|-----|------|:----------:|:--------:|
| 1 | 13,68551 | 36,76819 | 13,73779 | 36,75164 | 13,86161 | 36,71267 | 14,07228 | 36,64716 | Passable | BMP |
| 2 | 4,08032  | 42,02386 | 4,14185  | 41,95886 | 4,20145  | 41,89681 | 4,29536  | 41,80081 | Good     | JPG |
| 3 | 39,36202 | 32,18003 | 39,53967 | 32,16047 | 39,75080 | 32,13734 | 40,23195 | 32,08509 | Passable | JPG |
| 4 | 10,16325 | 38,06048 | 10,36696 | 37,97429 | 10,54075 | 37,90209 | 10,75772 | 37,81360 | Passable | JPG |
| 5 | 11,23915 | 37,62347 | 11,30987 | 37,59623 | 11,36296 | 37,57589 | 11,48721 | 37,52866 | Passable | JPG |
| 6 | 17,74762 | 35,63940 | 17,81440 | 35,62309 | 17,93130 | 35,59469 | 18,12880 | 35,54711 | Passable | BMP |
| 7 | 14,96744 | 36,37933 | 15,15246 | 36,32597 | 15,26478 | 36,29390 | 15,47264 | 36,23516 | Passable | JPG |
| 8 | 16,71671 | 35,89930 | 16,84128 | 35,86705 | 16,94928 | 35,83929 | 17,13225 | 35,79266 | Passable | JPG |
| 9 | 38,00736 | 32,33213 | 38,09660 | 32,32194 | 38,20729 | 32,30934 | 38,38694 | 32,28897 | Passable | PNG |
| 10 | 8,73154  | 38,71989 | 8,75813  | 38,70669 | 8,79675  | 38,68758 | 8,88947  | 38,64205 | Passable | JPG |
| 11 | 24,60844 | 34,21996 | 24,65254 | 34,21219 | 24,72874 | 34,19878 | 24,91765 | 34,16573 | Passable | BMP |
| 12 | 9,16532  | 38,50933 | 9,27949  | 38,45556 | 9,33555  | 38,42941 | 9,40272  | 38,39827 | Passable | JPG |
| 13 | 18,76607 | 35,39707 | 18,78555 | 35,39256 | 18,80869 | 35,38722 | 18,86902 | 35,37331 | Passable | JPG |
| 14 | 13,91239 | 36,69679 | 13,95134 | 36,68464 | 14,01206 | 36,66578 | 14,15382 | 36,62207 | Passable | PNG |
| 15 | 9,64639  | 38,28716 | 9,82926  | 38,20559 | 9,87318  | 38,18623 | 10,02537 | 38,11980 | Passable | JPG |
| 16 | 9,56097  | 38,32578 | 9,63735  | 38,29123 | 9,71483  | 38,25645 | 9,86947  | 38,18787 | Passable | BMP |
| 17 | 5,78642  | 40,50670 | 5,88407  | 40,43403 | 5,92228  | 40,40592 | 5,99334  | 40,35411 | Good | PNG |
| 18 | 18,83889 | 35,38025 | 18,88038 | 35,37070 | 18,93211 | 35,35881 | 19,02604 | 35,33732 | Passable | BMP |
| 19 | 12,98233 | 36,99728 | 13,01236 | 36,98724 | 13,05678 | 36,97244 | 13,14714 | 36,94249 | Passable | BMP |
| 20 | 5,33642  | 40,85830 | 5,35196  | 40,84567 | 5,37297  | 40,82866 | 5,40876  | 40,79983 | Good | PNG |
| 21 | 15,24450 | 36,29967 | 15,36473 | 36,26555 | 15,57883 | 36,20545 | 15,76751 | 36,15317 | Passable | JPG |
| 22 | 23,06949 | 34,50043 | 23,10438 | 34,49386 | 23,14882 | 34,48552 | 23,23630 | 34,46914 | Passable | BMP |
| 23 | 3,16604  | 43,12564 | 3,21890  | 43,05372 | 3,26969  | 42,98574 | 3,41982  | 42,79078 | Good | PNG |
| 24 | 6,90262  | 39,74067 | 6,95905  | 39,70530 | 7,06956  | 39,63688 | 7,28718  | 39,50521 | Passable | PNG |
| 25 | 7,95458  | 39,12463 | 8,05306  | 39,07120 | 8,06546  | 39,06451 | 8,11439  | 39,03824 | Passable | JPG |
| 26 | 18,16536 | 35,53836 | 18,19674 | 35,53087 | 18,23497 | 35,52175 | 18,31147 | 35,50357 | Passable | BMP |
| 27 | 16,97446 | 35,83284 | 17,00683 | 35,82457 | 17,04705 | 35,81431 | 17,12158 | 35,79537 | Passable | BMP |
| 28 | 8,42293  | 38,87618 | 8,46738  | 38,85331 | 8,51564  | 38,82863 | 8,62125  | 38,77510 | Passable | BMP |
| 29 | 7,49280  | 39,38436 | 7,54815  | 39,35240 | 7,58962  | 39,32860 | 7,69201  | 39,27041 | Passable | PNG |
| 30 | 11,65309 | 37,46639 | 11,69782 | 37,44976 | 11,78379 | 37,41796 | 11,95570 | 37,35505 | Passable | BMP |
| 31 | 34,74514 | 32,72186 | 34,83066 | 32,71119 | 34,98659 | 32,69179 | 35,19636 | 32,66583 | Passable | JPG |
| 32 | 23,81945 | 34,36149 | 23,87585 | 34,35122 | 23,95198 | 34,33739 | 24,10240 | 34,31020 | Passable | PNG |
| 33 | 36,91600 | 32,45866 | 37,05106 | 32,44280 | 37,12930 | 32,43364 | 37,26448 | 32,41785 | Passable | PNG |
| 34 | 12,59884 | 37,12750 | 12,64105 | 37,11297 | 12,70389 | 37,09144 | 12,82658 | 37,04970 | Passable | BMP |
| 35 | 11,45411 | 37,54119 | 11,47329 | 37,53392 | 11,50600 | 37,52156 | 11,56631 | 37,49885 | Passable | BMP |
| 36 | 22,45550 | 34,61758 | 22,61488 | 34,58686 | 22,73428 | 34,56399 | 22,88963 | 34,53442 | Passable | JPG |
| 37 | 6,74181  | 39,84304 | 6,75491  | 39,83461 | 6,77476  | 39,82186 | 6,81330  | 39,79723 | Passable | PNG |
| 38 | 19,17678 | 35,30305 | 19,23051 | 35,29090 | 19,32186 | 35,27031 | 19,45707 | 35,24003 | Passable | BMP |
| 39 | 3,15164  | 43,14544 | 3,15571  | 43,13983 | 3,15769  | 43,13711 | 3,16305  | 43,12974 | Good | PNG |
| 40 | 15,09758 | 36,34173 | 15,23824 | 36,30146 | 15,47305 | 36,23505 | 15,67320 | 36,17923 | Passable | JPG |
| 41 | 32,68597 | 32,98719 | 33,21777 | 32,91710 | 34,39499 | 32,76585 | 34,84177 | 32,70980 | Passable | PNG |
| 42 | 3,68242  | 42,46947 | 3,69604  | 42,45343 | 3,71422  | 42,43213 | 3,76085  | 42,37794 | Good | PNG |
| 43 | 19,11346 | 35,31741 | 19,13728 | 35,31200 | 19,15982 | 35,30689 | 19,20628 | 35,29637 | Passable | PNG |
| 44 | 23,97570 | 34,33309 | 24,03737 | 34,32194 | 24,10785 | 34,30922 | 24,22645 | 34,28791 | Passable | PNG |
| 45 | 13,80578 | 36,73019 | 13,87774 | 36,70762 | 13,95117 | 36,68470 | 14,15890 | 36,62051 | Passable | BMP |

| Metrics  | Average | Lowest Value | Highest Value|
|----------|---------|--------------|--------------|
| **MSE 50C**  | 15,59490 | 3,15164 | 39,36202 |
| **PSNR 50C** | 37,02206 | 32,18003 | 43,14544 |
| **MSE 300C**  | 15,67717 | 3,15571 | 39,53967 |
| **PSNR 300C** | 36,99520 | 32,16047 | 43,13983 |
| **MSE 600C**  | 15,77767 | 3,15769 | 39,75080 |
| **PSNR 600C** | 36,96737 | 32,13734 | 43,13711 |
| **MSE 1200C**  | 15,91871 | 3,16305 | 40,23195 |
| **PSNR 1200C** | 36,92119 | 32,08509 | 43,12974 |

Image quality testing resulted in average Mean Square Error (MSE) values ranging from 15,59490 for 50 characters message to 15,91871 for 1200 characters message, as well as average Peak Signal-to-Noise Ratio (PSNR) values ranging from 37,02206 dB for 50 characters message to 36,82119 dB for 1200 character message. Image quality testing results indicate that for DCT steganography, image distortion increases along with the number of characters embedded, although as a whole, image result is classified as passable. Based on the testing result, it can be concluded that steganographic methods based on DCT are proven to secure messages inside of an image.
