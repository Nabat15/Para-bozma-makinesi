# Para-bozma-makinesi
˙ISTENENLER
• Adım 1: Kullanıcı butonlar yardımıyla xx.xx ¸seklinde 100 TL den küçük
bozdurulacak para degerini girmelidir (ör: 99.99 - 14.35 - .78 gibi).
14.35 parasının ilk hanesi icin ilk butona 1 kere basılır, ikinci hanesi icin 4 kere
basılır, nokta kısmı icin 3. butona bir kere basmak yeterli iken geri kalan
kısımlar icin 4 ve 5. butonlardan yaralanılır. ˙Ilgili butonlara 9’dan fazla basınca
sıfırlanmalıdır. Her butona bası ¸sta ilgili buton için led yanmalıdır ve her bası ¸sta
ilgili rakam LCD de yenilenmelidir/anlık olarak gösterilmelidir. Hesapla butonuna
basıldıktan sonra bozma icin elde edilen miktar ve para cinsleri a ¸sagıdaki gibi ˘
LCD de gosterilir. (Bonus1: Bozdurulacak para giris butonlarından herhangi
birine bastıktan 5 sn sonra hicbir butona basılmazsa bozma icin elde edilen
miktar ve para cinsleri a ¸sagıdaki gibi LCD de gosterilir.) ˘
• Adım 2: Girilen deger display üst satırda saga hizalı olarak gösterilmelidir. ˘
- - - - - - - - - - - 99.99
- - - - - - - - - - - - - - - -
• Adım 3: Kullanıcının girdisine göre arka planda verilecek para miktarları
hesaplanır. (99.99 için 4 yirmilik, 1 onluk, 1 beslik, 4 birlik, 1 yarımlık, 1
ceyreklik, 2 metelik, 4 kurusluk)
[Kullanılacak paralar ve display yazıları: 20 TL: 1 yirmilik, 10 TL: 1 onluk, 5 TL:
1 beslik, 1 TL: 1 birlik, 50 kuru ¸s: 1 yarımlık, 25 kurus: 1 ceyreklik, 10 kuru ¸s: 1
metelik, 5 kuru ¸s: 1 delik, 1 kuru ¸s: 1 kurusluk]
• Adım 4: Her üc saniye aralıkla bozma i ¸slemi için hesaplanan paralar ve adetleri
display alt satırına yazdırılır, kalan para miktarı ise display sag üst satırda verilir. ˘
- - - - - - - - - - - 19.99
4 - yirmilik - - - - - -
3 sn sonra
- - - - - - - - - - - - 9.99
1 - onluk - - - - - - - - -
3 sn sonra
- - - - - - - - - - - - 4.99
1 - beslik - - - - - - - - -
3 sn sonra
- - - - - - - - - - - - - .99
4 - birlik - - - - - - - - -
3 sn sonra
- - - - - - - - - - - - - .49
1 - yarımlık - - - - - -
3 sn sonra
- - - - - - - - - - - - - .24
1 - ceyreklik - - - - -
3 sn sonra
- - - - - - - - - - - - - .04
2 - metelik - - - - - - -
3 sn sonra
2
- - - - - - - - - - - - - . - -
4 - kurusluk - - - - - -
• Adım 5: Ekranı herhangi bir anda temizlemek ve yeni bozdurulacak para
miktarını belirlemek için resetle butonuna basılır (bonus2: 3. butona (nokta
koyma butonu) 5 sn veya daha fazla basılarak resetleme saglanması) ˘
MALZEMELER
• Tiva C / Stellaris launchpad, STM vb. geli ¸stirme kartı (Arduino serisi geli ¸stirme
kartı olarak kullanılamaz.)
• Breadboard
• LCD Display (2x16) (LCD nin giri ¸s-çıkı ¸s baglantılarının ara ¸stırılması sizin ˘
tarafınızdan yapılacaktır. Bununla ilgili herhangi bir doküman
payla ¸sılmayacaktır.)
• 7 adet buton (hesapla ve resetle butonları ayrı olması durumunda)
• 7 adet led (hesapla ve resetle butonları ayrı olması durumunda)
• Direnç
• Jumper
