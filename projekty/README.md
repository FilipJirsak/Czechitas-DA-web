# Náměty na závěrečné projekty

## Stolní hry
Například člověče nezlob se, dáma, pexeso… Určené primárně pro hraní na tabletu s malými dětmi (předškolními). Když je potřeba vyplnit nějakou volnou chvíli,
hrací deska, figurky a kostky nemusí být vždy k dispozici, tablet často ano. Na internetu se dá najít spoustu her, ale ta mají třeba jiná pravidla, než na která jsme
zvyklí – což je pro malé děti komplikace. Navíc jsou obvykle v angličtině, a když hra vypíše _It's your turn, David_, předškolní dítě tomu nerozumí – i když třeba
už pozná své jméno nebo i umí číst.

Co by mohla umět třeba taková hra _Člověče, nezlob se_:
* Jako dospělák si na začátku nastavím, podle jakých pravidel hrajeme (třeba zda se musí figurky v domečku trefit přesně na jednotlivá místa, nebo jestli se vstupem do domečku automaticky řadí odzadu, nebo jestli musí domeček projít až do „postýlky“).
* Pak zadám jména hráčů (případně se to dá vylepšit, že tam místo jen dám fotky hráčů).
* Hráči si vyberou barvy.
* Nastavím pořadí hráčů (podle toho, jak reálně sedíme).
* A můžeme hrát :-)

Ideální bude, když se hra při běžném hraní obejde bez textů – třeba jméno hráče bude mít stejnou barvu, jakou hraje, případně ude mít tak obarvený rámeček kolem fotky.
A když bude hráč na tahu, jméno nebo rámeček se rozbliká. (Případně se to dá vylepšit tak, že texty budou namluvené, nebo se použije text-to-speech pro jejich přečtení).

Co se dá vylepšovat donekonečna je samozřejmě grafika, přidávat různé animace, zvuky a efekty.

Výhodou je, že je to 100% frontend, 0 % backendu. Na konci kurzu to zvládnete samy s malou pomocí od mentora, který vám může poradit, jak dělat animace, jak případně pořídit
fotku a jak řešit nějaké grafické efekty.

A samozřejmě je možné zvolit i jiné hry – třeba pexeso, kam si budu moci nahrát vlastní obrázky. Nebo matematické pexeso, kde budou místo obrázků příklady (a budou se hledat ty,
které dávají stejný výsledek). Nebo pexeso se slovíčky cizího jazyka. Nebo se můžete inspirovat třeba ve
[Velké knize deskových her](https://www.databazeknih.cz/knihy/velka-kniha-deskovych-her-36567) jakoukoli jinou hrou.

## Promítání písňových textů (Karaoke)
Když se společně zpívá s živou hudbou (třeba na hudební mši), je dobré k tomu promítat texty, protože si je ne každý pamatuje. Promítá se obvykle verš po verši a dnes se k tomu
obyvkle používá PowerPoint nebo jiný nástroj na prezentace – a ty nástroje na to nejsou úplně vhodné.

Bylo by tedy fajn mít nástroj, kam nahraju texty písniček (často už to mám v podobě nějakého textového souboru), upravím si je (rozdělím na verše, přidám repetice apod.), pak
si z toho sestavím playlist a mohu začít promítat. Písničky i playlist budou uložené v prohlížeči, ale mohu si je i uložit do souboru a později třeba na jiném počítači zase
nahrát.

Tohle je základ, který je opět 100% frontendový. K tomu se dají přidávat věci, které už budou vyžadovat trošku backendu, ale nic, co byste s malou dopomocí mentora nezvládly:
* Možnost uložit si písničky nebo playlist i na server. Později se to dá rozšířit i o přihlašování, abych mohlé své písničky upravovat a mazat.
* Možnost ovládat přehrávání z druhého okna prohlížeče nebo z mobilu. To určitě chcete! Při promítání z botebooku máte dvě plochy, jedna plocha se promítá projektorem a je tam jen
  aktuální verš. Z druhé plochy se promítání ovládá a vidíte tam kompletní písničku, celý playlist apod. Když se hráči rozhodnou, že nějakou sloku zopakují nebo změní pořadí
  písniček, nikdo neuvidí, jak zběsile hledáte to správné místo. Podobně se dá řešit i ovládání z jiného zařízení – z jednoho zařízení promítáte, z jiného (třeba z mobilu)
  prezentaci ovládáte. 
* Když už budete mít ovládání prezentace z jiného zařízení, může se k promítané prezentaci připojit i někdo další. Nepotřebujete pak ani projektor, každý si text zobrazí
  na svém mobilu.
* A když budete mít písničky uložené na serveru, můžete udělat i jejich veřejný seznam – když pak bude chtít někdo hrát tu samou písničku, nemusí si text sám připravovat.
  (Akorát pozor na autorská práva k textům.)
  
## Časovač pro workshopy a lekce
Při různých akcích je často potřeba odpočítat nějaký čas – dá se 10minutová přestávka, 20 minut na řešení úkolu apod. Ostatně takový časovač znáte z lekcí. Takových
časovačů je spousta, měl by ho mít v sobě i Google (mělo by fungovat do vyhledávacího pole zadat třeba „set a timer for 5 minutes“ – ale mně to nefunguje). Já si ale myslím,
že jich ještě není dost a dá se vymyslet další a lepší :-) Co by takový časovač mohl umět:
  
* Zobrazovat nejen zbývající čas (to dělají všechny časovače), ale i čas konce. Např.: „Přestávka do 15:00, zbývá 05:12.“ A ten zbývající čas bude ubývat.
* Při zadávání zaokrouhlovat absolutní čas. Např. když ve 14:48:37 zadávám přestávku na 10 minut, asi nebudu chtít pokračovat ve 14:58:38, ale zaokrouhlím to na 15:00.
* Připravit si jednotlivé časy do zásoby (rozplánovat si přestávky na celý den), abych je pak nemusel vytvářet až na místě. Na místě pak už jen doladím detaily, prodloužím
  nebo zkrátím přestávku apod.
* Ty připravené časovače si budu chtít uložit do souboru na disk a znovu je načíst. (Když budete chtít trošku backendu, můžete přidat i ukládání na server.)  
* Možnost nahrát si pod časovač svůj vlastní obrázek na pozadí.
* Když se vám bude chtít, můžete připravit různá grafická témata časovače, přidat různé animace, zvuk upozorňující na uplynutí času, nebo třeba hudbu na pozadí.
* Kdybyste se opravdu nudily, můžete přidat do časovače QR kód, který si účastníci načtou mobilem a zobrazí se jim ten samý časovač na jejich mobilu. Případně jim může mobil
  před uplynutím času zobrazit notifikaci.
* A kdybyste opravdu trvaly na tom, že tam musí být i nějaký backend, můžete tam přidat možnost změny času časovače tak, aby se aktualizoval i na těch mobilech a zobrazila se
  notifikace („Prodlužujeme přestávku na oběd do 14:00.“).
  
S výjimkou dvou volitelných funkcí, kde je to uvedeno, je to opět 100% frontend.

## Čtecí zařízení (např. pro podcasty)
Profesionálové při čtení textů na kameru používají čtecí zařízení, které jim zobrazuje text, který mají říct. Používají to moderátoři v televizi nebo politici při svých projevech. Předmětem projektu je vytvořit webovou aplikaci, která bude fungovat na stejném principu – uživatel si pustí text na tabletu vedle mobilu, nebo na obrazovce počítače pod kamerou, a bude číst text, který si připravil. Jako vylepšení je možné zobrazovat text zrcadlově převrácený bíle na černém – pokud bude mít někdo polopropustné zrcadlo před kamerou, může použít stejný princip, který používají profesionálové.
Aplikace by umožnila připravit si text ke čtení, uložit ho do souboru a načíst ze souboru. Dále umožní připravit časování (důležitá věc pro nezkušené lidi – čtecí zařízení by mělo užiavtele donutit, aby četl pomalu a tím pečlivěji vyslovoval). Dále může aplikace podporovat další možné funkce:
* Vzdálené ovládání (zrychlení, zpomalení)
* Přidávání doplňkových informací – frázování, emoce, gesta…
* Podpora pro víc lidí – např. barevné odlišení, kdo mluví.
* Frajeřinka by byla využít [API pro rozpoznávání mluvené řeči](https://developer.mozilla.org/en-US/docs/Web/API/SpeechRecognition), sledovat, co uživatel říká, a podle toho mu přizpůsobit posouvání textu.[](url)
