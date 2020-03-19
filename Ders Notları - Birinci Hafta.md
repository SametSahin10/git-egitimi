/////////////////////////////////////1. HAFTA//////////////////////////////////////////////////////////////////////////////////////////////

"Tab tuşuna basarak, yarısını yazdığımız dizinin veya dosyanın ismini otomatik tamamlayabiliriz "

ls ===> Bulunduğumuz dizinin içeriğini listeler.
ls -l ===> Bulunduğumuz dizininin içerğini ayrıntılı olarak listeler.
ls -la ===> Bulunduğumuz dizininin içerğini gizli ("." ile başlayan dosyalar ) dosyaları ve dizinleri de dahil ederek listeler.

pwd ===> Bulunduğumuz dizini gösterir. Örnek: /Users/sametsahin/Documents/Dersler

cd ===> Bulunduğumuz konumdan başka bir konuma gitmemizi sağlar. Örnek: "cd Desktop" (Desktop dizinine gider).
cd ===> Eğer sadece bunu yazarsak Home dizinine gider gider.
cd . ===> Bulunduğunuz konumda kalmasını sağlar.
cd .. ===> Bulunduğunuz konumdan bir adım geriye gider

mkdir ===> Dizin oluşturur. Örnek: "mkdir hello" (hello adında dizin oluşturur).

rm ===> Dosya silmek için kullanılır. Örnek: "rm kodlar" (kodlar adındaki dosyayı siler). 
rm -rf ===> Dizin siler. Örnek: "rm -rf hello" (hello adlı dizini siler).

cp ===> Kopyalamak için kullanılır. Örnek: "cp deneme.html ~/dosya/deneme.html". İlk parametre kopyalanacak dosyayı ikinci parametre ise hedefi gösterir.
cp -r ===> Dizini kopyalamak için kullanılır. Örnek: "cp -r deneme ~/dosya/deneme" . İlk parametre kopyalanacak dosyayı ikinci parametre ise hedefi gösterir.

mv ===> Taşımak için kullanılır.  Örnek: "mv deneme.html /dosya/deneme.html" . İlk parametre taşınacak dosyayı ikinci parametre ise hedefi gösterir.
mv ===> Dosya ismini değiştirmek için de kullanılabilir. Örnek: "mv deneme.html test.html" (deneme.html dosyası ismi test.html olarak değiştirilip taşınmıştır).

clear ===> Komut satırını temizler

vim ===> Vim text editörünü açar. Örnek: "vim Fasulyenin_Faydalari"
cat ===> İçerisinde yazı bulunan herhangi bir dosyanın içindekileri komut satırına yazdırır. Örnek: "cat Fasulyenin_Faydalari".