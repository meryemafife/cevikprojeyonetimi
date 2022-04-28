# Improved Agile: A Customized Scrum Process for Project Management in Defense and Security
Geliştirilmiş Çevik: Savunma ve Güvenlikte Proje Yönetimi için Özelleştirilmiş Bir Scrum Süreci

İtalyan savunma sanayi denenmiş yöntemdir.

Luigi Benedicenti, Paolo Ciancarini, Franco Cotugno, Angelo Messina,Alberto Sillitti, and Giancarlo Succi

Yazılım geliştirme  süreçleri Silahlı kuvvetler alanında, geleneksel olarak katı geliştirme süreçleri aracılığıyla ele alınmıştır. Bu tür süreçler, askeri bir organizasyonun ayrılmaz bir parçası olduğuna inanılan oldukça hiyerarşik yapıya çok iyi uyuyor gibiydi. Ama bugün artık durum böyle değil. Asimetrik rakipler, çok sayıda çatışan ihtiyaç ve yüksek kaliteli, esnek ve çevik bir müdahale zorunluluğu, askeri doktrini derinden değiştirdi. Farklı aktörlerden gelen çok sayıda, hızla değişen gereksinimlerin etkisi nispeten uzun bir süredir tanımlanmış olmasına rağmen ancak son zamanlarda gündeme geldi.

Bu düşüncelere ek olarak, savunma bütçelerindeki yeni kısıtlamalar, silahlı kuvvetlerde derin bir kültürel değişime neden olmuştur. 

Örneğin, ABD Savunma Bakanlığı satın alma politikalarını özel ekipman yerine genel kullanıma hazır ekipmanın tedarik edilmesine izin verecek şekilde değiştirmiştir. Bununla birlikte, yazılım üretimi, kısmen zaten iyi yapılandırılmış bir ortamda karmaşıklık ve hızlı değişimle başa çıkmak için güvenilir yöntemlerin olmaması nedeniyle daha yavaş değişiyor. Öte yandan, son on yılda ticari dünyada, son nesil programlama dillerinin etkinliği ve açık kaynaklı bilgisayar destekli yazılımların mevcudiyeti nedeniyle, yürütülebilir kod satırı (ELOC) veya işlev noktası başına yazılım maliyeti önemli ölçüde azalmıştır. 

Ayrıca, çevik geliştirme yöntemlerinin benimsenmesi, bu bağlamlarda yazılım geliştirme etkinliğinin ve verimliliğinin artmasına katkıda bulunmuş gibi görünmektedir. İtalyan Ordusu Genelkurmay Başkanlığı'nda bu faktörler, müteahhitlerin sivil ve askeri geliştirme ekiplerinin bir karışımıyla çalışmasını gerektiren yazılım geliştirmesinin içselleştirilmesine yol açmıştır. Buna karşılık, bu, çevik ilkelere ve daha spesifik olarak iAgile (gelişmiş Çevik için) adı verilen scrum'a dayanan yeni bir yazılım geliştirme sürecinin oluşturulmasına yol açmıştır.

Proje yönetimi bu sürecin ayrılmaz bir parçasıdır, çünkü çevik bir bağlamda bile, güvenlik ve müşteri memnuniyeti başta olmak üzere silahlı kuvvetlerin ihtiyaçlarına cevap vermek hala gereklidir. Çevik geliştirme ilkelerinden yararlanmak ve bunları İtalyan Ordusu prosedürleriyle kesiştirmek, yönetim stratejisine aşağıdaki hususların dahil edilmesiyle sonuçlandı: 
• Sık yayınlar.
• Yönetimi değiştirin.
• Savunma sektöründe çok sayıda olan ve geleneksel olarak birbirleriyle kolayca etkileşime girmeyen ihtiyaç sahipleri (hedef sahipleri), satın alma sahipleri (altın sahipleri) ve müteahhitler arasındaki karmaşık bir ortamda etkin işbirliği.
• Değişen müşteri ihtiyaçlarına ve acil durumlara hızlı tepki verebilmek için küçük ve yetkilendirilmiş ekiplere odaklanın.

iAgile sürecinin altyapısı dört ana sütundan oluşur: 
- çevik eğitim, 
- yenilikçi CASE araçları, 
- yapılandırılmış kullanıcı topluluğu yönetimi 
- özel çevik geliştirme doktrini. 

![Şekil 1](/defense/1.png)

Tüm bu sütunlar, iAgile'ın etkili olmasını sağlayan yönetim stratejisinin bir parçasıdır. Çevik eğitim, iAgile çerçevesinde çalışmak için gereken bilgiyi oluşturduğundan, değişiklik yönetimi için esastır. Ancak bu yeterli değildir, çünkü değişimin gerçekleşmesi için hem motivasyon hem de pekiştirme gerekir. 

Motivasyon, başlangıçta standart organizasyonel yollarla sağlanır, ancak ilk sprintten sonra, kısmi ürünün işlevselliğinin gösterdiği gözle görülür ilerlemeyle beslenir. 

Güçlendirme, geri bildirimin anında olmasını sağlayan ve kullanıcıları geliştirmeye yakın hale getiren yapılandırılmış kullanıcı topluluğu yönetimi aracılığıyla sağlanır, kullanıcı memnuniyetini ve dolayısıyla ekibin güven düzeyini büyük ölçüde artırır.

Yenilikçi CASE araçları sütununa ihtiyaç duyulur çünkü iAgile için uyarlanmış destekleyici araçlar olmadan, otomasyon eksikliği ve ilerleme izleme sistemi nedeniyle yazılım geliştirme daha yavaş ilerleyecektir. Özellikle, geliştirici müdahalesi gerektirmeden oluşturulan yazılım eserlerini ölçen ve geliştiricileri yavaşlatacak bir dizi invaziv olmayan izleme araçları geliştirmek çok önemliydi.

İzleme araçları, daha sonra, bir takviye mekanizması olarak hareket ederek ve gerektiğinde nedensel analiz ve problem çözümü için veri sağlayarak, gelişimin etkinliğini somut olarak gösteren ilerleme raporları oluşturabilir. 

Seçilmiş uzmanların departman başkanlarıyla aynı karar yetkisine sahip delege ürün sahipleri olarak hareket etmelerini sağlamak için yapılandırılmış kullanıcı topluluğu yönetimine ihtiyaç vardır. Bu adımı gerçekleştirmek, Ordudaki üst düzey yetkililerin tam desteğini gerektiriyordu. 

Bu, geliştirme ekiplerinde gerekli özerklik düzeyini oluşturdu, böylece geliştirme, sürekli yukarıdan aşağıya yetkilendirme darboğazı olmadan devam edebilirdi. Bu yapıyı gerçekleştirmek mümkün olmuştur çünkü bizim durumumuzdaki geliştirme birimi, çok hızlı değiştirilebilen ve bu nedenle proje üzerinde çok az etkisi olduğu algılanan tek bir kullanıcı hikayesidir; yine de, çok sayıda kullanıcı hikayesini aynı anda geliştirme özgürlüğü, belirgin bir üretkenlik artışı sağlar. Son olarak, sürecin askeri ortamdaki herhangi bir kopyasının iAgile süreç metodolojisi ile tutarlı olmasını sağlamak için bir doktrin geliştirilmelidir.

Doğal olarak bu sürece uygun bir yönetim ekibi oluşturmak önemlidir. Geliştirme çabası arttıkça, daha fazla takım oluşturmanın ve "Scrum of Scrums" yönteminin bir çeşidini kullanarak takımları birbirine bağlamanın gerekli olduğunu gördük.

Geliştirme, yedi kişilik tek bir ekiple başladı ve benzer şekilde yorumlanan yedi ekiple sona erdi. 

Bu, gruplar arasındaki etkileşime uyum sağlamak için döngülerimizi 3 haftalık bir başlangıç ​​süresinden 5 haftaya uzatmamıza neden oldu. 

Aynı zamanda ürün sahibi ve scrum master rollerinin yeniden tanımlanmasını da gerektirdi. 

Ürün sahibi rolü, paydaşları takip etmek için ek bir sorumluluğa sahipti. Bu “yön bulma” rolü, başlangıçta sürecimizde açık değildi, ancak projeye dahil olan paydaşların sayısı göz önüne alındığında, bir zorunluluktu. 

Scrum master rolü, hiyerarşik otorite açısından yeniden tanımlandı. Bu, scrum master'ın ekip üyeleri tarafından ortaya atılan sorunları çözme yetkisine sahip olmasını mümkün kılmak için gerekliydi. Ek olarak, scrum yöneticisi pasif bir şekilde geri bildirim beklemek yerine tüm ekip üyelerinden aktif olarak geri bildirim aldı. Scrum ustaları yetki kazandıkça, onlara geri bildirim döngüsünü devam ettirmek için sorumluluk vermek de gerekli hale geldi. 

Scrum of Scrums'ın yürürlüğe girmesine yardımcı olmak için küresel ürün sahibi rolünü yarattık. Bu rol, her bir bireysel saldırının senkronizasyonundan sorumlu oldu. Son olarak, beceri setleri büyüdükçe, bir sonraki sprintte beceri tahsisini planlamak için beceri setlerinin farkındalığını ve takımlardaki konumlarını yansıtan yeni bir rol yaratmak gerekli hale geldi. Biz ona hücum koçu diyorduk. Bu yönetim yapıları ve rol değişiklikleri, scrum yönteminden sapar ve iAgile'ı standart scrum'dan ayırarak, ilk projesinden bu yana devam eden başarısını da haklı çıkarır. 

Bu proje yönetimi stratejisini test etmek için İtalyan Ordusu için eksiksiz bir komuta ve kontrol sistemi geliştirdik. Bu gelişme, iAgile'ın ilk uygulamasıydı ve sonuç olarak, iAgile'ın ilk vaka çalışmamızın geliştirilmesiyle eş zamanlı olarak geliştiğini söylemek doğru olur. 

## Project Management in Defense Domains

Askeri ortamda en çok kullanılan proje yönetimi metodolojisi, Kontrollü Ortamlardaki Projeler, sürüm 2 (PRINCE2) ve türevleridir, örneğin NATO. 

- Bu tür bir yönetim faaliyeti, hem planlama hem de uygulama aşamalarında yoğun şekilde eğitilmiş profesyoneller ve çok miktarda resmi belge gerektirir. 
- Hızla değişen senaryolar ve değişken gereksinimler için bu eklemli ve zaman alıcı yöntemlerin uygulanması zor olabilir. 

PRINCE2 proje yönetimi süreç tabanlı bir yaklaşım yöntemidir.Bir proje yöneticisi tarafından bir proje yönetiminde uygulanması amaçlanan sekiz temel süreç modellenmiştir.Modelleme, mantıksal bir sıradaki adımlar açısından yapılır. PRINCE2, farklı karmaşıklık aralığındaki çeşitli proje türlerine uyarlanabilir. Kılavuzda (Başarılı Projeleri PRINCE2 ile Yönetmek, 2009), süreç modelini uygulamada bir proje yöneticisi için kılavuz olarak bir dizi “bileşen” listelenmiştir. PRINCE2, kanıtlanmış uygulamalar hakkındaki bilgilerin mevcudiyetine dayanan diğer metodolojilerden farklı olarak, proje yöneticileri ve ekipleri tarafından izlenecek daha kuralcı bir dizi adım sağlar. PRINCE2'nin olası bir avantajı, büyük ölçüde kuralcı olması ve orta ila büyük kuruluşlarda bir dereceye kadar standardizasyona neden olabilmesi gerçeğinden kaynaklanmaktadır. Metodolojinin belirli projelere göre uyarlanması, aynı temel adımların korunması ve aynı terminolojinin kullanılması şartıyla mümkündür. Kurumsal program yönetiminde ilgili faydalar özellikle personel eğitimi ve proje performans takibi alanlarında gözlemlenebilir. Yaratıcılığın olası kısıtlamaları, özellikle insan faktörlerinin tasarım çözümleriyle giderek daha alakalı hale geldiği yazılım geliştirme alanında bir dezavantajdır.

## The iAgile Development Process
iAgile, dağıtılmış scrum'a dayalı bir yazılım geliştirme sürecidir. Tıpkı scrum gibi, iAgile de bir ürün sahibinin, bir scrum master'ın, bir yöneticinin ve bir geliştirme ekibinin bir dizi kısa geliştirme döngüsünde (sprint'ler) somut işlevsellik sağlamak için işbirliği yaptığı yinelemeli bir geliştirme sürecidir.

Ancak, silahlı kuvvetler bağlamında çalışmanın benzersiz zorluğu ve sivil danışmanları artık münferit taşeronlar olarak değil, geliştirme ekibinin ayrılmaz bir parçası olarak dahil etme zorunluluğu, bizi iAgile'ı scrum'dan önemli ölçüde ayıran bazı değişikliklere götürdü. Ayrıca, iAgile'ın alanı, güvenlik ve zarif sistem bozulması gibi belirli işlevsel olmayan gereksinimleri ekleyen savunma ortamı için kritik görev yazılımıdır. Bu gereksinimler, iAgile'ı kuruluşta benimsenen standart scrum süreçlerinden daha da farklılaştırmaya da katkıda bulunur. Aslında, iAgile, çeşitli iAgile rollerindeki personele atanan bir dizi resmi prosedüre sahiptir. Bu rollerin çoğu, scrum yönteminden türetilmiştir, ancak genellikle rollerle ilişkili sorumluluklarda önemli bir yeniden şekillenme söz konusudur. iAgile'ın temel ilkeleri şu şekilde özetlenebilir:

1. Geliştirme ekipleri, üretim sürecindeki en alakalı varlıklardır, ancak faaliyetlerine ekip üyeleri tarafından üzerinde anlaşmaya varılan ve müşteri tarafından tamamen anlaşılabilir bir dizi nesnel, gerçek zamanlı, müdahalesiz etkinlik ve performans ölçümü eşlik etmelidir. Önlem seti, kullanıcı/paydaş öncelikleri (güven, güvenlik, kalite, vb.) tarafından belirtildiği şekilde ürünün en alakalı yönlerini kapsamalıdır. Ölçülerin ilk kullanıcıları ekip üyelerinin kendileridir. Önlemler bir yazılım geliştirme sanal kontrol odasında toplanır ve görüntülenir. Raporlar otomatik olarak oluşturulur ve ilgili tüm topluluk üyelerine gönderilir.
2. Ürün sahibinin (PO) geleneksel rolü, tek bir kişi tarafından kapsanmak yerine küresel ürün sahibi kurulu tarafından paylaşılır. GPO her zaman bir müşteri paydaş temsilcisini, en alakalı uygulama alanı uzmanlarını ve ekiplerin PO'larını içerir. Ekip PO'ları, ekiplerin üretim hedefleri ve programlarında her zaman uyumlu olmasını sağlamak için önemli bir özellik olan ekip senkronizasyonu ve geri bildirimden sorumludur.
3. iAgile'deki scrum master (SM) rolü güçlendirildi ve bir program yönetimi görevi edinildi. SM'nin ekip üyesi üzerinde karar verme yetkisi yoktur (aslında, scrum master'ların kendileri ekip üyeleridir), ancak SM'nin ürettiği raporlar, geliştirme durumunu ve ekip performansını değerlendirmenin tek yoludur. Her rapor, GPO'lara ve paydaşlara ulaşmadan önce ekip üyeleriyle paylaşılır.
4. Ön ekip oluşturma faaliyetleri sırasında teknik ekip üyelerinin becerileri doğru bir şekilde incelenir. Yazılım mühendisliği geçmişine sahip olmak zorunda olmayan konu uzmanlarıyla paralel çalışabilme yeteneği, ekip üyelerinin seçiminde önemli bir faktördür. Geliştiricilerin, çiftteki ikinci programcının bir güvenlik veya kalite uzmanı olabileceği asimetrik rollerle genişletilmiş “çift programlama” uygulaması gerekiyor. Ekip üyelerinin teknik gelişimi, tüm üretim süreci boyunca uygulanır ve ürün biriktirme listesine “bilgi edinme kullanıcı hikayelerinin” eklenmesiyle elde edilir. Özellikle asimetrik çift programlama, scrum'da yaygın olarak kullanılmaz.
5. Sürece yeni bir rol eklendi: *scrum koçu*. Bu rol, geliştirme ekibindeki beceri matrisini takip etmekten ve asimetrik ikili programlama sürecini bilgilendirmekten sorumludur. Standart scrum geliştirmede, takımın beceri farklılaşması yoktur. Ancak çevremizde, bir araya gelen çeşitli beceriler vardır. Kullanıcı gereksinimlerinin karmaşıklığını ve silahlı kuvvetlerin bugün faaliyet gösterdiği bağlamı ele alabilmek için ihtiyaç duyulan danışmanların ve silahlı kuvvetler personelinin benzersiz karışımından gelirler. Takımın beceri setini takip etmemek tehlikeli olabilir çünkü genellikle kullanıcı hikayelerinin ayrılmaz bir parçası olan örtük varsayımların yanlış anlaşılmasına neden olabilir.
6. Proje başlangıcında tüm ilgili paydaşlardan (karar vericiler, üst düzey kullanıcılar ve uygulama alanı uzmanları) oluşan bir ağ oluşturulur ve GPO tarafından profesyonel bir sosyal ağ olarak yönetilir. Ağ, projeyle ilgili tüm bilgileri paylaşmak için kullanılır ve tüm önemli proje kararları hazırlanırken danışılır.
7. Scrum'dan türetilen tüm “ritüeller” (stand-up toplantıları, sprint planlama, incelemeler ve teslimatlar) elektronik biçimde belgelenir veya bantlanır.
8. iAgile'da oynanan roller ile silahlı kuvvetlerin üyeleri olarak oynanan rollerin uzlaştırılması, değişim yönetimi uygulamaları yoluyla güçlü ve kararlı bir şekilde ele alınmalıdır. Bunlar, örneğin, bizim durumumuzda doğrudan Genelkurmay Başkanlığı'ndan gelen üst düzey bir taahhüt; Orduya aşılanması daha kolay olan açık bir aciliyet duygusu; ve bu tür bir sonuca ulaşmak için motivasyon yaratan ve aynı zamanda başarısı kesin olarak tespit edilip ölçülebilen açık, ölçülebilir bir hedef sağlayan nihai sonucun net bir şekilde tanımlanması. Bu son nokta biraz daha detaylandırmayı hak ediyor. Proje yöneticileri genellikle nihai sonucu, ürünün gereksinimlerinin uygulanma yüzdesi ve planlanan bütçeden sapma olarak tanımlar. *Ancak bizim durumumuzda sonuç maliyetler, müşteri memnuniyeti ve kalite açısından tanımlanmaktadır.* Bu proje hedefleri, projeyi yönetmek için kullanılan yöntem ve araçlardan bağımsızdır ve çevik geliştirme yöntemlerinin temelini oluşturan gereksinimler ve geliştirme süreci hakkında belirsizliğe izin verirken kesin olarak tanımlanabilir.

Yukarıda ifade edilen ilkeler, standart kurumsal scrum'dan çok farklı bir süreç yaratmaya katkıda bulunur. Bu, en alakalı olanları eğitim ve kullanıcı topluluğu yönetişimi olan bir dizi zorluk yaratır. Ekip üyelerinin hemen üretken ekip üyeleri olabilmeleri için eğitim çok önemlidir. iAgile yeni ve gelişmekte olduğundan, eğitim de gelişir. Bu nedenle akademiyi yalnızca sürecin tasarımına değil, aynı zamanda çeşitli roller için uygun eğitim programlarının geliştirilmesine de dahil etmek doğaldı. Kullanıcı topluluğu yönetişimi bir meydan okumadır çünkü kavramın kendisi başlangıçta silahlı kuvvetler için belirsizdi. Zorluk, son derece uzmanlaşmış bir ortamda kullanıcı hikayelerini tanımlarken çok sayıda örtük varsayımdan kaynaklanmaktadır. Normalde, geliştirme ekibi bu ortama aşina olduğu için bu bir sorun olmaz. Ancak, varsayımların tutarlılık açısından nadiren kontrol edildiği ortaya çıktı; ve çevreye danışmanlar eklendiğinde, bu varsayımları örtük durumda bırakmanın başarılı projelere yol açmadığı ortaya çıkıyor. Aşağıdaki bölümler, her iki zorluğa da nasıl yaklaştığımızı kısaca açıklamaktadır.

### 1 Training
Bu muhtemelen geleneksel çevik ile karşılaştırıldığında en önemli farklılıkları içeren alanlardan biridir. iAgile, kritik görev uygulamalarıyla ilgili potansiyel güvenlik açıklarının farkındalığını dahil etmek için sürekli olarak değişmektedir. Süreçteki belirli role bağlı olarak, gerçekçi alıştırmaları ve rol oynamayı vurgulayan daha odaklı eğitime ihtiyaç vardır. Geliştirme ekiplerinin tüm bileşenleri (teknik, yönetim ve özel alan uzmanlığı), yazılım ürününün doğasını tam olarak anlamak ve yazılım geliştirme arasındaki farkların farkında olmak için yazılım mühendisliğinin temel kavramlarına ve evrimine aşina olmalıdır. Bu farkındalığın ekiplerde paylaşılması gerekir ve bu nedenle her iAgile eğitim kursunda ortak bir teorik giriş bölümü yer alır. İlk bölümü, üretim sürecinde kapsanacak role bağlı olarak belirli bir pratik bölüm takip eder. Yazılım mühendisleri, gereksinim toplama ve anlama ve sprint yürütme gibi belirli iAgile teknikleri konusunda eğitilirken, süreç yöneticileri invaziv olmayan program yönetimi teknikleri konusunda eğitilir.

### 2 User Community Governance
Kullanıcı Topluluğu Yönetimi 

iAgile'ın temel özelliklerinden biri, yazılım geliştirme sürecine kullanıcı topluluğunun tam katılımıdır. Savunma ve Güvenlik alanındaki kritik görev yazılımı alanı, gerçek ihtiyaçların çoğunun örtük veya gömülü olduğu, genellikle sentetik bir “görev ihtiyacı” belgesi aracılığıyla belirtilen kullanıcı gereksinimlerinin önemli karmaşıklığı ile karakterize edilir. Kullanıcı/paydaş, ortaya çıkarılması çok zor olan ancak uygulamanın doğru uygulanması için çok önemli olan ilgili alana özel uzmanlığa sahiptir. Vaka çalışmasında bildirildiği gibi, kullanıcının yalnızca birkaç ürün teslimatından sonra kendi gereksinimlerini tam olarak anlamaya başlaması oldukça normaldir. Bu ortamda, seçilmiş kullanıcı uzmanlarının geliştirme ekiplerine doğrudan katılımının yanı sıra, daha geniş bir kullanıcı/paydaş topluluğuna ulaşılabileceği bir ağın gerçekleştirilmesi, iAgile projesinin başarısı için hayati önem taşımaktadır.

## iAgile Benefits

1. Maliyetler = maliyet düşürme faktörlerinin çoğu, üretim ekiplerinin belirli ürün karmaşıklığı ile başa çıkmak için artan kapasitesi gibi insani ve sosyal faktörlerle ilgili olduğundan, tam olarak analiz edilmemiştir. Daha etkin bir üretim yapısının (kaynaklar ve zaman) uygulanması ve kullanıcı ihtiyaçlarının/ihtiyaçlarının daha iyi anlaşılması nedeniyle ilgili tasarruflar belirlenmiştir
2. Müşteri Memnuniyeti = geliştirilmiş çevik metodoloji, ağırlıklı olarak kullanıcının üretim döngüsüne güçlü katılımına dayanmaktadır. Katılım, kullanıcı ihtiyaçlarının tanımlandığı ve kullanıcı hikayelerinin müzakere edildiği ilk aşama ile sınırlı değildir, yaşam döngüsü boyunca sürekli olarak uygulanır. Kullanıcı topluluklarından uzmanlar, iAgile'ın temel özelliği konusunda eğitilir ve üretim ekiplerine tam olarak dahil edilir. Sprint incelemeleri sırasında, ürün teslimatını kabul etmesi istenen “müşteri” üst düzey temsilcisi, takım ürün sahibi olarak hareket eden kendi topluluğunun bir bileşeni tarafından nihai sunum brifingini alabilir.
3. Kalite = iAgile tarafından sunulan kalite faydaları, başlangıçta beklenenden daha belirgindir. Çevik yöntemlerin çoğunda, yeni kodun yalnızca ihtiyaç duyulduğunda geliştirileceği, hemen entegre edileceği ve nihayetinde geliştirme ekibinin çoğunluğu tarafından bilineceği için kalitenin daha yüksek olacağına dair bir ilk varsayım vardır. Bu varsayım iAgile'de mutlaka geçerli değildir ve aslında, birden fazla ekip farklı kod tabanlarında çalıştığında, ikili programlama ve sürekli entegrasyon gibi uygulamaların faydalı etkilerinin azaldığını, çünkü ekiplerin fiziksel olarak ayrılmasının bir bilgi ayrılığı oluşturduğunu iddia ediyoruz. Kod doğası gereği bağlantılıdır ve genellikle protokollerle ayırmanın ötesine geçen öngörülemeyen yan etkilerle bağlantılıdır. Bu nedenle, geliştirmemizdeki hata oranının önceki geliştirmelerde ölçtüğümüzden daha düşük olması beklenmemektedir. Ancak, aşağıdaki temel nedenlerden dolayı müşteri tarafından algılanan kalitede belirgin bir iyileşme bekliyoruz: 
   1. Müşteri, gelişmeyi olduğu gibi görebiliyor ve gereksinimlerinin gelişimini etkileyebiliyor doğrudan ve üretken bir şekilde.
   2. iAgile kullanılarak geliştirilen kod tabanı, geleneksel bir yöntem kullanılarak geliştirilen karşılık gelen kod tabanından daha küçüktür, çünkü kod tabanında yalnızca müşterinin ihtiyaç duyduğu gereksinimler hayatta kalır. Böylece, kod tabanının kapsamı daha kesin ve kullanıcı ihtiyaçlarına cevap veriyor.
   3. Daha hızlı geri bildirim mekanizması, kullanıcının bir işlevselliğin geliştirilmesinde hataları erkenden bildirmesine olanak tanır, bu da doğrulama ve doğrulamadan diğer geliştirme yöntemlerine göre daha erken geçme olasılığını artırır.
   
## Conclusions
son derece güvenli, kritik öneme sahip yazılımları daha düşük maliyetlerle ve daha yüksek müşteri memnuniyetiyle oluşturmayı mümkün kılmak için çevik ilkeler kullanan bir yazılım geliştirme ve proje yönetimi yöntemi olan iAgile'ı açıklar. Bu yöntem, çevik ilkelerin, yenilikçi araçların, yapılandırılmış kullanıcı topluluğunun ve geleneksel olarak muhafazakar bir ortamda süreci benimsemek için bir değişiklik yönetimi yolu sağlayan ve kullanıcılar için getirileri ve geliştiricilerin katılımını en üst düzeye çıkaran özel bir çevik geliştirme doktrininin benzersiz bir birleşimidir. 

iAgile, kanıtlanmış bir kurumsal geliştirme yöntemi olan scrum'a dayanmaktadır; ancak danışmanlar ve ordu personelinin bir araya geldiği, görev açısından kritik, son derece uzmanlaşmış bir ortamda çalışmanın gereklilikleri önemli değişiklikler gerektiriyordu. Bunlar, projenin ve ilerlemesinin nesnel bir temsilini oluşturmak için invaziv olmayan bir ölçüm sisteminin tanıtılmasını, ürün sahibinin bir ürün sahibi kurulu ve ekip ürün sahipleri olarak uzmanlaşmasını, scrum master rolünün geliştirilmesini, proje için bir tarama yöntemini içerir.