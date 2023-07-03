# Sorunu Anlamak:
1. 1 butonuna basılmasından, güncellenen değerimizin render edilmesine kadar olan uygulama adımları nelerdir? 
Her adım için kodun hangi bölümünün geçerli olduğunu listeleyin.
* Kullanıcı 1 butonuna tıkladı.
* OnButtonClick fonksiyonu tetiklenir.
* addOne fonksiyonunu calistirir. addOne calisip sonuc olarak type iceren bir obje doner.
* dispatch metodu reduceru bu obje ile calistirir.
* state olarak initial state ile baslyarak action tipine gore reducer icerisinde bulunan caselerden birisini calistir. bu senaryoda bir eklemeyi calistirir. state icerisindeki objede total bir arttirilir.
* app.js icerisinde bulunan state degeri guncellenmis olur.
* state in totalini prob olan totaldisplay guncellenir.
* TotalDisplay total artı 1'i gösterdi.
