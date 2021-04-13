# LINUX-Shell-Programming-Pipes-and-Filters
Shell programming in Linux. Pipe and filter are used.

Komutlar Codes.txt dosyasının içinde bulunmaktadır.
Elimizde 5000 satırlı bir veri seti var. Veri seti liste.txt dosyasının içinde bulunmaktadır.
Rastgele oluşturulan veriler aşağıdaki sütunlardan oluşmaktadır:
1. Öğrenci Numarası, 2. Ad, 3. Soyad, 4. E-Posta, 5. Ders Kodu, 6. Not, 7. Dersi Kaçıncı Alışı
Üretim kuralları aşağıdaki şekilde gerçekleşmiştir:
1. 2015 girişlilerin öğrenci numarası 2015 ile baslar, 2014 girişlilerin öğrenci numarası 2014 ile baslar
2. 2015 girişliler CS365 ve CS464 derslerini alamazlar
3. CS365 veya CS464 derslerinden birini alabilmek icin CS101 ve CS102 derslerinin alınmış olması
gerekli
4. CS102 alabilmek icin CS101 almış olmak gerekli
5. 2015 girişlilerin email adresleri i.soyisim@ce1.marmara.edu.tr şeklindedir
6. 2014 girişlilerin email adresleri isimsoyisim@ce1.marmara.edu.tr şeklindedir
7. herhangi bir dersten 30 altında not alan kalır
8. herhangi bir dersten 50 altında not alan şartlı geçer. 

Problem

1- liste.txt isimli veri setini kullanacaksınız.

2- liste2.txt dosyasına; CS101 ve CS102 dersini alanları listeleyin.

3- liste3.txt dosyasına; listelenmiş liste2.txt dosyası üzerinden 2015 girişlileri listeleyin (egrep ile).

4- liste4.txt dosyasına; listelenmiş liste3.txt dosyası üzerinden 50 ve yukarı not alanları listeleyin. Böylece liste4.txt dosyasının içinde CS101 ve CS102 dersinden 50 ve yukarı not alan 2015 girişliler listelenmiş olmalı. 

5- liste5.txt dosyasına; Filtrelenen öğrencilerin numaralarındaki eksi (-) işaretini alt çizgi (_) ile değiştirin.
 
6- liste6.txt dosyasına; Aldıkları puanlara
göre büyükten küçüğe göre sıralayın.

7- liste7.txt dosyasına; isimlerine göre a'dan z'ye alfabetik şekilnde ve notu 50 den yüksek olanları sıralayın. 
Dosyadaki ayıraç karakterinin virgül olduğunu harici olarak belirtin.

8- liste8.txt dosyasına; listelenmiş liste7.txt dosyası üzerinden; Notu 90'dan küçük olan, dersi 2. defa almış öğrencileri listeleyin (egrep kullanmadan)

9- Şimdiye kadarki filtrelemenin sonucunda listede kaç öğrenci kaldığını ilgili komut ile ekrana yazdırın.
(Burada çıktı olarak ekrana satır sayısı yazdırılacaktır)

10- Bulunan satır sayısı ile öğrenci numaranızı arasında boşluk kalacak şekilde ekrana yazdırın.Ekranda örneğin “123 1001011010” şeklinde bir satır görünmelidir.

11- Çıktınızın md5 hash fonksiyonu ile özetini ekrana yazdırın (örneğin
9606d1bf8bde301a4ac2136672060a94 gibi..)


