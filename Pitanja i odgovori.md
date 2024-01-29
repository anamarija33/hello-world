1. Koja je namjena mrežnih tehnologija ?
		Namjena mrežnih tehnologija je :
		- **prijenos podataka** - omogućavaju brz i učinkovit prijenos podataka između različitih računala i uređaja (dijeljenje datoteka, streaming medija..)
		- **komunikacija** - omogućavaju razne oblike komunikacija putem različitih usluga (epošta, chat, video konferencije ..)
		- **dijeljenje resursa** - mreže omogućavaju zajedničko korištenje resursa (printer, datoteka, aplikacija, zajednička suradnja)
		- **povezivanje uređaja u internet stvari - IoT** - povezuju različite uređaje iz područja IoT
	

2. Što je komunikacija i objasnite ukratko koji su bitni elementi komunikacije ?

Komunikacija je proces razmjene informacija (podataka) između jednog ili više sudionika, taj proces uključuje slanje i primanje poruka putem različitih kanala te razumijevanje poruka.
Bitni elementi komunikacije su :izvor ( pošiljatelj ), poruka, medij kojim se poruka prenosi, primatelj, povratna informacija, kontekst, šum i proces kodiranja i dekodiranja.

![[Pasted image 20240105204812.png]]
3. Na vlastitom primjeru navedite i objasnite elemente komunikacije.

Šaljem (pošiljatelj) poruku nekoj osobi(primatelj) preko telegrama (medij kojim se poruka prenosi), ta poruka se potom kodira, dođe do primatelja, potom se poruka dekodira kako bi ju primatelj razumio. Ako ju je primatelj razumio, šalje povratnu poruku(povratna informacija).

4. Detaljno objasnite što je računalna mreža.

Računalna mreža je skupina računala povezanih određenim medijem, omogućujući im komunikaciju i suradnju, neovisno o njihovoj geografskoj udaljenosti. Ove mreže omogućuju brz i učinkovit prijenos informacija , podataka i resursa između povezanih računala, te podržavaju različite oblike komunikacije. Računalne mreže koriste različite medije za povezivanje: žičane (ethernet kabeli), bežične (signali poput WiFi-a) i optičke (optičke veze koje koriste svjetlosne signale) tehnologije. 
Cilj računalnih mreža je osiguravanje stabilnog i pouzdanog funkcioniranja računalnih mreža, to uključuje poboljšanje komunikacije, optimizaciju dijeljenja resursa, povećanje dostupnosti informacija te podršku različitim aplikacijama i uslugama koje korisnici mogu koristiti unutar mreže.

5. Navedite topologije mreže i opišite prednosti i nedostatke topologije po vlastitom izboru.

Topologije mreže koje postoje su : sabirnica, prsten, zvijezda, mreža(mesh) i hijerarhijska.
Prednosti i nedodstatci topologija: 
- sabirnica : prednosti : jednostavna je - svi čvorovi dijele jedan zajednički komunikacijski kanal i podaci se šalju svim čvorovima, a svaki čvor odlučuje hoće li prihvatiti ili ignorirati poruku. Nedostatci : ograničenja u brzini i količini podataka koja se mogu prenijeti, kad nastupi prekid u jednoj točki, cijela mreža prestaje funkcionirati.
- prsten : prednosti : jednostavna, efikasnija od sabirnice pri prijenosu veće količine podataka,  jednostavan popravak mreže. Nedostatci : jedan neispravan čvor može stvoriti probleme za cijelu mrežu, dodavanje ili mijenjanje čvorova može utjecati na rad mreže.
- zvijezda: prednosti : svi podaci prolaze kroz centralni čvor, to olakšava upravaljanje i otklanjanje kvarova, ako je jedan čvor neispravan, on ne utječe na ostatak mreže, dodavanje i uklanjanje čvorova ne utječe na ostatak mreže. Nedostatci : ako centralni čvor ne funkcionira, čvorovi gube povezanost, 

6. Na koji način možemo klasificirati računalne mreže?

Klasifikaciju računalne mreže možemo vršiti prema: 
- namjeni (privatne i javne mreže)
- funkcionalnosti (klijent - server; peer-to-peer (P2P) mreže)
- vrsti veza (žičane, bežične)
- veličini (LAN, WAN)
- geografskoj pokrivenosti (PAN, CAN, MAN, WAN)

7. Objasnite računalne mreže prema namjeni.

Računalne mreže prema namjeni mogu biti **privatne** ili **javne**.
**Privatne računalne mreže** su ograničene na određenu organizaciju, tvrtku ili skupinu korisnika, obično su postavljene za internu uporabu i omogućuju razmjenu informacija između uređaja unutar te organizacije. 
**Javne računalne mreže** su otvorene za opću uporabu i omogućuju povezivanje različitih organizacija i pojedinaca diljem svijeta. (najpoznatiji  pr. - internet)

8. Objasnite računalne mreže prema funkcionalnosti.

Računalne mreže prema funkcionalnosti mogu biti klijent-server ili p2p.
**P2P - peer-to-peer računalna mreža** - predstavlja sustav u kojem računala i uređaji međusobno surađuju, dijeleći resurse i podatke direktno između sebe, bez centralnog poslužitelja. Svaki čvor ima jednaku ulogu i može djelovati kao izvor ili primatelj podataka. P2P mreža je otporna na kvarove, skalabilna je i jednostavno ju je implementirati. 
Primjeri - streaming, VOIP telefonski pozivi i video konferencije

**Klijent-server arhitektura mreže** - temelji se na modelu suradnje između klijenata (korisničkih računala) i servera (centralnih računala ili poslužitelja) koji pruža resurse, usluge ili podatke korisnicima.
Klijenti iniciraju zahtjeve prema serveru, server je odgovoran za obradu i odgovaranje na zahtjeve klijenta.
Primjeri - web preglednik, baze podataka

9. Objasnite računalne mreže prema veličini.

Računalne mreže prema veličini mogu biti LAN i MAN.
LAN (Local Area Network)  je mala geografski ograničena mreža koja povezuje računala i uređaje unutar iste zgrade, kampusa ili lokalne okoline. Ima visoku brzinu prijenosa podataka, nisku latenciju i visoku sigurnost.
WAN (Wide Area Network) obuhvaća veće geografske udaljenosti i povezuje LAN-ove na različitim lokacijama koristeći usluge ISP-ova. Ima nižu brzinu od LAN-a, veću latenciju ali omogućuje globalnu povezanost. (najpoznatiji primjer- Internet)

10. Objasnite klijent - server arhitekturu.

Klijent - server arhitektura temelji se na modelu suradnje između klijenata(korisničkih računala) i servera (centralnih računala ili poslužitelja) koji pruža resurse, usluge ili podatke korisnicima. 
Server je računalo na kojem se čuvaju podaci, zadatak sservera je dati na korištenje resurse, usluge ili podatke, brine o sigurnosti, te nadzire rad svih klijenata.
Klijent je računalo koje omogućuje pristupanje podacima i uslugama koje pruža server. Klijenti mogu i međusobno razmjenjivati podatke posredstvom poslužitelja.

11. Objasnite P2P arhitekturu.

Peer to Peer (P2P) predstavlja sustav u kojem računala i uređaji međusobno surađuju, dijeleći resurse i podatke direktno između sebe, bez centralnog poslužitelja. Svaki čvor ima svoju ulogu i može djelovati kao izvor ili primatelj podataka.

12. Kakve mogu biti mreže s obzirom na geografsku pokrivenost i ukratko ih objasnite ?

Mreže mogu biti PAN (Personal Area Network), LAN (Local Area Network), MAN (Metropolitan Area Network), WAN (Wide Area Network) s obzirom na geografsku pokrivenost.
PAN - mreža računala unutar jedne stambene jedinice, služi za međusobno spajanje manjeg broja računala ili računala i periferije, uključuje spajanje uređaja putem Bluetooth tehnologije
LAN - mreža koja žičano spaja manje računalne mreže na nmanjem geografskom području (unutar zgrade, organizacije, kampusa..)  ( WLAN - bežični LAN- potreban barem jedan Access point i jedno bežično mrežno sučelje)
MAN - mreža koja pokriva jedan grad ili veliko urbano područje
WAN - mreža koja međusobno spaja LAN računalne mreže na širokom geografskom području

13. Što je VPN i ukratko objasnite ?

VPN (Virtual Private Network) je tehnologija koja omogućuje sigurno povezivanje između udaljenih računala ili mreža putem javne internetske infrastrukture. VPN stvara "virtualni tunel" za siguran prijenos podataka, on stvara enkripciju kako bi se osiguralo da se podaci preneseni preko interneta ne mogu lako čitati ili prepoznati od neovlaštenih osoba.

14. Koji su osnovni elementi stvaranja računalne mreže i ukratko ih objasnite?

Potrebna su 3 osnovna elementa za stvaranje računalne mreže: 
- prijenosni medij - medij koji se koristi za povezivanje više mrežnih uređaja u jednu cjelinu i putem kojega se prenose podaci (koaksijalni kabel, mrežni (ethernet) kabel, optički kabel, bluetooth, Wi-Fi, mobilna mreža)
- mrežno sučelje (mrežna kartica) - spaja mrežne uređaje (host) s prijenosnim medijem
- protokoli - opisuju način na koji se podaci prenose pomoću mrežnog sučelja i prijenosnih medija.

15. Koji su prijenosni mediji za povezivanje mrežnih uređaja u cjelinu, te ih ukratko objasnite ?

Prijenosni mediji za povezivanje mrežnih uređaja u cjelinu su žičani medij (UTP - unshielded twisted pair, neoklopljena upletena parica) , optička vlakna (svjetlovod- tanka staklena ili plastična nit sa svojstvom vođenja svjetla) ili radio valovi. 

16. Koja je uloga mrežne kartice ?

Mrežna kartica je fizički instalirana u računalo, ona komunicira sa operativnim sustavom računala preko upravljačkih programa (drivers). Povezana je s mrežnom infrastrukturom putem kabela ili bežične veze. Računalo (operativni sustav) koristi mrežnu karticu za paketnu komunikaciju za primanje ili slanje podatka unutar mreže. Mrežna kartica prima podatke iz mreže i predaje predaje ih operativnom sustavu računala, te odašilje podatke prema odgovarajućoj mrežnoj adresi (MAC). Također upravlja kolizijama.

17. Što je MAC adresa ?

MAC (Media Access Control) adresa je jedinstvena identifikacija mrežne kartice, koristi se za identifikaciju uređaja u mreži. Sa MAC adresom se radi unutar LAN mreža.

18. Što je protokol ?

Protokol je set pravila za formatiranje i procesiranje podataka, oni utvrđuju postupke uspostavljanja, održavanja i prekida veze. 

19. Objasnite ulogu Internet Protocol (IP).

IP adresira i omogućuje usmjeravanje paketa između različitih mreža kako bi stigli do odredišta. Dijeli pakete na manje dijelove koji se prenose i zatim ponovno sastavljaju na odredištu. IP zaglavlje sadrži informacije potrebne za usmjeravanje paketa, uključujući izvor i odredište IP adrese, verziju IP protokola, vrijeme života i kontrolne informacije.

20. Što je IP adresa i koje vrste postoje ?

Svaki uređaj dobiva jedinstvenu 32 (IPv4) ili 128 (IPv6) bitnu IP adresu koja se koristi u komunikaciji s tim uređajem. Adresa kodira identifikaciju mreže na koju je uređaj povezan kao i identifikaciju uređaja na toj mreži.

21. Usporedite IPv4 i IPv6.

IPv4 adresa je 32 bitna, oblik adrese je 4 grupe po 3 znamenke (0-9) odvojene točkom. Broj adresa je 2³²
IPv6 adresa je 128 bitna, oblik adrese je 8 grupa po 4 heksidecimalnih znaka odvojena : .
Broj adresa je 2¹²⁸ . IPv6 je osmišljen zbog nedostatka IPv4 adresa.


22. Objasnite lokalne IP adrese.

Lokalne IP adrese se koriste za povezivanje računala unutar LAN mreža, ovim adresama nije moguće pristupiti izvan lokalne računalne mreže. Koriste se 192.168.0.0 - 192.168.255.255


23. Objasnite razliku između statičke i dinamičke IP adrese.

Statičke IP adrese se rijetko ili nikada ne mijenjju (IP adrese web poslužitelja)
Dinamičke IP adrese se mijenjaju barem jednom unutar 24h (pružatelji usluga pristupa Internetu)

24. Koja je uloga DNS ?

Domain Name system (DNS) je domenski nazivni sustav koji se koristi kako bi se pristupilo internetskim sadržajima. U njemu se nalaze informacije o IP adresama i imenima računala. Korištenjem DNS-a internetskim sadržajima se pristupa putem naziva domena umjesto upisivanjem IP adrese.

25. Objasnite ulogu Transmission Control Protocol (TCP).

Transmission Control Protocol (TCP) je komunikacijski kanal između pošiljatelja i primatelja, garantira pouzdanu isporuku podataka od izvorišta do odredišta u kontroliranom redosljedu. 

Komunikacija putem TCP-a počinje uspostavom veze između dva računala, podaci  se dijele na segmente manje veličine, svaki segment ima redni broj koji omogućava pravilan redoslijed prilikom rekonstrukcije podataka na odredištu. TCP koristi mehanizme za osiguravanje pouzdane isporuke podataka, prilagođava brzinu slanja podataka kako bi spriječio preopterećenje mreže i gubitak podataka.

26. Objasnite 4-slojni mrežni model i za svaki sloj definirajte protokole.

Mrežni model korišten u TCP/IP grupi protokola je 4-slojni model koji se sastoji od: 
- Aplikacijskog sloja (HTTP, FTP, POP3, SMTP, SNMP, DNS, IMAP, NTP, SOCKS, SSH, DHCP)- sadrži komunikacijske tehnologije koje se koriste za međusobna spajanja i potrebe pojedinih aplikacija 
- Transportni sloj (TCP, UDP)- sadrži komunikacijske tehnologije koje se koriste za komunikaciju između računala koje se nalaze na različitim lokalnim mrežama
- Mrežni sloj (IP, ICMP)- sadrži komunikacijske tehnologije koje se koriste za međusobna spajanja lokalnih računalnih mreža
- Sloj podatkovne veze (Ethernet, PPP(point to point protocol),L2TP (Layer 2 tunneling protocol), ARP) - sadrži komunikacijske tehnologije koje se koriste za potrebe spajanja pojedinih uređaja u lokalnim računalnim mrežama

27. Objasnite ulogu UDP protokola.

UDP (User Datagram Protocol) je protokol koji pruža brz i jednostavan prijenos podataka, ali bez garancije pouzdanosti ili redoslijeda. (računalne igre, streaming, voip)

28. Što je OSI referentni model i objasnite njegove razine (slojeve) ?

OSI referentni model (Open Systems interconnection basic reference model) je apstraktni slojeviti model koji služi kao preporuka stručnjacima za razvoj računalnih mreža i protokola.
Podjeljen je na 7 slojeva, svaki sloj opisuje skup povezanih funkcija koje omogućuju jedan dio računalne komunikacije, zajedno prikazuju tok podataka od izvora prema odredištu.
- Aplikacijski sloj pruža mrežne usluge aplikacijama i upućuje zahtjev uslugama prezentacijskog sloja.
- Prezentacijski sloj omogućuje da su podaci čitljivi na odredištu, brine o formatu i strukturi podataka i pregovara o sintaksi prijenosa za aplikacijski sloj
- Sesijski sloj uspostavlja, upravlja i prekida veze između aplikacija
- Transportni sloj zadužen za pouzdan prijenos podataka između uređaja. Otkriva i ispravlja greške u prijenosu, uspostavlja, održava i prekida virtualne krugove.
- Mrežni sloj pruža usluge povezanosti i odabire najbolje putanje za paket podataka. Podaci do odredišta mogu putovati različitim putanjama.
- Data Link sloj omogućuje pouzdan prijenos podataka preko medija. Brine se o pristupu mediju za prijenos podataka. Zadužen je za povezanost i odabir putanje između uređaja.
- Fizički sloj brine se o fizičkim komponentama mreže: medijima za prijenos, konektorima, razinama napona i signala, brzinama prijenosa podataka
![The OSI Model](https://cloudflare.com/img/learning/ddos/what-is-a-ddos-attack/osi-model-7-layers.svg)
29. Što je paket u prijenosu podataka i kako se odvija paketni prijenos?

Podaci koje je potrebno prenijeti se razdvajaju na pakete, tada se prenose tehnologijom paketnog prijenosa. Paketni prijenos se odvija na način da se paketima podataka dodaju se zaglavlja i metapodaci. Paketi imaju IP adresu pošiljatelja i primatelja, svaki paket se šalje drugim putem, put paketa određuju usmjerivači. Svaki paket sadrži redni broj i broj ukupno poslanih paketa kako bi se mogli sastaviti u cjelinu.

30. Što je podatkovno omotavanje (data encapsulation) ?

Podatkovno omotavanje je kada se paketima podataka dodavaju informacije koje omogućavaju ispravan prijenos i obradu tih paketa, dodaju se zaglavlja i metapodaci.

31. Kako se odvija pakiranje podataka s obzirom na slojeve u OSI modelu ?

Podatke koji su zaprimljeni sa aplikacijskog sloja u transportni sloj se podijele u manje dijelove, pridodaje se TCP zaglavlje (TCP izvorni port, TCP odredišni port, polje TCP zastavica) te tijelo TCP (stvarni podaci koji se prenose)
Segmenti zaprimljeni sa transportnog sloja u mrežni sloj su procesirani sa paketima, ovaj sloj sadrži IP zaglavlje (IP izvornu adresu, odredišnu IP adresu, vrstu IP protokola, polje IP opcija ( IP izvorna ruta i IP sigurnosne opcije)), ovdje se može provesti fragmentacija ako je potrebno.
Paketi sa mrežnog sloja procesiraju se u okvire, ono sadrži ethernet zaglavlje (MAC adresa) i ethernet tijelo.
Fizički sloj su bitovi koji se prenose mrežom

32.  Koja je uloga preklopnika (switcha) ?

Uloga preklopnika je da zaprimljene pakete podataka prosljeđuje isključivo mrežnim uređajima kojima su oni namijenjeni, to radi pomoću MAC adrese mrežnih uređaja.

33. Koja je uloga usmjerenika (routera) ?

Uloga usmjernika je da poveže računalne mreže koje koriste različite mrežne protokole ( npr LAN i WAN ). Koristi network address translation ( NAT ) uz IP adrese kako bi više uređaja spojenih u LAN moglo pristupati internetu koristeći samo jednu IP adresu.

34. Objasnite što je Internet ?

Internet je globalni sustav ogromnog broja raznih računalnih mreža (privatnih, javnih, akademskih, poslovnih), povezanih žičanim, optičkim ili bežičnim tehnologijama. Koristi se za komunikaciju, razmjenu informacija, obrazovanje, trgovinu... Koristi standardni skup internetskih protokola(TCP/IP) kako bi se omogućila komunikacija između različitih uređaja. 

35. Usporedite klijent - server i P2P aplikacijsku arhitekturu.

Klijent-server arhitektura je centralizirani sustav, ima centralno računalo - server koji sadrži podatke ili usluge, a klijenti komuniciraju s tim serverom i od njega dobivaju resurse. Server mora biti cijelo vrijeme dostupan te je ograničen na broj klijenata.
U P2P arhitekturi sva računala imaju jednake uloge u mreži, nemaju centralizirani administrativni sistem te dijele resurse jedni sa drugima, svako računalo može djelovati kao izvor ili primatelj podataka. Skalabilna mreža, postoje sigurnosni rizici zbog nemogućnosti provjere vjerodostojnosti povezanih računala, nema izravnih troškova održavanje mreže, mogućnost bržeg prijenosa podataka, nestalnost mreže.

36. Koja je uloga naredbe netstat u okviru operacijskog sustava ?

Naredba netstat prikazuje sve portove koji se trenutno koriste na računalu. 

37. Koja je uloga portova i navedite primjer za 4 porta (broj i uslugu) ?

Uloga porta je da identificira jedinstvenu destinaciju ili izvor podataka tijekom mrežne komunikacije, oni omogućavaju mrežnim uređajima da usmjeravaju podatke prema odgovarajućim aplikacijama ili uslugama na uređaju.
primjeri:
FTP - 21 - file transfer protocol
HTTP - 80 -hyper text transfer protocol
DNS - 53 - domain name service
HTTPS - 443 - secure hyper text transfer protocol
IMAP - 143 - internet message access protocol

38. Što je ISP i koje vrste postoje ?

ISP je pružatelj internetskih usluga, vrste ISP-a:
- za kućnu/poslovnu primjenu: spajanje na internet putem dial-upa, (a)DSL-a (telefonska linija), kabelskih modema(kabelska televizija), optičkih kablova
- za institucionalnu primjenu: CARNet
- za mobilnu primjenu: spajanje mobilnih uređaja na bazne stanice
// ILI
Širokopojasni: DSL, kabelski, optički
Bežični : Wi-Fi, mobilni
Satelitski
Lokalni ISP
Globalni ISP
Virtualni ISP

39. Što je TIER 1, TIER 2 i TIER 3 kod ISP ?

ISP su podjeljeni prema području djelovanja: 
- TIER 1: pružaju usluge na međunarodnom planu (međusobno su povezani direktnim fizičkim vezama, optički kablovi unutar određenog kontinenta ili države)(Google ili Akamai su djelomično organizirani kao TIER1 ISP-ovi)
- TIER 2 : pružaju usluge na regionalnoj razini (na razini države: CARNet)
- TIER3: pružaju pristup internetu na lokalnoj razini (T-com, H1, B.net, A1)

40. Što je propusnost (throughput) kod prijenosa podataka ?

Propusnost je mjerenje brzine prijenosa:  količina paketa koja se u određenom vremenskom intervalu može prenijeti s ishodišta do odredišta (Kbit/s, Mbit/s, Gbit/s,Tbit/s)

41. Što je data loss ili delay kod prijenosa podataka?

Data loss je udio podataka koji nikada ne pristignu ili na odredište stižu oštećeni. Delay je vrijeme koje je paketu potrebno da dođe iz ishodišta do odredišta.

42. Objasnite princip rada web preglednika.

Kada se upiše URL u web preglednik, preglednik traži IP adresu web stranice na DNS serveru, uspostavlja se konekcija sa serverom na kojemu se nalazi web stranica, šalje HTTP zahtjev serveru da bi server mogao poslati kopiju stranice. Ukoliko server pošalje potvrdnu poruku, odmah počinje slati i datoteke web stranice, koje šalje u manjim paketima. Preglednik sastavi pakete u cjelinu i prikaže ju korisniku.

43. Što je HTTP ?

HTTP (Hypertext transfer protocol)  je protokol potreban za razmjenu podataka između poslužitelja i preglednika web sadržaja 

44. Što je URL i navedite primjer ?

URL ( Uniform resource locator ) je adresa koja identificira određeni sadržaj na internetu, koristi se za lociranje i pristupanje različitim vrstama sadržaja. Obično sadrže informacije o protokolu , domeni i putanji do sadržaja.

npr https://www.unizd.hr

45. Što je WWW i navedite primjer?

WWW (World Wide Web) je globalni informacijski prostor na internetu koji omogućuje pristup i razmjenu podataka. On je jedan od ključnih sustava koji čini internet i omogućuje korisnicima pregledavanje i pretraživanje sadržaja putem web preglednika
npr https://www.google.com

46. Što je HTML i što on omogućava ?

HTML  (Hypertext markup language) je jezik koji je potreban za izradu web sadržaja, definira strukturu i način prikazivanja dokumenata u internetskim preglednicima. Jedna od osobina je izbjegavanje linearnosti, pomoću html-a je moguće pregledavati sadržaj preskakajući određene dijelove korištenjem poveznica ( linkove ).
Pomoću HTML-a omogućeni su smanjeni zahtjevi  prema hardverskim resursima servera (većina procesa tumačenja-prikazivanja sadržaja se odvija na klijentskim računalima), i omogućeno je smanjenje količine podataka koje je potrebno prenijeti između klijenta i servera.

47. Koji protokoli se koriste kod elektroničke pošte, objasnite na primjeru ?

Za slanje elektroničke pošte koristi se SMTP ( Simple mail transfer protocol) 
Za primanje elektroničke pošte koristi se POP (Post office protocol)
IMAP (Internet message access protocol) - za pristupanje i upravljanje epoštom.
Primjer : Klijentski program za epoštu koristi SMTP za slanje pošte, nakon što epošta stigne na poslužitelj za primanje epošte, korisnik koristi IMAP za pristup i upravljanje svojom epoštom

48. Što je FTP ?

FTP (File Transfer Protocol) je protokol za prijenos velikih količina datoteka

49. Definirajte što je podatak ?

Podatak je simbol koji prezentira pojedinačne izjave (tvrdnje) o realnom svijetu. Osnovni čimbenici podataka su izvornost, činjenice, kontekst, opažanje,mjerenje,zapisivanje,procesiranje, svrsishodni oblik.............

50. Na koji način možemo prikupljati podatke ?

Podatke možemo prikupljati na način da ih izravno mjerimo ili izravno percipiramo (čujemo,vidimo,nanjušimo itd), za stvari koje nisu izravno uočljive podatke možemo prikupiti pomoću anketa ili uspoređivanjem

51. Što je informacijska sigurnost ?

Informacijska sigurnost je zaštita informacija i informacijskih sustava od neovlaštenog pristupa, uporabe, otkrivanja, ometanja, izmjene ili uništenja.

52. Na kojoj razini se odvija računalna sigurnost ?

Računalna sigurnost se odvija na osobnoj ili organizacijskoj razini.

53. Objasnite povezanost računalne sigurnosti i produktivnosti poslovanja .

Povećanje sigurnosnih mjera često ide na štetu smanjenja produktivnosti ljudskog rada ili IT sustava kao i visokih financijskih investicija.

54. Koji su osnovni sigurnosni koncepti ?

Osnovni sigurnosni koncepti su :
- povjerljivost - za zaštitu informacija od neovlaštenog pristupa
- integritet - očuvanje točnosti i cjelovitosti informacija
- raspoloživost - osiguranje pravovremenog pristupa informacijama kada su potrebne 

55. Što je CIA trokut ?

CIA trokut je temelj za planiranje sigurnosnih mjera (Confidentiality, Integrity, Availability)

56. Objasnite ulogu povjerljivosti u sigurnosnom konceptu.

Uloga povjerljivosti je ograničenje pristupa određenim podacima, samo osobe s odgovarajućim ovlastima trebaju biti u mogućnosti pristupiti osjetljivim podacima.


57.  Objasnite jednu klasifikaciju povjerljivosti podataka.

Javni podaci: podaci koji su namjenjeni za javnu distribuciju.

58. Na koji način je definirana klasifikacija i povjerljivost podataka u Hrvatskoj  ?

Klasifikacija –  postupak utvrđivanja jednog od stupnjeva tajnosti podataka s obzirom na stupanj ugroze i područje, stupnjevi tajnosti klasificiranih podataka u RH : ograničeno,povjerljivo, tajno i vrlo tajno


59. Tko može klasificirati podatke u Hrvatskoj ?

Klasificiranje podataka mogu provoditi samo nadležna državna tijela u području obrane, sigurnosno-obavještajnog sustava, vanjskih poslova, javne sigurnosti, kaznenog postupka te znanosti, tehnologije, javnih financija i gospodarstva ukoliko su podaci od sigurnosnog interesa za RH

60. Koje su štićene vrijednosti u Hrvatskoj ?

Štićene vrijednosti se temelje Ustavom utvrđenog ustrojstva RH : neovisnost, cjelovitost i sigurnost RH; međunarodne odnose RH; obrambenu sposobnost i sigurnosno-obaviještajni sustav; sigurnost građana; osnove gospodarskog i financijskog sustava RH; znanstvena otkrića, pronalaske i tehnologije od važnosti za nacionalnu sigurnost RH

61. Koji su stupnjevi tajnosti podataka u Hrvatskoj ?

Stupnjevi tajnosti podataka u RH su: VRLO TAJNO, TAJNO, POVJERLJIVO, OGRANIČENO.

- VRLO TAJNO -  podaci čijim bi neovlaštenim otkrivanjem nastala nepopravljiva šteta za nacionalnu sigurnost i vitalne interese RH
- TAJNO - podaci čije bi neovlašteno otkrivanje teško naštetilo nacionalnoj sigurnosti i vitalnim interesima RH
- POVJERLJIVO - klasificiraju se podaci čije bi neovlašteno otkrivanje naštetilo nacionalnoj sigurnosti i vitalnim interesima RH
- OGRANIČENO - podaci čije bi neovlašteno otkrivanje naštetilo djelovanju i izvršavanju zadaća državnih tijela u obavljanju poslova u području nacionalne sigurnosti i vitalnih interesa RH

63. Objasnite razliku između poslovne i profesionalne tajne.

Poslovna tajna se odnosi na proizvodnu tajnu, istraživački ili konstrukcijski rad, kao i podaci koji nisu poznati stručnoj javnosti i podaci koji omogućavaju osiguranje gospodarskog napretka. Profesionalnom tajnom se smatraju svi podaci o osobnom i obiteljskom životu pojedinca koje je u obavljanju svog znanja saznao odvjetnik, javni bilježnik, branitelj, zdravstveni djelatnici, djelatnik skrbništva, vjerski ispovjednik ili bilko koja druga osoba prilikom obavljanja svog znanja.

64. Objasnite ulogu integriteta u sigurnosnom konceptu.

Uloga integriteta u sigurnosnom konceptu je osigurati da je podatak ili informacija zaštićena od neovlaštenih ili slučajnih promjena.

65. Navedite i ukratko objasnite moguće prijetnje integritetu podataka.

Moguće prijetnje integritetu podataka su : 
- ljudska pogreška - kada pojedinci netočno unose podatke, dupliciraju ili brišu, ne slijede odgovarajuće protokole ili pogriješe tijekom tih radnji.
- pogreške u prijenosu - podaci se ne mogu uspješno prenijeti s jedne lokacije u bazi podataka na drugu.
- pogreške i virusi - špijunski ili zlonamjerni softveri i virusi dijelovi su softvera koji mogu napasti računalo i promjeniti, izbrisati ili ukrasti podatke
- neispravan hardver- neispravan hardver može učiniti podatke netočnima ili nepotpunima, ograničiti pristup podacima ili otežati korištenje informacija.

66. Na koji način možemo očuvati integritet podataka ?

Integritet podataka možemo očuvati provjerom unosa, provjerom podataka, uklanjanjem dupliciranih podataka, sigurnosnim kopiranjem podataka, kontroliranjem pristupa podacima, pregledavanjem pristupa podacima.

67. Što je raspoloživost i kako je računamo ?

Raspoloživost -  dostupnost i upotrebljivost podataka na zahtjev ovlaštenog korisnika. Računa se formulom:
Raspoloživost = vrijeme dostupnosti / (vrijeme dostupnosti + vrijeme nedostupnosti)
ili ( Availability = Uptime/(Uptime+Downtime))

68. Što su rizici i prijetnje ?

Rizik je vjerojatnost da se dogodi neki događaj, prijetnja je vrlo specifičan rizik, radnja ili događaj koji bi mogao rezultirati kršenjem sigurnosti, ispadom ili oštećenje sustava iskorištavanjem poznatih ili nepoznatih ranjivosti.

69. Objasnite jednu od prijetnji iz ENISE taksonomije.

Prisluškivanje / presretanje / otmica - presretanje komprimitirajućih emisija, presretanje informacija, interferirajuće zračenje, ponavljanje poruka, mrežno izviđanje, manipulacija mrežnim prometom i prikupljanje informacija, otmica sesije.

70. Koja područja prijetnji je definirala ENIS-a. ?

ENISA identificira sljedeća područja koja su pod utjecajem prijetnji: Digitalna imovina, ekonomija, društvo, ugled, fizička sigurnost, psihološko okruženje

71. Koji su osnovni koraci u analizi rizika ?

Osnovni koraci u analizi rizika su : identifikacija rizika, analiza i prioritet, planiranje i vremenski raspored, praćenje i izvještavanje, kontrola mitigacije rizika, učenje o rizicima.

72. Što je izjava o riziku ?

Izjava o riziku je jezični izraz uzročne veze između stvarnog postojećeg stanja i potencijalnog, nerealiziranog drugog događaja ili stanja stvari .
Prvi dio izjave o riziku naziva se uvjetom i daje opis postojećeg stanja za koji tim smatra da bi uzročno moglo rezultirati gubitkom ili smanjenjem dobiti. Drugi dio izjave o riziku naziva se posljedica i opisuje nepoželjno stanje stvari.

ili 


Izjava o riziku obično se odnosi na dokument koji identificira, procjenjuje i opisuje različite vrste rizika s kojima se organizacija može suočiti u određenom projektu, procesu ili poslovnom kontekstu. Ova izjava ima za cilj pružiti jasno razumijevanje potencijalnih prijetnji ili neizvjesnosti koje mogu utjecati na postizanje ciljeva ili uspješnost određenih aktivnosti.

73. Što je vjerojatnost rizika ?

Vjerojatnost rizika je mjera vjerojatnosti da će se stanje stvari opisano u dijelu izjave o riziku o posljedicama stvarno dogoditi

74. Što je učinak rizika ?

Učinak rizika je procjena ozbiljnosti štetnih učinaka, ili veličine gubitaka, ili potencijalnog oportunitetnog troška ako bi se rizik realizirao unutar projekta ili organizacije. Može se predstaviti ili u brojčanim terminima ili kao izrazi prirodnog jezika.

75. Objasnite ulogu izloženosti riziku i rangiranje rizika.

Rangiranje rizika se koristi za određivanje prioriteta rizika prema njihovoj ukupnoj opasnosti za organizaciju kao i određivanja prioriteta djelovanja na rizike. Metoda izloženosti riziku se izvodi množenjem vjerojatnosti rizika s utjecajem rizika.

76. Koja je uloga smanjenja izloženosti riziku ?

Smanjenje izloženosti riziku znači prepoznati moguće ranjivosti, te probati riješiti se ranjivosti.

77. Koja je uloga akcijskog plana i koji su  mogući načini provedbe ?

Ako se ne može napraviti smanjenje izloženosti rizicima, potrebno je definirati akcijski plan. 
Mogući načini provedbe su : istraživanje (istraživanje o uzrocima može smanjiti rizik), prihvaćanje (rizici kod kojih nije moguće efektivno intervenirati, prihvatiti ih,dokumentirati te pratiti), izbjegavanje (rizik koji se lako kontrolira može se umanjiti ili eliminirati ukoliko se promjeni opseg projekta), prijenos(prijenos rizika drugom entitetu van projekta(outsourcing)), smanjenje(),plan za nepredviđene situacije (kreiranje jedne ili više rezervnih opcije ako pokušaji da se spriječi štetni događaj ne uspiju)

78. Što je načelo najmanjih privilegija ?

Načelo najmanjih privilegija je sigurnosna disciplina koja zahtjeva da se korisniku, sustavu ili aplikaciji ne da više privilegija nego što je potrebno za obavljanje njihove funkcije ili posla

79. Koja je uloga podjela dužnosti ?

Uloga podjele dužnosti je da spriječi bilo koju pojedinačnu osobu ili entitet da ima potpuni pristup ili obavlja sve funkcije kritičnog ili osjetljivog procesa. (kako bi se spriječile prijevare, krađe i pogreške)

80. Navedite moguća područja mogućih napada ili kompromitacije računalnog sustava  i ukratko ih opišite ?

Područja mogućih napada su : 
- informacijski sustav(aplikacije) (kod u aplikaciji, broj ulaznih podataka u aplikaciju, broj pokrenutih usluga, portovi sa kojima aplikacija radi)
- računalne mreže (opći dizajn mreže, pozicija ključnih sustava, pozicija vatrozida, pozicija drugih sigurnosno povezanih mrežnih uređaja)
- zaposlenici/osobe (socijalni inženjering, potencijal za ljudske pogreške, rizik zlonamjernog ponašanja)

81.  Na koji način se provodi analiza mogućih napada na računalni sustav ?

Identifikacija ranjivosti, pregled arhitekture sustava, identifikacija i ocjena prijetnji, analiza scenarija napada, simulacija napada, analiza logova i praćenje aktivnosti, procjena utjecaja, upravljanje rizicima, implementacija sigurnosnih mjera

# ŠTO JA ZNAN

82. Što podrazumijevamo pod socijalnim (društvenim) inžinjeringom ?

Socijalni inženjering podrazumjeva stjecanje informacija o mreži ili sustavu socijalnim sredstvima (iskorištavanjem ljudske psihologije). To je tehnika obmane koju koriste hakeri kako bi dobili informacije ili podatke o određenom sustavu. 

83. Kako se organizira fizička sigurnost računalnog sustava ?

Fizičko smještanje računala i drugih uređaja u osigurane prostore, ograničavanje pristupa ovim prostorima samo ovlaštenim osobama, nadzor pristupa, video nadzor, osiguranje od prirodnih katastrofa, održavanje inventara, sigurnosna osoblja, zaštita od elektromagnetskih smetnji etc

84. Koja je uloga kontrole pristupa ?

Uloga kontrole pristupa je da se ograniči pristup resursima samo ovlaštenim korisnicima, aplikacijama ili računalnim sustavima

85. Koja je uloga autentikacije ?

Uloga autentifikacije je da se korisnik identificira podacima (ili tokenima ili biometrijskim podacima) koji su samo njemu poznati , kojima će pristupiti informacijama ili sustavu.

86. Koja je uloga autorizacije ?

Autorizacija se odnosi na proces dodjele prava i privilegija određenim korisnicima, računalima ili sustavima kako bi se omogućio kontrolirani pristup određenim sadržajima ili funkcionalnostima sustava. Ovaj proces osigurava da korisnici imaju onoliko prava koliko im je potrebno za obavljanje svojih poslova.

87. Koja je uloga praćenja aktivnosti ?

Praćenje aktivnosti znači da se bilježe sve aktivnosti vezane uz pristup a administratori mogu pregledati te zapise radi identifikacije eventualnih nepravilnosti

88. Što je digitalni certifikat ?

Elektronički dokument koji sadrži identitet(korisnika ili org. ), i pripadajući javni ključ. Koristi se za autentifikaciju kako bi dokazao identitet osobe. 

89. Koja je uloga "smart kartica" ?

Uloga pametne kartice je da utvrdi identitet osobe tj nositelja kartice. Može sadržavati digitalni certifikat za dokazivanje identiteta ili dozvole i informacije o pristupu.

90. Koja je uloga zaštitnih tokena ?

Sigurnosni tokeni su fizički uređaji koji ovlaštenom korisniku računalnih usluga olakšava autentifikaciju. Mogu sadržavati USB priključak, RFID funkcije ili bluetooth sučelje. Neki uključuju dodatne tehnologije poput statičke lozinke ili digitalnog certifikata, slično pametnoj kartici, neki automatski generiraju drugi kod koji se mora unijeti radi identifikacije.

91. Što je biometrika ?

Biometrija je biološka karakteristika koja je jedinstvena pojedincu(otisak prsta, prepoznavanje lica, iris i zjenica, govor, dlan, vena etc.), koristi se kao metoda identifikacije kako bi se poboljšala sigurnost.

92. Koja je uloga administratora na sustavu i kako se ona odvija u Windows okolini ?

Administrator u sustavu, uključujući Windows okolinu, ima ključnu ulogu u upravljanju, održavanju i osiguravanju pravilnog funkcioniranja računalnog sustava. Administrator ima ovlasti i privilegije koje mu omogućuju pristup i kontrolu različitim dijelovima sustava.
U windows okolini on može upravljati korisnicima ili grupama, upravljati resursima(instalacija,konfiguracija softvera..), održavati sustav(ažuriranje), izvođenje sigurnosnih kopija podataka, upravljanje sigurnosnim postavkama ili pravilima............................................................

93. Što je korisnički račun ?

Korisnički račun je identifikacijski entitet koji omogućuje korisniku pristup računalnom sustavu, mreži ili uslugama. Korisnički račun uključuje informacije koje jedinstveno identificiraju korisnika i definiraju njegova prava i privilegije unutar sustava.

94. Što je grupa korisnika ?

Grupe predstavljaju organizacijski mehanizam u sustavima za upravljanje korisnicima koji omogućuju grupiranje korisnika kako bi im se olakšalo zajedničko upravljanje i dodjeljivanje prava pristupa. korisnik unutar grupe automatski nasljeđuje određene karakteristike, privilegije ili prava pristupa koji su dodjeljeni toj grupi.

95. Usporedite prava i dozvole korisnika ?

Prava se odnose na posebna ovlaštenja ili privilegije koje korisnik ili entitet ima unutar sustava(Administratorska prava koja omogućuju korisniku mijenjanje postavki sustava, instaliranje i deinstaliranje softvera, pristupanje posebnim resursima, itd.)
, Dozvole se odnose na dopuštenja koja određuju što korisnik može raditi s određenim resursima ili podacima.(Dozvole na datotekama i mapama koje kontroliraju tko može čitati, pisati ili izvršavati određene datoteke. Dozvole na mrežnim resursima koje definiraju tko može pristupiti tim resursima.)


ili ukratko prava se obično odnose na šire ovlasti koje korisnik ili entitet ima unutar sustava, dok se dozvole odnose na specifična dopuštenja koja kontroliraju pristup, manipulaciju ili korištenje određenih resursa

96. Koja je uloga dijeljenja diskova i mapa, te na koji način se može provesti sigurnosni postupak ?

Dijeljenje diskova i mapa (ili resursa) u mrežnom okruženju dopušta korisnicima pristup zajedničkim podacima i resursima na računalnim sustavima.Sigurnosni postupci : postavljanje preciznih dozvola pristupa na dijeljenim resursima kako bi se kontrolirao pristup, čitanje etc, enkripcija podataka, korištenje sigurnosnih metoda pristupa......... neman pojma

97. Koja je uloga enkripcije i dekripcije u zaštiti podataka ?

Uloga enkripcije i dekripcije je osigurati sigurnost informacija. Enkripcija pretvara čitljivi podatak u nečitljivu formu pomoću matematičkih algoritama i ključeva, dekripcija vraća nečitljivu formu u čitljivi podatak pomoću ključa ili lozinke.

99. Što je digitalni potpis ?

Digitalni potpis je način potvrde autentičnosti, integriteta i porijekla digitalnog dokumenta ili poruke. Koristi se u svrhu osiguranja elektroničkih informacija i pružanja vjerodostojnosti identiteta potpisnika. 

100. Objasnite postupke zaštite zaporkom u svrhu povećanja sigurnosti.

Zaporke trebaju biti duljine najmanje od 8-12 znakova, trebaju sadržavati mala i velika slova, posebne znakove i brojeve. Treba izbjegavati jednostavne lako pogodljive zaporke, i zaporke treba redovito mjenjati (svakih 3-6 mjeseci)