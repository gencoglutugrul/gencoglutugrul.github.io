---
layout: post
title:  "Yerli Metal Fetişimi Tatmin Edecek Bot"
date:   2020-11-17 15:48:00
---
Son üç dört aydır yerli metale kafayı takmış durumdayım. Metal derken genellikle black ve death metali kastediyorum. Zira diğer alt türleri sevsem de pek dinlemiyorum. Hatta death ve black arasından da özellikle black metalciyim demek doğru olur. Aslında bu yerli metal fetişim pandemiden önce gittiğim konserle başladı. Konserin ertesi gününde boynum koptuğu için okula gitmemiştim ve evdeki vaktimi de konsere gelen Merhum, Oculos, Sabhankra ve Tagraht'ı araştırmakla geçirdim. Sonrasında pandemi yüzünden konser diye bir şey duymadık bile...

Neyse efendim biz yattığımız yerden online eğitimle uğraşırken birbirinden güzel yerli metal grupları pandemi sürecinde albüm kaydedip yayınladı. Tabi biz de yine yattığımız yerden gerek spotify olsun gerek youtube olsun farklı farklı mecralardan severek dinledik. Bu süreçte yerli black metalin hiç de kötü olmadığını farkettim. Üstelik yerli black metalin okadar da az üretilen bir şey olmadığını da farkettim. Hatta öyle ki bu yazıyı yazdığım gün kontrol ettiğimde metal-archives üzerinde tam 25 yerli black metal (alt türleri ile birlikte) albümü (singlelar da dahil) yayınlanmış. Bunu ilk farkettiğimde bunların hepsini keşfetmek ve bir playlist yapmak istedim. Tabi bu durumda herkesin imdadına koşan metal-archivesi taramaya başladım. Önce elle taradım tek tek tüm yerli black metal gruplarını açıp 2020'de albümü olup olmadığına baktım. Çünkü amacım pandemi sürecinde çıkan yerli black ve death metal parçalarının playlistini yapmaktı. 

Playlisti oluşturup önemli sayıda albüm ekledikten sonra bu sefer her yeni albüm çıktığında acaba başkası da albüm çıkarmış mı gözümden kaçmış mıdır diye yeniden tarama ihtiyacı hissetmeye başladım. Ben de her seferinde tek tek taramamak için metal-archives'i benim yerime tarayacak rezil bir bot yaptım :D Sonra bu botun çektiği içerikleri json formatına kaydedip içinde istediğim gibi filtreleme işlemi yaptım. Böylece metal-archives de olur da gözümden kaçan yeni bir albüm yayınlanırsa bulmam sadece dakikalarımı alacak.

Playlist demişken o playlisti de buraya bırakalım tabii. Şimdilik toplam 24 albüm (singlelar dahil), 22 sanatçı, 128 parça var ve pandemi bitene kadar da sürekli güncel tutacağım. Hem black hem de death parçaları bulunuyor. Peki neden bu kadar az? Çünkü her sanatçı albümünü spotifyda yayınlamayı tercih etmiyor veya yayınlayamıyor. 

<iframe src="https://open.spotify.com/embed/playlist/1jWEKxAbMCt3AY3bT2FT7M" width="300" height="380" frameborder="0" allowtransparency="true" allow="encrypted-media"></iframe>

Şimdi sıra geldi kodlara... PHP ile yazdım çünkü en hakim olduğum dil php, bunun yanında hızlıca yazdığım için fazlaca saçmalık yapmış olabilirim :D Belki bir ara düzenlerim ama şimdi değil. İşte parçaları çekmek için yazdığım rezil kodlar;

<script src="https://gist.github.com/gencoglutugrul/8e383182bdec6fd9e5f35e70c1313531.js"></script>