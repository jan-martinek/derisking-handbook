---
title: Základní principy návrhu moderního softwaru
---
Technologické projekty mají větší šanci uspět, pokud „netechnické“ profese dohlížející na jejich průběh a rozpočet rozumí šesti základním principům moderního vývoje softwaru, kterými jsou: **design zaměřený na uživatele**, **agilní vývoj softwaru**, **DevOps**, **modulární architektura**, **modulární zakázky** a **vlastnictví produktu**.
Jde o obecné principy, jejichž pochopení nevyžaduje technické vzdělání.
Ale jakmile je jednou ovládnete, dostanete se skrz vatu a technický žargon na jádro úspěšného řízení softwarových projektů.

## Design zaměřený na uživatele

Veškerý vývoj softwaru by se měl točit kolem potřeb skutečných koncových uživatelů, konkrétních lidí, kteří budou systém používat.
Těmito koncovými uživateli mohou být například žadatelé o dávky, pracovníci call center, sociální pracovníci nebo kdokoliv jiný ze státní správy a bezpočtu dalších společenských skupin.

Návrh softwaru pro uživatele a s uživateli snižuje rizika projektu, protože zvyšuje šance, že výsledný software bude řešit skutečné problémy – nikoliv to, co za problémy považuje omezená skupina účastníků projektu.
K identifikaci oněch skutečných problémů existuje řada různých postupů, například rozhovory s uživateli nebo testování použitelnosti.

V projektu zaměřeném na uživatele slouží veškerá práce k naplnění potřeb koncových uživatelů.
Práce se hledá a prioritizuje v těsné a pravidelné spolupráci s koncovými uživateli a přihlíží k technickým omezením, kterým ovšem bezvýhradně nepodléhá. (Jinými slovy, cílem práce je získat nějakou novou hodnotu pro uživatele.
Během tohoto procesu je nutné respektovat možnosti zvolených technologií, například programovacích jazyků nebo serverového softwaru, ale zdánlivá technická omezení by nikdy neměla vést k tomu, že se nějaká práce vynechá.) Technický tým i koncoví uživatelé během práce pravidelně kontrolují výstupy a systém se nepovažuje za hotový, dokud koncoví uživatelé neodsouhlasí, že splňuje všechny jejich potřeby.

Design zaměřený na uživatele stručně řečeno říká, že je potřeba řešit problémy konkrétních relevantních uživatelů, nikoliv problémy šéfů jejich šéfů.

## Agilní vývoj softwaru

Ve státní správě odjakživa převládá praxe podrobného plánování velkých softwarových projektů nadlouho dopředu.
Nejen vývojáři softwaru ovšem už před léty došli k tomu, že tyto plány nikdy neodpovídají realitě a vždy vyžadují řadu drahých úprav.
Takže je načase, aby i zadavatelé přestali vyžadovat podrobné dlouhodobé plánování a začali softwarové projekty rozpočtovat jinak.

Metodě plánování celého projektu předem se říká _vodopád_.
Kdybyste tímto stylem plánovali dejme tomu měsíční rodinný výlet po Evropě, pečlivě byste předem naplánovali každý den od podrobného itineráře cesty přes zamluvení hotelu až po předplacení všech jídel nebo zakoupení lístků na různé atrakce.
Což by vůbec nefungovalo, protože byste nevyhnutelně narazili na změny, nečekané možnosti a podobně.
Racionálně uvažující člověk nebude chtít rozhodnout všechno předem na začátku cesty, protože ještě neví, co ho cestou čeká.
Většina lidí by si naplánovala hrubou trasu a klíčové zastávky – a podrobnosti by doplnili až po cestě.

Podobný, takzvaný _agilní_ přístup lze zvolit ve vývoji a modernizaci softwarových systémů.
Agilně vedené projekty nespoléhají na léta drahého plánování a sbírání požadavků, po kterém by teprve došlo na samotný vývoj softwaru.
Agilní projekty se plánují pouze v hrubých obrysech a kladou důraz na co nejrychlejší start reálných prací, které pak postupně směřují k dobře popsanému celkovému cíli projektu.
Na jeho naplnění obvykle pracuje malý, samostatný a motivovaný tým (obvykle 5–9 lidí včetně vývojářů, produktových manažerů, UX expertů, copywriterů nebo bezpečnostních expertů), který se soustředí na potřeby koncových uživatelů a v opakovaných dvoutýdenních cyklech dodává konkrétní, fungující software.

První den každého cyklu si tým naplánuje práci na následujících 14 dní. (Cyklus může být kratší, například týdenní, i delší, například až měsíční.
Dva týdny jsou nejčastější.) Každý úkol, na kterém bude pracovat, má podobu takzvané „user story“ neboli uživatelského příběhu, což je konkrétní uživatelská potřeba identifikovaná během práce s uživateli.[^stories]
Seznamu všech user stories se říká _backlog_.

Na vybraných user stories tým 14 dní pracuje a na závěr cyklu zkontroluje výsledky, otestuje je na uživatelích a nabere si další user stories z backlogu na příští cyklus, načež se vše opakuje.
Cyklům se obvykle říká _sprinty_.

Software dodaný v úvodních sprintech obvykle nestojí za mnoho a často je dokonce později úplně nahrazen jiným, ale důležité je, že pomalu a systematicky formuje technický přístup celého projektu a pomáhá jej smysluplně integrovat mezi stávající systémy úřadu.

Každý sprint bez výjimky končí dodáním fungujícího softwaru – plně otestovaného, plně dokumentovaného, připraveného k použití.
Dochází tedy k průběžnému dodávání hodnoty až do okamžiku, kdy je systém připraven k širšímu nasazení.
Tým pak pracuje dál, dokud se nevyčerpají všechny cíle nebo peníze, podle toho, co přijde první.[^agile]

Dodavatel je placen za čas svých zaměstnanců, nikoliv za softwarový systém.
Veškeré výstupy – software, dokumentace, výzkum, grafické návrhy, _zkrátka_ _všechno_ – patří státu a jsou odevzdány na konci každého sprintu.
Technologie se mění, státní politika se mění, předpisy se mění, zákony se mění, priority se mění. Žádný projekt naplánovaný pečlivě do detailu předem se s těmito změnami nebude schopen vyrovnat a je velká šance, že vůbec nedojde do konce – anebo jen za cenu výrazných vícenákladů, průtahů a drahých požadavků na změny.

Díky spojení agilního vývoje s designem zaměřeným na uživatele může vývojářský tým neustále iterovat směrem ke skutečným potřebám uživatelů, a to způsobem, na který by při plánování předem nikdy nepřišel.

V roce 2019 vydalo americké ministerstvo obrany studii Software Acquisition and Practices (SWAP), která obsahuje i stručný návod, [jak odhalit rádoby agile](https://media.defense.gov/2019/May/02/2002127286/-1/-1/0/DIBGUIDEDETECTINGAGILEBS.PDF).
Najdete v něm praktický souhrn pravidel agilního vývoje a sadu otázek, kterými si i netechnický lídr týmu může ověřit, že skutečně dělá agile a nikoliv parodii na něj.

## Vlastnictví produktu

Pokud chtějí týmy ve státní správě získat zpět kontrolu nad svými projekty, musí se soustředit na výsledky, nikoliv na výstupy.
To znamená, že musí upustit od některých tradičních manažerských praktik a orientovat se především na produkt.

Slovo „produkt“ může znít v kontextu státní správy cize, ale jde o důležitou součást terminologie technologického světa.
„Produkt“ je zkrátka cokoliv, co vzniká: webová stránka, mobilní aplikace, intranetová aplikace, atd.
A ačkoliv to slovo dává větší smysl v kontextu běžného byznysu, prakticky celé produktové uvažování se dá bezvadně uplatnit i ve státní správě.

_Product owner_ neboli vlastník produktu je klíčovou osobou každého softwarového projektu a _musí_ jít o státního zaměstnance.
Vlastník produktu spolupracuje se všemi zainteresovanými stranami na směřování produktu, s důrazem na to, aby z něj mohli co nejrychleji těžit koncoví uživatelé.
Vlastník produktu je součástí agilního procesu vývoje, ve kterém průběžně definuje a prioritizuje práci produktového týmu, pomocí jasných [výkonnostních metrik](https://www.atlassian.com/agile/project-management/metrics) měří pokroky projektu a komunikuje se všemi zúčastněnými stranami.

Vlastník produktu nepotřebuje špičkové znalosti technologií.
Měl by ale znát uživatele systému, jeho doménu (například systém zdravotního pojištění nebo fungování registru vozidel) a různé mantinely, ve kterých se systém musí pohybovat.

Silný vlastník produktu se stará o to, aby měl projekt jasnou vizi a strategii, aby měly projektové týmy prostor pro vlastní rozvoj a aby stavěly nebo nakupovaly to, co bude skutečně postupně přinášet hodnotu koncovým uživatelům.
Nemilosrdně prioritizuje tak, aby produkt splňoval potřeby uživatelů a největší pozornost dostávaly potřeby, které jsou v dané chvíli nejdůležitější.
Vlastník produktu potřebuje od svého úřadu dostatečný mandát, aby mohl zastupovat účastníky projektu a dělat operativní rozhodnutí bez komplikovaných rozhodovacích hierarchií.

Tato představa se liší od běžného projektového řízení státních projektů.
Agilní vlastník produktu nemá Ganttův diagram ani podrobnou pětiletku.
Naopak má ale jasnou představu, čím pomůže koncovým uživatelům a jak toho dosáhne.
Jeho nejdůležitějším úkolem je pečlivě sledovat celý vývojářský tým a hlídat, aby se pohyboval na ideální hranici mezi potřebami státu a potřebami koncových uživatelů systému.

Vlastník produktu se může učit za pochodu, ale je lepší ho proškolit předem.
Agilní vývoj nebo některé jeho konkrétní varianty (například Scrum) vyučuje řada kurzů, některé přímo určené pro vlastníky produktů. Škála je široká od videí na YouTube až po [osobně vedené vícedenní kurzy s certifikací](https://www.scrumalliance.org/courses-events/search?ctyp=Cspo&rad=30&pg=1). Čím důležitější projekt, tím formálnější a důslednější by mělo být vzdělání vlastníka produktu.

## DevOps

Historickým vývojem došlo k tomu, že o provoz hotového softwaru se často stará jiný tým než ten, který jej vytvořil.
Dodavatel například stráví několik let vývojem softwaru a následně ho předá státnímu IT týmu (anebo jinému dodavateli), kterému občas zabere měsíce práce, než systém bezchybně rozběhne na svých serverech.
Celý proces obvykle doprovází nemalá míra frustrace a vzájemného obviňování, výsledkem čehož může být i selhání celého projektu.
Státní správa proto často trvá na tom, že dodavatel softwaru musí systém i provozovat, na vlastní infrastruktuře a neomezeně dlouho.
Tím se výrazně omezuje soutěž mezi dodavateli (většina z nich se hostingem softwaru nezabývá) a dochází k závislosti na jednom dodavateli (_vendor lock-in_), ze které pak obvykle plynou vysoké provozní náklady.
Spoléháním na tento zastaralý režim provozu získáte za větší peníze menší hodnotu, než jakou byste dostali, kdybyste zvolili moderní nástroje běžně používané v soukromém sektoru.

Řešením je DevOps, tedy spolupráce týmů zodpovědných za vývoj (_**dev**elopment_) a provoz softwaru (_**op**erations_).
Cílem je automatizovat práci, která je potřeba k testování softwaru a jeho nasazení na produkční server, kde z něho mají užitek uživatelé.
Vývojáři už pak nemohou prostě předat dokončenou práci provoznímu týmu s tím, že „jim to funguje“.
Součástí jejich práce je napsat automatické procesy pro správné nasazení softwaru na produkční server.
Nesou zodpovědnost – jak praktickou, tak smluvní – za to, že jejich kód poběží na serveru správně.[^devops]

Je dost pravděpodobné, že tímto způsobem vznikla většina softwaru, který denně používáte na svém telefonu a počítači.
DevOps automatizuje testování kvality, testování bezpečnosti, integraci práce od více vývojářů i nasazování softwaru na server.
Pokud je součástí tohoto procesu i testování bezpečnosti, přidává se do zkratky občas i bezpečnost, _security_, a mluví se tedy o DevSecOps.

## Modulární architektura

Velké a složité softwarové projekty mají tendenci se hroutit pod vahou vlastní administrativy. Žádný z jednotlivých vývojářů nerozumí celému systému, ale každý nový člen projektového týmu zvyšuje složitost komunikace uvnitř týmu.
Roste potřeba dalších dodatečných rolí (například softwarových architektů), se kterými musí vývojáři konzultovat svou práci, a jednotliví vývojáři se musí navzájem pečlivě koordinovat, aby předešli konfliktům.
S rostoucí velikostí týmu zkrátka roste režie na jeho řízení a klesá čas strávený samotnou prací.

Pokud se chcete tomuto osudu vyhnout, je lepší velké projekty rozbít na několik menších, víceméně samostatných.
V tomto modelu každá komponenta komunikuje s ostatními prostřednictvím jednoduchých modulárních standardů, takže libovolný kus skládačky lze kdykoliv vyměnit.
Místo monolitu, na který bude za pár let každý nadávat, vznikne malý ekosystém, jehož jednotlivé části lze snáz aktualizovat a upravovat podle měnících se potřeb.
Každou komponentu má na starosti samostatný agilní tým, který se mimo jiné stará o dokumentaci komunikačního rozhraní komponenty (API, _application programming interface_).
Nároky na koordinaci mezi týmy pak nejsou tak velké – z větší části jim stačí sledovat dokumentaci API ostatních komponent, se kterými spolupracují.

Pokud jednotlivé komponenty používají dostatečně obecné, abstraktní API (tedy jakýsi společný standard), mluvíme o architektuře orientované na služby neboli _service-oriented architecture_, SOA.
Jde vlastně o analogii konceptu standardizovaných součástek, který umožnil průmyslovou revoluci.
Standardizovaná rozhraní jsou základní ideou cloud computingu, elektrických zásuvek, USB konektorů, Lega, vlaků a nespočtu dalších moderních produktů a procesů.

Modulární návrh IT systémů z menších kusů propojených otevřenými a dokumentovanými API je „stříbrná kulka“, která vede k flexibilním a udržitelným systémům, lepšímu naplnění uživatelských potřeb a snížení provozních nákladů.

## Modulární zakázky

Agilní vývoj zaměřený na uživatele, vlastnictví produktu, DevOps a modulární architektura umožňují rozdělit velké, vysoce rizikové projekty na menší a zvladatelnější zakázky.
Jednotlivé kontrakty by měly být natolik malé, aby se úřad nemusel bát odebrat zakázku špatně fungujícímu dodavateli a nahradit jej jiným. (Podrobně viz sekci _Nakupujte služby, ne software_.) Zbytek dodavatelů mezitím může pracovat dál, takže celková ztráta hybnosti bude minimální.
Nový dodavatel by navíc neměl mít potíže přebrat práci po předchozím, protože ten měl podle pravidel agilního vývoje dodávat co 14 dní úplný, dokumentovaný a otestovaný software.
Další výhodou modularizace je, že se výsledné kontrakty mohou vejít do limitu pro malé zakázky a jsou tím pádem zatížené menší administrativní režií.

Existují dodavatelé, kteří se na tento styl práce přímo specializují.
Zhruba se dá říct, že agilní vývojářský tým 5–9 lidí stojí zhruba 1–2 miliony dolarů ročně, podle přesného umístění.

Tento přístup vyžaduje koordinaci a ochotu na straně investora.
Lidé zodpovědní za nákup softwaru bývají často zvyklí na tradiční přístup outsourcování IT projektů: jedna zakázka popsaná dlouhým poptávkovým dokumentem, ještě delší nabídky ze strany dodavatelů a zastaralé certifikace vesměs založené na metodice vodopád.
Obecně řečeno nemají agilní týmy zaměřené na uživatele ani páru o tom, co znamená CMMI nebo EVMS – tyto standardy už se dnes za vhodnou cestu k flexibilním a nákladově efektivním systémům nepovažují.
Celkově tedy jde o zbytečnou překážku pro vstup dalších dodavatelů, kteří mohou ve spolupráci se státem teprve začínat a nechce se jim investovat zdroje do sepisování nabídkových dokumentů.

---

Moderní procesy vývoje softwaru vychází z potřeb uživatele, používají agilní metodiku vývoje a opírají se o vlastnictví produktu, DevOps, modulární architekturu a modulární zakázky.
Pochopením těchto klíčových konceptů získáte dobrou šanci řídit softwarové projekty efektivně a zvládnout zbytek tohoto textu.

[^stories]: User story má obvykle formu „jako [role uživatele] potřebuji [funkce], abych [důvod]“.
Například: „Jako sociální pracovník potřebuji mít poznámky k danému případu uložené na telefonu, abych se k nim dostal i v oblastech bez mobilního signálu.“
Veškerá technická práce pak má za úkol pokrýt nějakou user story.

[^agile]: Podle [výzkumu serveru Stack Overflow](https://insights.stackoverflow.com/survey/2018#work-_-which-methodologies-do-developers-use) z roku 2018 provedeného mezi 57 075 vývojáři používá agilní metody 85 % profesionálních softwarových vývojářů.
Podobně [studie společnosti HP](https://softwaretestinggenius.com/docs/4aa5-7619.pdf) z roku 2015 zjistila, že „drtivá většina oslovených organizací dnes primárně používá agilní metody vývoje“.
Popisovaný proces tedy není nijak výjimečný.

[^devops]: Další informace o DevOps například v článku amerického ministerstva obrany [Is Your Development Environment Holding You Back? A DIB Guid for the Acquisition Community](https://media.defense.gov/2018/Oct/09/2002049592/-1/-1/0/DIB_DEVELOPMENT_ENVIRONMENT_2018.10.05.PDF).
