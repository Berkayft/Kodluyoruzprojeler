# Merge Sort Projesi
## (16,21,11,8,12,22) dizisini merge sort yöntemiyle sıralayalım.
1'inci adımın sonucu -> (16,21,11) ve (8,12,22) önce ikiyle bölüyoruz.      
2'nci  adımın sonucu -> (16,21) , (11) , (8,12) ve (22) bu adımla beraber bölme işlemlerimiz bitti. şimdi ikili grupları kendi aralarıdna büyükten küçüğe sıralayacağız.        
3'üncü adımın sonucu -> (16,21) , (11) , (8,12) ve (22) değişme gözükmemesinin sebebi sıraların zaten büyükten küçüğe denk gelmiş olması yoksa sorgulamalar yapıldı. Şimdi dizileri birleştiricez.          
4'üncü adımın sonucu -> (11,16,21) ve (8,12,22) şeklinde iki dizemiz oldu şimdi bunlar nasıl oldu? ilk olarak ilk iki diziyi kendi arasında birleştireceğiz. 11 ve 16 arasında hangisi daha küçük diye sorgu yapıyoruz bu iki sayı olmasının sebebi iki dizedeki en küçük sayılar olması ve en başa en küçük sayıyı yazıcak olmamımızdan dolayı başka bir ihtimal kalmıyor. 11 i yerleştirdikten sonra 16 ve 21 arasında kıyaslama yapılıp yerleştiriliyor (11,16,21) şeklindeki diziye erişiyoruz. aynı adımları diğer diziye de uyguluyoruz.          
5'inci adımın sonucu -> (8,11,12,16,21,22) bu son adımdı bu adıma yukarda küçük dizileri birleştirme şekliyle ulaştık önce 8 ve 11'i kıyasladık sonra 11 ve 12 şeklinde devam etti.         
*******************************************
## Big-O notation'unu hesaplama
n/2 n/4 n/8 şeklinde giden hesaplamalarda Big-o notation -> O(logaritma 2 tabanında n) şeklinde gösterilir.
