# Selection Sort Projesi
## Verilen diziyi sıralama
(22,27,16,2,18,6) dizisini Insertion sort yöntemiyle sıralayalım.
1'inci adımın sonucu -> (2,27,16,22,18,6) bu adımda önce tek tek en küçüğü bulana kadar sayıları tarıyoruz soldan başlayarak. 2'nin en küçük olduğunu anladıktan sonra 22 ile yer değiştiriyoruz. 
2'nci adımın sonucu ->  (2,6,16,22,18,27) artık 27 den başlayıp 6 ya doğru en küçük elemanı arayacağız. Sonra da yer değiştireceğiz.
3'üncü adımın sonucu -> (2,6,16,22,18,27) bu adımda bir değişiklik olmamış gibi gözükebilir ama 16 dan başlayıp 27 ye kadar sorgu yaptık sadece ilk başladığımız en küçük olduğu için değişim gözükmedi.
4'üncü adımın sonucu -> (2,6,16,18,22,27) burda 22 den başlayıp 27 ye kadar tarama yaptık. 
5'inci adımın sonucu -> (2,6,16,18,22,27) 3. adımdaki durumla aynısı burda da olmuş tarama yaptık ama bir değişim gerçekleşmedi ilk eleman en küçük diye.
***************
## Verilen dizinin Big-O natation'unun hesaplanması
İlk adımda ilk sayıyı seçip diğer 5 sayı ile karşılaştırıyoruz ve en son 1 tanesi ile yer değiştiriyoruz yani 6 tane işlem gerçekleşti.
İkinci adımda 27 yi seçip diğer 4 sayı ile karşılaştırıp 6 ile yerini değiştiriyoruz sonucunda 5 işlem yapılmış oldu. 
Böyle 1'er 1'er azalan şekilde gidiyor ise n elemanlı bir dizide Insertion sort yöntemiyle sıralama yapılmaya çalışıldığında n * (n+1) / 2 kadar işlem yapılır keza bu da (n^2 + n) / 2 bu ifadenin de Big-O natation'u -> O(n^2) şeklinde gösterilir.
## Time Complexity: Dizi sıralandıktan sonra 18 sayısı aşağıdaki case'lerden hangisinin kapsamına girer? Yazınız
18 sayısı ortada bulunduğu için average case e girer.
## (7,3,5,8,2,9,4,15,6) dizisinin Selection Sort'a göre ilk 4 adımını yazınız.
1'inci adımın sonucu -> (2,3,5,8,7,9,4,15,6)
2'nci adımın sonucu ->  (2,3,5,8,7,9,4,15,6)
3'üncü adımın sonucu -> (2,3,4,8,7,9,5,15,6)
4'üncü adımın sonucu -> (2,3,4,5,7,9,8,15,6)


