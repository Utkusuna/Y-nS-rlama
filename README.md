# YıgınSıralama
Yığın Sıralaması

--Yığın nedir?

Yığın tek taraflı giriş çıkışı olan , (LIFO)ilk giren son çıkar mantığında çalışan bir nevi veridir.
 
 --Yığın sıralaması ( HEAP SORT) nedir?
 Yığın sıralaması ise bize verilen yığın verilerinin hafızada tutulması ve sıralanması için kullanılan bir algoritmadır.
 Yığın sıralaması yapılırken arka planda bir yığın ağacı oluşturulup kökteki veriyi alarak alttaki verilerle kıyaslanıp sıralanmasından ibarettir.
 Sıralama yaparken (LIFO) mantığını çökertip küçükten büyüğe veyahut büyükten küçüğe doğru sıralanır ancak LIFO mantığı kökten dallara doğru ağaç yapımında devam eder.

Örnek vermek gerekirse bir sınıftaki öğrenci numaralarını kullanabiliriz;

Sınıftaki öğrenci numaraların girişleri sırasıyla : (76,85,24,13,98,57,41) olsun.
Bu ağacı oluşturursak ortaya şöyle bir görüntü çıkar:

                  (76)
               /       \
             (85)      (24)
             /   \     /   \
           (13)  (98) (57) (41)
       
Ağacın kök değerine bakılarak sol ve sağ dallardaki köklerle sıralayalım.Bu sayede en büyük değer ağacın kökünde kalır.
 
                 (85)
                /    \
              (13)   (98)
              
 ----------------------------------------------------------------------------------------------------------------------------
 
 En sonda en büyük değer olan 98 sayısını yığındaki en büyük veriyi bulmuş oluruz.
