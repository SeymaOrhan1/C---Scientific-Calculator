# C---Scientific-Calculator
It is a Scientific Calculator project in Visual Studio Code with C#.


Projenin Amacı: Microsoft Visual Studio programı ile kullanıcı arayüzlü bir hesap makinesi 
tasarlamaktır. Tasarlanacak olan hesap makinesi ondalık, sekizlik, onaltılık ve onluk 
tabanlarında dört işlem yapabilecektir. İşlem yapılacak taban kullanıcı tarafından seçilecektir. 
Sayı tabanı değiştirildiğinde ekrandaki sayı, seçilen tabana dönüştürülecektir. Ondalık sayı 
tabanında - diğer tabanlardan farklı olarak - sin, cos, tan, sinh, cosh, tanh, kare alma, karekök 
alma, log işlemlerini yapabilecektir. Hesap makinesine sayılar hem ekran klavyesinden hem 
de bilgisayar klavyesinden girilebilecektir. Hesap makinesine her türlü hatalı giriş 
engellenecektir.


Projenin Yapılışı: Projeye başlamadan önce internet araştırmaları yapıldı. Proje de kullanıcı 
ara yüzü Microsoft Visual Studio Programında Windows Form Application ile oluşturuldu. 
Oluşturulan ara yüzdeki bileşenler gerekli kodlar yazılarak hesap makinesinin çalışması 
gerçekleştirildi.


Proje de kullanılan elemanlar:
-Form
-TextBox
-Label
-Button
-RadioButton
-Menü Toolstrip-Menu Item
-GroupBox
 
 
 
 Form, “Hesap Makinesi (Şeyma ORHAN)” olarak adlandırıldı. Yapılacak işlemler 3 başlık 
altında toplandı: Standart, Bilimsel, Sayı Tabanı. Menü Toolstrip-Menu Item’ i ara yüze 
getirilerek bu başlıklar yazıldı ve işlem menüsü oluşturuldu. Text Box ile yapılan işlemler 
gösterilmektedir. Menünün altına yerleştirilmiştir. Yapılan işlemin diğer kısmını görmek için 
Label aracı seçilip TextBox’ un sol üst köşesine yerleştirilmiştir. 40 adet buton seçilip ekrana 
hesap makinesi tuşları şeklinde yerleştirilmiştir. Butonlar menüdeki 2 gruba göre ayrılarak 
yerleştirilmiştir. Birinci grup sayılar ve dört işlem yapılacak aritmetik işlem operatörleri 
olarak gruplandırılmış bu grup menüden Standart sekmesi seçildiğinde açılacak olan ilk 
yüzdür. İkinci grup sin, cos, tan, sinh, cosh, tanh, kare alma, karekök alma, log, mod, In, exp, 
%, küp alma işlemleri , π sayısı, decimal, binary, octal, hexadecimal dönüşüm işlemlerini 
yapacak butonlardan oluşturulmuştur. Bu grup menüde Bilimsel olarak adlandırılmış ve 
menüden ‘Bilimsel’ sekmesi seçildiğinde, Standart sekmesinin butonları yanı sıra Bilimsel 
sekmesinin butonları da açılacaktır. Aynı zamanda TextBox da daha uzun bir satır haline 
gelecektir. GroupBox ile işlem yapılacak sayı tabanlarını seçmek için ikinci grup butonlarının 
yanına bir panel oluşturulmuştur ve panele ‘Sayı Tabanı’ adı verilmiştir. Bu panele 4 adet 
RadioButton yerleştirilerek işlem yapılacak sayı tabanının kullanıcı tarafından seçilmesi 
amaçlanmıştır. Bu grup, menüde ‘Sayı Tabanı’ olarak adlandırılmıştır ve menüden bu sekme 
seçildiğinde Bilimsel sekmesi ile üçüncü grup olan Sayı Tabanı paneli açılacaktır. TextBox, 
Bilimsel sekmesindeki boy uzunluğunda olacaktır. Ara yüzü tamamlanan hesap makinesinin 
gerekli kodları C# dilinde yazılmıştır.




