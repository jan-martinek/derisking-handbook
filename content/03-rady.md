---
title: Rady pro rozpočtování a řízení technických projektů
---

## Změňte svůj pohled na rizika

Za posledních pár desítek let státní správa přestala pro vývoj kritických systémů používat vlastní zaměstnance a začala spoléhat na externí dodavatele.
Jde o zdánlivě bezpečnější řešení, které je často motivované také omezenými vlastními kapacitami a sliby levnějších „krabicových“ řešení ze strany dodavatele.

Na projektech jako Heathcare.gov jsme se ovšem naučili, že outsourcovat jde pouze práci, nikoliv riziko selhání.[^healthcare]
Neúspěšné projekty jdou na vrub zadavatele, nikoliv dodavatelů.
Státní správa je občanům zodpovědná za své fungování a její úřady tedy musí mít pod kontrolou projekty, na které fungování státu spoléhá.
Pokud úřad žádá o peníze na IT systém, ve skutečnosti nepotřebuje vyřešit technický problém – potřebuje vyřešit nějaký problém spojený s fungováním státu.
Technologie zde slouží jako prostředek, nikoliv jako cíl.

To neznamená, že by státní správa musela všechny systémy vyvíjet vlastními silami.
Musí mít ale jasná očekávání ohledně lidských výstupů a technických standardů spojených s bezpečností dat, jejich používáním, interoperabilitou, sledováním a vyhodnocováním.

Zatímco technické know-how je běžně dostupné a levné, schopnost vést státní úřad je vzácná a cenná.
Státní správa musí přijmout odpovědnost za vlastní projekty a riziko jejich selhání; externí dodavatelé by měli fungovat pouze jako najatá pomocná síla, kterou lze v případě nespokojenosti snadno nahradit.

### Kontrolní seznam

* Projekt má vyhrazeného vlastníka s dostatečně silným mandátem.
Vlastník je zaměstnanec zadavatele, nikoliv externista nebo zaměstnanec nějaké státní IT společnosti.
* Všichni účastníci projektu si uvědomují, že stávající přístup metodou vodopád většinou nevede k úspěchu a přechod k agilnímu vývoji a modulárním zakázkám toto riziko výrazně snižuje.
* Účastníci projektu nepovažují externí dodavatele za „vlastníky“ projektu nebo jeho výstupů, ale za nahraditelné pomocníky.

### Klíčové otázky

* Určili a proškolili jste státního zaměstnance (nikoliv externího dodavatele!), který bude fungovat jako vlastník projektu a bude udávat jeho směr a priority a dohlížet na práci vývojářského týmu?
* Existuje v úřadu hierarchie, v rámci které může kdokoliv získat shora podporu týkající se nové metodiky vývoje?
Sahá tato hierarchie až do nejvyšších pater veřejné správy?
Může někdo z účastníků projektu novou metodiku bojkotovat?
Pokud ano, jakým způsobem můžete tyto problémy předat výš a vyřešit je, aniž by ohrozily úspěch projektu?
* Jakým způsobem přebírá úřad zodpovědnost za vedení projektu a vlastnictví jeho výstupů?
Nepřenáší riziko na externího dodavatele?

## Nakupujte služby, ne software

Když poptáváte software, nekupujete _věc_, ale _službu_: práci týmu vývojářů a designérů na základě priorit určených vlastníkem produktu.
Tento myšlenkový posun vede k úplně jinému – mnohem jednoduššímu – poptávkovému řízení a formulování smluv.

Váš poptávkový dokument neboli RFP (_Request for Proposal_) by měl popisovat obecný cíl projektu a měl by obsahovat první verzi produktového backlogu, tedy seznamu práce, kterou je potřeba udělat.
Tento výčet sepsaný vlastníkem produktu by měl mít podobu _user stories_, tedy potřeb koncových uživatelů, a mělo by být jasně řečeno, že slouží pouze k hrubé představě o typu poptávaných prací, nikoliv jako jejich vyčerpávající a definitivní seznam.
Oběma stranám musí být zřejmé, že detailní předmět práce se bude měnit v závislosti na prioritách a postupující analýze potřeb; se změnami je třeba počítat předem a pro moderní metody vývoje softwaru by neměly představovat problém.

Poptávkový dokument by měl popisovat spíše cíle projektu než výčet prací nebo podrobných vlastností produktu.
Tím se vyhnete tradičním doobjednávkám změn u dodavatele, protože rozsah prací není dán předem a tým pracuje zkrátka na tom, co mu řeknete.
Pokud se váš dodavatel pyšní „agilním“ přístupem, ale změny má tendenci řešit pomocí dodatečných objednávek, mělo by se vám v hlavě rozsvítit červené světlo.

Abyste měli jistotu, že dodavatel naplní požadované technické specifikace, měl by váš poptávkový dokument obsahovat plán posuzování kvality (QASP, _Quality Assessment Surveillance Plan_) vhodný pro agilní vývoj.
Podle tohoto plánu se na konci každého sprintu posoudí, jestli jsou odevzdané výstupy otestované, zabezpečené, přístupné, dokumentované a správně nasazené.[^qasp] \(Ukázkový plán posuzování kvality najdete v dodatku B.) Kvalitativní požadavky může naplnit pouze skutečný, nasazený a fungující software, nikoliv sebelepší popis toho, co bude software dělat někdy v budoucnosti.

Historicky existuje velký tlak na to, aby zakázky probíhaly za pevnou cenu, protože to zdánlivě snižuje jejich rizika.
Pokud ale můžete průběžně vyhodnocovat kvalitu skutečně dodaného softwaru, pak vám větší flexibilitu dávají průběžné platby za čas a náklady (se stropem pro celkové výdaje).
Tento režim placení vám navíc dává jednodušší cestu ven pro případ, že dojde k zásadní změně zadání projektu, nebo když nejste spokojeni s kvalitou dodaného softwaru.
Pokud práce dodavatele z libovolného důvodu nenaplňuje vaše představy, prostě mu přestanete zadávat další úkoly, kontrakt tím efektivně vzato zanikne a můžete zkusit jiného dodavatele.

### Kontrolní seznam

* Projekt má vyhrazeného vlastníka s dostatečně silným mandátem.
Vlastník je zaměstnancem zadavatele, nikoliv externistou nebo zaměstnancem nějaké státní IT společnosti.
* Osoba zodpovědná za podpis zakázky se staví pozitivně k projektu samotnému i k novým metodám vývoje softwaru.
* Poptávkový dokument je formulován čistě jako poptávka vývojářských služeb, nikoliv jako poptávka konkrétního výstupu.
* Poptávkový dokument požaduje multifunkční tým, který kromě vývojářů obsahuje například designéry nebo experty na UX.
* Poptávkový dokument nemá více než 20 stránek.
* Poptávkový dokument obsahuje backlog alespoň s desítkou user stories.
* Platby budou probíhat průběžně podle času a nákladů, se stropem pro celkové výdaje.
* Pro výběr dodavatelů bude použit nejjednodušší možný nástroj, který vám umožní oslovit vhodné dodavatele.

### Klíčové otázky

* Má produktový vlastník mandát dělat rychlá autoritativní rozhodnutí za celého zadavatele?
* Je produktový vlastník připraven investovat do své role většinu svého pracovního času?
* Je vedení zadavatele připraveno řídit produkt podle zjištěných potřeb koncových uživatelů, na základě přímých konverzací s těmito uživateli?
Anebo chce řídit produkt podle vlastních osobních preferencí?
* Mluví poptávkový dokument jasně o pravidelném odevzdávání fungujícího kódu, dokumentace a testů? Říká jasně, že veškeré pracovní výstupy budou majetkem státu?

## Pozor na past komerčního softwaru na míru

Běžný krabicový komerční software (_Commercial off-the-shelf Software,_ COTS) a software poskytovaný jako služba (_Software as a Service_, SaaS) nabízí výbornou příležitost, jak pořídit nový software nebo infrastrukturu rychle, bez nutnosti vyvíjet software na zelené louce.
Pokud například potřebujete textový procesor, dává bezvadný smysl koupit standardní krabicový produkt.

Pokud ale poptáváte velký, specializovaný systém, bez kterého se neobejdete, dávejte si na nabídky běžného komerčního softwaru velký pozor.
Dodavatelé velice často prezentují svůj komerční, „na míru upravitelný“ software jako všelék, který zvládne všechny vaše jedinečné regulatorní a procesní požadavky.
A nejspíš mají pravdu – ovšem většinou jen za cenu výrazných úprav.

Než tedy podobný software zakoupíte, poptejte se jiných státních úřadů, jaké s ním mají zkušenosti.
Velmi pravděpodobně se dozvíte, že produkt, který byl prezentován jako hotové řešení, si nakonec na úpravách vyžádal mnohem víc času a peněz, než se původně předpokládalo.

Při plánování rozpočtu nediktujte konkrétní řešení, dejte úřadu prostor pro výběr, které části systému si může koupit a které postavit.
Pokud rozpočet vyžaduje krabicový software, úřad může skončit uvázaný k vysoce upravované verzi krabicového produktu, která nepůjde bez velkých nákladů upgradovat.
A podobně pokud rozpočet předepisuje použití SaaS řešení, může tím úřad natlačit do nevyhovujícího SaaS systému, u kterého utratí podstatné peníze za dodatečného „softwarového integrátora“ a propojení se stávajícími systémy.
V obou případech dochází k nežádoucímu _vendor lock-inu_, závislosti na jednom dodavateli.

Běžný komerční software skutečně může být dobrým základem i pro velké nové systémy.
Ale zadavatel musí k jeho volbě přistupovat s otevřenýma očima a vědomím, že v něm velmi pravděpodobně nekupuje specializované řešení na klíč.

### Kontrolní seznam

* Rozpočet projektu nepředepisuje použití krabicového softwaru, SaaS, ani softwaru na míru, ale dává zadavateli možnost vybrat libovolnou kombinaci těchto přístupů podle potřeby.
* Tvrzení dodavatele o tom, že jeho krabicový software nebo SaaS bude fungovat i bez nákladných úprav, je nezávisle ověřeno u jiných států nebo úřadů, kde tyto produkty používají a mají s jejich úpravami zkušenosti.

### Klíčové otázky

* Pokud si necháváte upravit krabicový software na míru, jak budou probíhat jeho budoucí aktualizace?
Kolik další práce bude potřeba na integraci těchto úprav a kdo za to zaplatí?
* Co se stane, když váš poskytovatel SaaS jednoho dne zčistajasna skončí?
* Bude mít stát bezplatný a snadný přístup ke svým datům, datovým modelům a API?

## Chtějte důkazy místo slibů

Historicky se pokrok v softwarových projektech nejčastěji měřil porovnáváním dokončené práce s časovým harmonogramem napsaným na začátku projektu, k čemuž slouží nástroje jako Ganttovy diagramy nebo seznamy hotových úkolů.
Tento přístup má jednu nevýhodu: nefunguje.
A právě na tom, že nefunguje, je založený celý agilní vývoj.
Moderní softwarové týmy vůbec netuší, co znamenají zkratky jako CMMI nebo EVM, a nebudou mít zájem o projekty, které něco podobného vyžadují.

Místo abyste pokrok poměřovali nějakým grafem, který za tím účelem vznikl, je lepší sledovat objem skutečně hotové práce.
Přidejte se na konci každého sprintu k závěrečné poradě, kde se celému projektovému týmu a přizvaným koncovým uživatelům předvádí práce dokončená v rámci sprintu.
Vyzkoušejte si hotový web.
Nainstalujte aplikaci.
Shánějte se po takzvaném [diagramu spalování](https://en.wikipedia.org/wiki/Burn_down_chart) (_burn down chart_), který ukazuje množství zbývající práce a potřebného času.

Důležitou pojistkou proti iluzornímu pokroku je také plán posuzování kvality (_Quality Assurance Surveillance Plan_, QASP), který by měl být součástí smlouvy s dodavatelem.
Podle tohoto plánu se na konci každého sprintu kontroluje, jestli veškerá odevzdaná práce odpovídá předepsaným standardům.
Plán jasně říká, jakým způsobem stát zjistí, jestli je práce dostatečně kvalitní – a tím pádem předchází i nepříjemným překvapením pro dodavatele. (Ukázkový plán najdete v dodatku B.)

Plán posuzování kvality nevyžaduje vznik výstupů čistě pro kontrolu průběhu práce – nejlepší je prostě zkoušet, _jestli výsledek skutečně funguje_.
Jde o radikálně odlišný přístup k hlídání pokroku technologických projektů.
Má výhodu v tom, že je objektivnější, měřitelnější a funkčnější než subjektivní či právnické interpretace nějakých sáhodlouhých seznamů systémových požadavků.

### Kontrolní seznam

* Vlastníkem produktu je vyhrazený státní zaměstnanec s dostatečně silným mandátem.
* Neexistují žádné plánovací nebo reportovací požadavky, které by byly v rozporu s agilním vývojem.
Neexistují tedy například žádné termíny, do kterých by měly být hotové konkrétní úkoly, a neexistuje podrobná specifikace požadovaných funkcí – ani v poptávkovém dokumentu, ani v akvizičním plánu, ani v legislativě.
* Na konci každého sprintu zkontroluje státem zaměstnaný vývojář, jestli dodaná práce splňuje měřítka definovaná plánem posuzování kvality.
* Všichni nadřízení vlastníka produktu jsou ochotni posuzovat pokroky projektu primárně v podobě demonstrací fungujícího softwaru, diagramu spalování a přehledu hotových a zbývajících user stories.
* V úřadu je předem určen člověk, který je připraven opakovaně vysvětlovat pokroky projektu všem nadřízeným, pro které může být způsob sledování pokroku agilních projektů na rozdíl od vodopádu nezvyk.

### Klíčové otázky

* Jste schopni nabídnout všem účastníkům projektu podporu při přechodu na takto radikálně odlišný způsob měření pokroku projektu?
Od samotného státního úřadu až po nejvyšší úrovně veřejné správy?
Může se někdo z nich zablokovat a trvat na Ganttově diagramu, takže by agilní vývoj nepřipadal v úvahu?
* Kdo bude mít na starost prezentaci výsledků mimo úřad, tedy například parlamentním komisím?

## Investujte do vlastních lidí

Lidé bez zkušeností s vývojem softwaru nemohou kvalifikovaně vést softwarové projekty ani rozhodovat o jejich rozpočtech.
Stát musí zajistit, aby úřady zaměstnávaly dostatek lidí s odpovídajícími zkušenostmi.

Je sice lákavé „vyřešit“ tento problém spoléháním na zaměstnance nějaké centrální státní IT agentury nebo na dodavatele, ale jedině sám zadavatel je schopen přesně posoudit vlastní potřeby, vysvětlit je dodavatelům a následně zkontrolovat jejich výstupy.
Proto nutně potřebuje zvládnout související know-how.

Snažte se zjistit, jestli lidé zodpovědní za vedení a rozpočet projektu mají odpovídající technické zkušenosti.
S výjimkou těch úplně nejmenších úřadů má prakticky každý někoho technicky orientovaného, kdo může vedení projektu doplnit – ačkoliv naopak prakticky nikdo k tomuto účelu nezaměstnává přímo softwarové vývojáře.

Pokud nemáte potřebné know-how sami, musíte zaměstnat někoho, kdo ho přinese, i kdyby to mělo být jen na určitou dobu nebo externě.
Nejlepší je vývojář nebo designér se zkušenostmi ve vývoji moderního softwaru, ideálně pro státní sektor.
Také můžete jednoho nebo víc zaměstnanců poslat na školení základů agilního vývoje softwaru, po celých Spojených státech je řada programátorských „kempů“ a existují i online varianty.

Náklady na zaměstnání vývojáře nebo zvýšení kvalifikace stávajících zaměstnanců jsou ve srovnání se státními výdaji za IT směšné.
A jakmile váš zaměstnanec jednou zažije agilní projekt od začátku do konce, rozhodování o rozpočtech dalších softwarových projektů už pro něj bude jednodušší.

Analogicky musí úřad zaměstnat dostatek vývojářů k tomu, aby dokázal posoudit a zkontrolovat výstupy od dodavatelů.
Zde vývojáři dohlíží na kvalitu výstupů a kontrolují, aby dodavatelé pracovali, na čem mají.

Software sice v principu není nikdy „hotový“ – vždy bude potřeba ho měnit podle nových technologií, předpisů, regulací, zákonů a uživatelských potřeb –, ale časem přijde chvíle, kdy vám na další práci bude stačit výrazně menší počet vývojářů.
Zvlášť v tomto okamžiku je pak důležité mít několik vlastních lidí, kteří danému softwaru rozumí a budou schopni jej udržovat.

U větších projektů je potřeba vývojářský tým nasmlouvat na dobu neurčitou, pod dohledem státního vlastníka projektu.
U vodopádu by se této fázi říkalo „provoz a údržba“, ale v agilním vývoji jde o standardní mix prací: analýza uživatelských požadavků, design, vývoj softwaru, atd.[^maint]

### Kontrolní seznam

* O rozpočtu projektu rozhodují lidé se zkušenostmi v agilním zakázkovém vývoji větších softwarových systémů.
* Pokud nikoho takového nemáte, stát má pro tyto příležitosti smlouvu s vhodným dodavatelem, který může know-how přinést externě.
Tento dodavatel nesmí být ve střetu zájmů, tedy nesmí pro stát dělat nic jiného a nesmí být ve spojení s dodavateli krabicového softwaru.
* Úřad má určeného státního zaměstnance, který projekt technicky povede.
Tento zaměstnanec musí mít prokazatelné zkušenosti se zakázkovým agilním vývojem softwaru.

### Klíčové otázky

* Když dodavatel na konci každého sprintu odevzdává hotový kód, který konkrétní státní zaměstnanec má na starosti kontrolu jeho kvality?
* Pokud úřad říká, že potřebuje 10 milionů dolarů na dokončení konkrétního softwarového projektu, kdo z lidí zodpovědných za rozpočet má zkušenosti na to, aby tuto částku posoudil?
* Až bude software hotový, kdo ho bude udržovat?
Má úřad vlastní zaměstnance, kteří toho jsou schopni?
Zúčastní se procesu vývoje, aby systému rozuměli a dokázali ho podporovat?

## Minimalizujte cenu změn

Váš stát bude existovat déle než libovolný software.
Což znamená, že z vašeho krásného nového softwaru bude jednou pravděpodobně ošklivý starý a špatně použitelný software.

Sebelepší software bude časem potřeba nahradit, ať už částečně, nebo zcela.
A pokud software kupujete jako jeden velký monolit, zaručeně časem přestane plnit potřeby úřadu.

Technologie se mění – stejně jako politika, regulace, zákony a priority.
Libovolný projekt naplánovaný podrobně předem nebude schopný se těmto změnám přizpůsobit a riskuje neúspěch nebo výrazné překročení časového a finančního rozpočtu.

Místo abyste kupovali jeden velký kus proprietárního softwaru, trvejte na tom, aby váš dodavatel standardně používal open-source software a architekturu orientovanou na služby (_service-oriented architecture_, SOA).
Od samotného začátku tím snížíte náklady na aktualizaci a změny systému.

### Kontrolní seznam

* Systémy, ať už původně cloudové nebo právě do cloudu stěhované, používají architekturu orientovanou na služby (SOA), která není vázaná na konkrétní produkty nebo dodavatele.
* Data jsou v zájmu přenositelnosti uložená v otevřených, nepatentovaných formátech podporovaných více dodavateli.
* API používají otevřená schémata.
* Kdekoliv je to možné, místo komerčního softwaru se používá open-source software, který snižuje riziko závislosti na jednom dodavateli.
* Stát vlastní všechny výstupy od dodavatele.
* Pokud jsou některé komponenty systému řešené běžným krabicovým softwarem, jeho dodavatel poskytuje smluvně i technicky možnost přejít ke konkurenci a nabízí přiměřeně nákladnou možnost exportovat všechna uložená data.

### Klíčové otázky

* Jaký je váš plán snižování časových a finančních nákladů na budoucí aktualizace systému kvůli změnám technologií, politiky nebo dodavatelů?
* Kolik budou stát změny systému kvůli změnám technologií nebo politiky?
* Jsou API otevřená a použitelná jinými dodavateli?
* Jsou používané datové formáty standardizované, otevřené a použitelné jinými dodavateli?
* Udržování softwaru ve formě vyžaduje pravidelnou a průběžnou práci – máte její plán?

## Měřte pokrok na iterace, ne na milníky

Hodnota by neměla vzniknout až na konci projektu – koncoví uživatelé by ji měli začít postupně získávat nejpozději šest měsíců od uzavření smlouvy.
Už na konci prvního sprintu musí zadavatel dostat ke kontrole první fungující kód a následně se tento proces bude opakovat s každým dalším sprintem.
Koncoví uživatelé by měli kontrolovat výsledky každého sprintu bez ohledu na to, jestli došlo k nasazení nové produkční verze pro běžné použití.

Nepoměřujte pokroky projektu story pointy, počtem řádků kódu, člověkohodinami ani jinými podobnými metrikami.
Jediným opravdu smysluplným měřítkem úspěchu je hodnota dodaná koncovým uživatelům.
A tu nejlépe posoudíte tím, že si na konci každého sprintu v rámci závěrečné porady promluvíte se *scrum masterem*[^scrum] a státním vlastníkem produktu.

### Kontrolní seznam

* Dodavatelský tým používá agilní metodiku vývoje.
* Dodavatel má povinnost na konci každého sprintu nasadit novou verzi funkčního softwaru na státem vlastněnou infrastrukturu.
* Projektový tým pravidelně mluví s koncovými uživateli a konzultuje s nimi své výsledky, jednak kvůli ověření funkčnosti hotové práce, jednak kvůli plánování nové.
* Poptávkový dokument neobsahuje podrobný harmonogram prací, zmínky o Ganttově diagramu ani formální závazky typu IV&V a podobně.
* Existuje předem určená osoba, která má na starost pravidelně docházet na hodnocení sprintů a informovat vedení projektu o jeho pokrocích.

### Klíčové otázky

* Dokáže zadavatel během šesti měsíců dodat koncovým uživatelům nějakou hodnotu?
V čem přesně tato hodnota spočívá?
* Je zadavatel připravený na to, že dodavatel bude neustále průběžně mluvit s koncovými uživateli softwaru, potenciálně tedy zaměstnanci zadavatele?

## Omezte celkové výdaje

Čím je projekt dražší, tím menší má šanci uspět.
Obecně řečeno byste za celý projekt neměli utratit více než 10 milionů dolarů.[^standish1] \(Vzácnými výjimkami z tohoto pravidla jsou extrémně složité projekty jako například pojištění nezaměstnanosti nebo systémy týkající se programu Medicaid.)

### Kontrolní seznam

* Zadavatel chápe, že nedostává zlomek potřebných peněz – dostává úplně nový proces vývoje softwaru a k němu adekvátní systém financování.

### Klíčové otázky

* Pokud projekt „vyžaduje“ 20 milionů dolarů, kolik hodnoty lze uživatelům dodat za polovinu nebo desetinu této částky? (Pokud „žádnou“, projekt je ztracený.)
* Pokud vlastní náklady doplní dotace shora, zvlášť v nějakém výhodném poměru (například 9:1 v programech Medicaid), bude mít někdo problémy, když projekt nevyčerpá všechny dostupné peníze?
* Je mezi účastníky projektu někdo, jehož odměny se odvíjí od proinvestovaných prostředků a má tedy motivaci utratit sto milionů tam, kde by deset stačilo?

## Omezte velikost zakázek

Dlouhodobá spolupráce s jedním dodavatelem nebo využití většího počtu týmů od jednoho dodavatele zní lákavě, ale nevyhnutelně vede k závislosti na tomto dodavateli.
Rozdělením projektů na menší zakázky motivujete dodavatele k vývoji udržitelnějšího softwarového ekosystému namísto monolitu, a navíc mají menší zakázky znatelně větší šanci na úspěch.[^standish2]

Vyžadujte, aby žádná jednotlivá zakázka nestála ročně víc než dva miliony dolarů a žádná smlouva netrvala déle než tři roky.
Tím pádem nedostanete od jednoho dodavatele víc než dva vývojářské týmy – pokud jich projekt vyžaduje víc, sežeňte je u jiného dodavatele a nechte je pracovat samostatně.
Omezte také délku poptávkového dokumentu, neměli byste do něj investovat víc než 60 dní a neměl by zabrat víc než 20 stránek.

Kromě ochrany před závislostí na jednom dodavateli mají menší zakázky ještě jednu výhodu: mají menší pravděpodobnost, že je někdo napadne, protože při jejich pořizovací hodnotě se nevyplatí do nich investovat úsilí a právníky.
Pokud k dodavatelům přistupujete otevřeně a s respektem a nevyžadujete po nich stovky stránek nabídkové dokumentace, je větší šance, že s vámi budou chtít spolupracovat i do budoucna.

S rostoucím počtem lidí na projektu roste objem času, který jim zabere vzájemná koordinace. Řešením je pracovat souběžně, bez větší koordinace, což se dá zařídit stavěním systému z volně provázaných komponent.
Pokud na vašem projektu pracují týmy od více než jednoho dodavatele, máte také o něco lepší možnosti, když bude potřeba některého z dodavatelů vyměnit.

### Kontrolní seznam

* Pokud bude projekt vyžadovat větší počet zakázek, došlo k analýze rozsahu první z nich a máte aspoň hrubou představu, co budou obsahovat ty ostatní.
* Pokud bude na projektu pracovat více než jeden vývojářský tým, systém využije architekturu orientovanou na služby (SOA).
* Pokud je to možné, projekt je rozdělen na podlimitní zakázky nebo zakázky malého rozsahu, které mají rychlejší a jednodušší administrativu.
* První identifikovaný projekt má relativně nízkou technickou složitost, nízké politické riziko a vysokou hodnotu pro koncové uživatele, takže na něm týmy mohou vyzkoušet nový styl práce, experimentovat a učit se v prostředí s relativně nízkým rizikem.

### Klíčové otázky

* Přečetla si osoba zodpovědná za zadávání zakázek tohoto průvodce?
* Chápe dotyčná osoba, že po ní nikdo nechce udělat veškerou práci na zakázce za 50 milionů dolarů?
Chápe, že dvoumilionové zakázky je mnohem jednodušší zpracovat a agilně bude též jednodušší je uřídit?

## Plaťte za ekosystém, ne za monolity

Dávejte si pozor, abyste jeden zastaralý systém nenahradili jiným zastaralým systémem.
Trvejte na systému volně provázaných komponent, které se dají postavit postupně.
Výsledný systém pak v budoucnu nebudete muset nahrazovat jednorázově, ale bude možné postupně obměňovat zastarávající komponenty podle potřeby.

### Kontrolní seznam

* Každá zakázka musí přinést nějakou hodnotu koncovým uživatelům – nemůže jít jen o „údržbu serverů“ nebo „nastavení databáze“, ale třeba o „webovou aplikaci pro správu oprávnění“ nebo „zjednodušení náborového procesu“.
* Neexistuje jediný „enterprise architekt“, architektura se objeví postupně během agilního vývoje.
* Pokud je projekt dost velký na to, aby na něm pracovalo několik agilních týmů zároveň, nikdo neočekává, že všichni členové všech týmů budou chodit na společné porady.
* Poptávkový dokument předepisuje použití architektury orientované na služby.

### Klíčové otázky

* Existuje nějaké slabé místo, jehož vyřazením by došlo k výpadku celého systému?
Pokud ano, systém je spíš monolit než síť služeb.
* Pokud potřebujete vyřadit jednoho dodavatele kvůli nízké kvalitě výstupů, mohou ostatní pracovat bez přerušení?

## Rozšiřte okruh svých dodavatelů

Vaši stávající dodavatelé se nejspíš do moderního stylu vývoje softwaru popisovaného v tomto textu dvakrát nepohrnou – začali jste s nimi kdysi spolupracovat právě pro styl práce, kterého se teď chcete zbavit.
Bude potřeba najít a přilákat nové firmy, které používají moderní metodiky vývoje.

Menší, kvalifikovaný agilní tým velmi pravděpodobně najdete i ve svém státě, pokud je to pro vás priorita.[^alaska]
Pokud ale chcete snížit náklady, je důležité zvážit i spolupráci se vzdálenými a distribuovanými dodavatelskými týmy.

Se státech jako Kalifornie, Washington, New York, Virginie nebo Maryland může agilní tým snadno stát dvakrát tolik co tentýž tým na středozápadě nebo severu Ameriky.
To je rozdíl milionu dolarů ročně, bez dopadu na kvalitu.
Vyplatí se tedy zvážit, jak moc stojíte o místní tým, případně tým ze svého státu.[^locals]
Podporou distribuovaných týmů získáte kromě jiného přístup k mnohem větší zásobárně talentu, takže se vyplatí do distribuované spolupráce investovat[^remote] a návštěvy na místě vyžadovat jen v případě potřeby, například kvůli kontaktu vývojářů s koncovými uživateli.

A jak ony malé kvalifikované týmy najít? Řada měst a států má přímo seznamy vhodných agilních dodavatelů, viz například pravidelně aktualizovaný [seznam kalifornského ministerstva informatiky](https://github.com/CDTProcurement/adpq).
Zkuste některé z těchto dodavatelů oslovit v budoucích poptávkách.
Poptejte se také mezi svými kolegy z jiných státních úřadů, jestli by vám vhodného dodavatele nedoporučili.
Anebo se zkuste vžít do role softwarového vývojáře, co hledá práci, a projděte si známé weby s nabídkami pracovních příležitostí a networkingu – velmi pravděpodobně na nějakého agilního dodavatele ze svého státu narazíte.
Celý proces nemusí trvat déle než pár hodin.

Častou praxí je dávat přednost dodavatelům, kteří už poptávaný systém jednou postavili.
Vůbec to není nutné, jen si tím omezujete výběr na několik velkých mezinárodních firem.
Lepší je rozšířit záběr na společnosti, které úspěšně dodaly nějaký analogický systém – pokud někdo například vyrobil rezervační web pro půjčovnu aut, jistě by uměl udělat například web pro turistické povolenky, a hlavní vývojář databáze pro sledování komet by jistě uměl udělat databázi pro sledování polohy státních vozidel.
Hledáním relevantních zkušeností po této ose jistě najdete řadu vhodných dodavatelů, kteří by vaši zakázku zvládli.

### Kontrolní seznam

* Poptávkový dokument je stručný (maximálně 20 stránek) a srozumitelný i pro vývojáře, kteří pro stát běžně nepracují.
* Akviziční plán počítá s aktivním oslovením malých dodavatelů.
* Poptávkový dokument není na webu zamčený za registračním formulářem, ale je volně k dispozici, aby ho komunita dodavatelů mohla snadno sdílet.
* Poptávkový dokument od dodavatele vyžaduje, aby ve své nabídce uvedl klíčové odpovědné osoby (nejvýše tři), například hlavního vývojáře nebo hlavního designéra.
* Akviziční plán počítá s tím, že si s několika nejslibnějšími dodavateli osobně promluvíte, a to nikoliv s jejich obchodními zástupci, ale s klíčovými vývojáři.
* Zaměstnanci dodavatele nejsou nuceni pracovat na místě u zadavatele.
* Dodavatelské týmy a státní vlastník produktu mají svolení používat videohovory, chat, veřejný verzovací systém a [jiné nástroje běžně používané agilními týmy](https://media.defense.gov/2018/Oct/09/2002049591/-1/-1/0/DIB_DETECTING_AGILE_BS_2018.10.05.PDF#page=3), viz například [seznam nástrojů pro vzdálené zaměstnance GSA](https://www.gsa.gov/reference/for-gsa-employees/on-the-go).

### Klíčové otázky

* Plynou vám nějaké výhody – politické či jiné – z toho, že zakázku zadáte v rámci státu?
Nebo tuto podmínku máte přímo jako součást zadání?
Pokud ano, může vás to omezit při hledání vhodného dodavatele?
* Stojí vám úspora jednoho milionu dolarů na každý agilní tým za to, abyste překonali námitky proti vzdáleným týmům?
* Udělali jste si aspoň letmý průzkum trhu, abyste věděli, jaké dodavatele oslovit svým poptávkovým dokumentem – anebo pouze naslepo poptáváte a doufáte?

## Podělte se o svůj software s ostatními

Hotový software – ať už jako celek, nebo některou svou komponentou – by pravděpodobně mohl být užitečný pro jiné státní úřady.
V mnoha státech navíc platí legislativa, [díky které je software vytvořený státem automaticky veřejným dílem](http://copyright.lib.harvard.edu/states/).

Otevřeně vyvíjený software lépe motivuje zaměstnance dodavatele – nabízí jim dobrou referenci do portfolia pro budoucí zaměstnavatele, případně i jen možnost pochlubit se kamarádům.
Motivovaný dodavatel pro vás odvede lepší práci.
A při zadávání budoucích zakázek se můžete odkázat na volně dostupný kód, takže zájemci uvidí, na čem přesně nebo proti jakému API by pracovali.

### Kontrolní seznam

* Poptávkový dokument požaduje, aby byl zdrojový kód od prvního okamžiku vyvíjen veřejně na nějaké sociální platformě pro vývojáře, například [GitHubu](http://github.com/) nebo [GitLabu](https://gitlab.com/).
* Poptávkový dokument vyžaduje, aby byl zdrojový kód jasně označen jako veřejné dílo nebo uvolněn pod nějakou [open-source licencí](https://opensource.org/licenses).
* Poptávkový dokument vyžaduje dodržování pravidel bezpečnosti, zejména tedy důsledné oddělení softwaru od dat a konfigurace (například přístupových hesel), což by mělo být ověřeno automatickými testy.
* Poptávkový dokument vyžaduje dostatečnou dokumentaci, aby projekt dokázal spustit i vývojář, který na něm nepracuje.

### Klíčové otázky

* Nebude vám někdo – například osoba zodpovědná za bezpečnost projektu – dělat problémy kvůli zveřejňování kódu pod open-source licencí?
* Víte o nějakých jiných státních úřadech nebo organizacích, které by z vašeho softwaru mohly profitovat?
Můžete s nimi zadání a vývoj projektu konzultovat?

## Berte software jako provozní výdaj

Zakázkový software, na rozdíl od mostů nebo jiných kapitálových infrastrukturních projektů, není nikdy „hotový“, takže je potřeba počítat s jeho průběžnými úpravami.
Jen tak můžete naplnit dnešní potřeby uživatelů, nikoliv ty včerejší.

U malých systémů to znamená přidat k vašemu vývojářskému týmu řekněme do jednoho úvazku navíc.
U velkých, klíčových systémů to může znamenat celý dodatečný tým, který se bude starat o údržbu a rozvoj.

Na údržbu softwaru se z hlediska rozpočtu obvykle hledí úplně jinak než na samotný vývoj, což je chyba.
Udržovat software znamená jednoduše pokračovat v jeho úpravách podle potřeb uživatelů, které se mění podle zákonů, regulací, politik, doporučených praxí nebo nových technologií.
Jsou k tomu potřeba tytéž dovednosti, metody a úkoly, jaké byly potřeba během vývoje.
Takže pokud vám někdo navrhuje převést projekt do nějaké speciální fáze provozu a údržby (_operations and maintenance_, O&M), mělo by se vám v hlavě rozsvítit červené světlo.

Obecně řečeno vás agilní tým 5–9 vývojářů bude stát 1–2 miliony dolarů ročně v závislosti na tom, odkud přesně je.
Financování se dá postupně navýšit během několika rozpočtových cyklů podle toho, jak se vám bude dařit úspěšně snižovat rizika, kontrolovat výdaje a dodávat iterativně hodnotu koncovým uživatelům.

Ve výsledku tím můžete získat předvídatelný zdroj financování softwarových projektů a nahradit jím nepředvídatelné kapitálové výdaje.
A váš zřizovatel na oplátku získá předvídatelné roční náklady na všechny vaše softwarové projekty.

### Kontrolní seznam

* Zadavatel si uvědomuje, že software je nutné zlepšovat průběžně po celou dobu jeho existence, protože „údržba“ se kvalitativně nijak neliší od vývoje.
* Zadavatel poptává agilní vývojářské služby.
* Zeptali jste se zadavatele, jestli by nechtěl finance na projekt dostávat průběžně v rámci provozního rozpočtu, namísto jedné velké sumy.
* Tento režim financování byl konzultován se všemi potřebnými nadřízenými organizacemi.
* Pokud je projekt vysoce rizikový, dostane v prvním roce pouze několik málo milionů dolarů a financování se bude navyšovat až podle hodnoty dodané uživatelům.

### Klíčové otázky

* Budou vyžádané prostředky utraceny během jednoho rozpočtovacího období?
* Pokud zadavatel žádá 50 milionů dolarů, kolik hodnoty lze koncovým uživatelům dodat za dva miliony, další dva miliony, a tak dále?
* Pokud je projekt financovaný federálními dolary, je federální agentura ochotná vzít v úvahu provozní model financování?

## Ptejte se dodavatele na technické věci

Když úřad poptává rozpočet na zakázkový vývoj softwaru, často dochází k tomu, že spolu o technických věcech mluví dvě skupiny netechnických lidí.
V takové situaci pochopitelně jen zřídka padnou klíčové otázky jako například ty, které jsou uvedené v tomto textu.
Všechny podobné technické otázky ale padnout musí – a musí na ně padnout i správné odpovědi. (Ukázkové otázky a odpovědi najdete v dodatku A.)

Přidělení peněz na projekt, který je předem odsouzen k nezdaru, nikomu neprospěje.
A pokud zadavatel přesně neví, co chce, velmi pravděpodobně to také nedostane.

### Kontrolní seznam

* Úřad postupuje podle návodu [Digital Services Playbook](https://playbook.cio.gov).
* Pokud má být výstupem projektu web, úřad dodavatele odkáže na [oficiální webový design systém Spojených států](https://designsystem.digital.gov/).
* Úřad postupuje podle [Deseti přikázání softwaru](https://media.defense.gov/2018/Apr/22/2001906836/-1/-1/0/DEFENSEINNOVATIONBOARD_TEN_COMMANDMENTS_OF_SOFTWARE_2018.04.20.PDF).
* Úřad si prostudoval tento text.
* Úřad prošel [testem rádobyagilního vývoje](https://media.defense.gov/2018/Oct/09/2002049591/-1/-1/0/DIB_DETECTING_AGILE_BS_2018.10.05.PDF).

### Klíčové otázky

* Co přesně chce úřad koupit?
Proč?
Kdo z toho bude mít užitek?
* Které části systému budou psané na míru?
Které budou řešené běžným, nepřizpůsobeným krabicovým softwarem?
Kolik budou stát aktualizace tohoto softwaru?
Co se stane, když dodavatel nějaké komerční komponenty, například databázového systému, skončí s podnikáním?
* Kdo jsou koncoví uživatelé vašeho systému?
Mluvili jste s nimi?
Co chtějí?
* Jste připraveni reagovat na změny?
* Kolik bude stát přechod na nový systém?
* Co děláte pro to, abyste se v budoucnosti vyhnuli nákladným požadavkům na změny?

[^healthcare]: Viz případové studie [Case Study of CMS Management of the Federal Marketplace](https://oig.hhs.gov/oei/reports/oei-06-14-00350.asp) (americké ministerstvo zdravotnictví) a [The Spectacular Fall and Fix of HealthCare.gov](https://hbswk.hbs.edu/item/the-spectacular-fall-and-fix-of-healthcare-gov) (Harvard Business School).

[^qasp]: Jako příklad poptávkového dokumentu nabízíme [tuto poptávku amerického daňového soudu](https://github.com/ustaxcourt/case-management-rfq), která v sekci Deliverables and Performance Standards obsahuje i plán posuzování kvality.

[^maint]: Další informace o rozdílném přístupu agilního vývoje k provozu a údržbě systémů najdete například v článku [Software maintenance is an anti-pattern](https://18f.gsa.gov/2016/02/23/software-maintenance-is-an-anti-pattern/) na blogu 18F.

[^scrum]: Scrum je jedna z konkrétních verzí agilního vývoje.
Přebírá jeho základní charakteristiky (iterativní vývoj a pragmatický přístup k procesům) a přidává k nim několik jasně definovaných definic, procesů a rolí, z nichž jednou je právě zmíněný scrum master – člověk, který má stručně řečeno za úkol odstraňovat procesní překážky bránící týmu v efektivní práci. (pozn.
překl.)

[^standish1]: Společnost Standish Group ve svém CHAOS Reportu z roku 2014 na vzorku 25 tisíc softwarových projektů zjistila, že software dražší než 10 milionů dolarů uspěje [pouze v osmi procentech případů](https://www.standishgroup.com/sample_research_files/CHAOSReport2014.pdf#page=3).
S klesajícími náklady jde úspěšnost projektů rychle nahoru, kolem hranice jednoho milionu dolarů už se pohybuje kolem 70 %.

[^standish2]: Společnost Standish Group ve svém CHAOS Reportu z roku 2014 na vzorku 25 tisíc softwarových projektů zjistila, že [čím je softwarový projekt dražší, tím menší má šanci uspět](https://www.standishgroup.com/sample_research_files/CHAOSReport2014.pdf#page=3).
Omezením rozsahu jednotlivých zakázek rozdělíte projekt na větší počet menších komponent, které mají jednotlivě větší šanci uspět – a s nimi pak i projekt jako celek.

[^alaska]: Aljašské ministerstvo zdravotnictví a sociálních věcí se s hledáním vhodných dodavatelů potýkalo v roce 2017.
O tom, jak se jim nakonec podařilo přitáhnout malého místního agilního dodavatele, si můžete přečíst v článku [How Alaska is using transparency to attract modern software vendors](https://18f.gsa.gov/2017/09/12/how-alaska-is-using-transparency/).

[^locals]: Úřad pracovních statistik nabízí [přehled mezd softwarových vývojářů podle státu](https://www.bls.gov/oes/current/oes151132.htm#IDX701), podle kterého je mezi nejdražším státem (Washington) a nejlevnějším státem (Portoriko) rozdíl 150 %.
I v rámci jednotlivých států se náklady mohou zásadně lišit, například mezi městem a venkovem.
Takže trváním na práci dodavatele v místě zakázky můžete snadno zdvojnásobit své náklady.

[^remote]: Podrobný návod na distribuovanou spolupráci viz [18F’s best practices for making distributed teams work](https://18f.gsa.gov/2015/10/15/best-practices-for-distributed-teams/).

