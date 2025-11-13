# Softversko-Inzenjerstvo-2026
## Dokumentacija
<ins>__Pomoć pri korišćenju__</ins>
## Sadržaj
### Korisnički deo
1. Uvod
2. Glavna srana\
     2.1 Pretraživanje\
     2.2 Prikaz oglasa
3. Meni\
   3.1 Prijava i registracija\
   3.2 Pretraživanje\
        3.2.1 Filteri\
   3.3 Upravljanje svojim oglasima
4. Profili
   4.1 Uređivanje
   4.2 Oglasi
### Developer deo
1. Uvod
2. ...
3. ...
4. ...
<hr>

# Korisnički deo
## 1. Uvod
Dobrodošli u zvaničnu dokumentaciju Oglasi za Posao Novi Pazar (u nastavku "OPNP"). Ova dokumentacija je namenjena korisnicima kojima treba pomoć pri korišćenju sajta i developerima koji razvijaju funkcionalnosti sajta. Ovde ćete pronaći detaljna uputstva za korišćenje svih funkcionalnosti, kao i tehničke informacije za razvoj i integraciju dodatnih opcija.\
OPNP omogućava korisnicima jednostavno pretraživanje, postavljanje i upravljanje oglasima, dok pruža developerima mogućnost da prošire funkcionalnosti ili implementiraju dodatne funkcije prema potrebama. Naša misija je da stvorimo intuitivan i efikasan alat za sve koji žele da pronađu željeni posao na internetu.
## 2. Glavna strana
Glavna strana OPNP je prva strana kojom će te pristupiti pri ulazku na sajt, sa njene leve strane je prisutan meni koji ulazi dublje u funkcionalnosti sajta. Na glavnoj strani, ispod naslova, možete naći traku za pretragu, kao i nedavno objavljene oglase za posao.\
Traka za pretragu omogućava korisnicima da unesu nazive oglasa i ključne reči vezane za posao koji traže i omogućava brzo filtriranje oglasa prema zadatim kriterijumima. Ispod nje se nalaze nedavno objavljeni oglasi. Korisnik sa leve strane, pre menija, ima opciju da sortira oglase po svojoj želji.
### 2.1 Pretraživanje
Pretraživanje oglasa se radi pomoću trake za pretraživanje prikazano na glavnoj strani ili u meniju. U njoj direktno možete ukucati naziv oglasa ukoliko sigurno znate oglas koji vas interesuje. Pored pretrage preko naziva oglasa, OPNP daje jos sledeće mogućnosti:
- **Pretraga po ključnim rečima:** Korisnici mogu upisivati specifične fraze ili reči vezane za poziciju, firmu, lokaciju, itd.

- **Automatski predlozi:** Dok korisnik upisuje, aplikacija može automatski predlagati ključne reči ili popularne pretrage.

- **Pretraga po kategorijama:** Pored slobodnog unosa, korisnici mogu odabrati određene kategorije industrije koje ih zanima (npr. "IT", "Marketing", "Zdravstvo") za precizniju pretragu.
### 2.2 Prikaz oglasa
Ispod trake za pretragu, na početnoj stranici, prikazuju se nedavno objavljeni oglasi. Pri ulazku na sajt, oglasi na glavnoj strani nisu filtrirani, ona samo prikazuje oglase koji su nedavno objaveljeni do vašeg ulazka. Oglasi su prikazani u obliku kartica ili prozora koji imaju sažete informacije o poslu koji oni opisuju, da bi ste dobili punu informaciju, kliknite na njega i on će izaći na sred ekrana u uveličanim dimenzijama.
Oglasi su zadano sortirani po vremenu kada su objavljeni, krenući od novijih ka starijim. Mogućnosti sortiranja oglasa po datumu imate levo, pre menija.

**Sortiranje po datumu:** Oglasi su sortirani po datumu objavljivanja, sa najnovijim oglasima prikazanim na vrhu. Oglase je moguće sortirati na sledeći način:

- Noviji ka starijim
- Stariji ka novijim
- Oglasi objavljeni ovog meseca, krećući od novijih
- Oglasi objavljeni ovog meseca, krećući od starijih
- Oglasi objavljeni ove nedelje, krećući od novijih
- Oglasi objavljeni ove nedelje, krećući od starijih

**Detalji malog prozora oglasa:** Svaki oglas prikazuje osnovne informacije, kao što su:

- Naziv pozicije
- Naziv kompanije
- Lokacija
- Kratak opis posla
- Plata
- Broj telefona i/ili email poslodavca
- Datum objavljivanja

**Pregled punog oglasa:** Klikom na oglas, korisnici mogu videti sve informacije tog oglasa, kao što su pun opis, zahteve posla i sve detalje vezano za taj posao.
## 3. Meni
Meni služi za dalje i detaljnije pregledanje oglasa. Na njemu se nalaze funkcionalnosti koje će omogućiti korisnicima da prave svoje oglase uz registraciju i/ili prijavu. Pored toga meni daje opcije daljeg filtriranja oglasa po svojoj želji.
### ***Napomena!:*** <ins>Neke funkcionalnosti nisu dostupne ukoliko korisnik nije prijavljen.</ins>

1. **Dugme za prijavu i registraciju:** Na samom početku korisnicima je omogućeno da se prijave ili registruju. Ovo dugmić je vidljivo pre nego što korisnik postane prijavljen. Nakon što korisnik izvrši prijavu, dugme za prijavu i registraciju se zamenjuje sa sledećim informacijama o korisničkom profilu.

2. **Profilna slika i ime korisnika:** Kada se korisnik uspešno prijavi, prikazuju se njegova profilna slika (ako je postavljena, u slučaju će se prikazati placeholder slike) i ime korisnika. Ove informacije su vidljive u meniju i omogućavaju korisnicima da brzo prepoznaju da li su prijavljeni ili ne.

3. **Dugme za odjavljivanje:** Nakon prijave, ispod imena i profilne slike korisnika, prikazuje se dugme za odjavljivanje. Klikom na ovo dugme, korisnik će biti odjavljen i stranica će se osvežiti.

4. **Traka za pretraživanje oglasa:** Meni uključuje traku za pretraživanje oglasa, pored one na glavnoj strani, koja omogućava korisnicima da brzo pretražuju oglase prema nazivima oglasa, ključnim rečima i kategorijama. Pretraga se vrši u realnom vremenu, što znači da dok korisnik upisuje, korisniku se predlažu ključne reči i oglasi koji imaju veći broj posetioca.

5. **Dugme za kreiranje i objavljivanje oglasa**: Za poslodavce i korisnike koji žele da postave oglas za posao, tu je dugme koje vodi ka stranici za kreiranje i objavljivanje novog oglasa. Ovo dugme je vidljivo samo korisnicima koji su prijavljeni na svoj nalog. Pritiskom na dugme izaći će prozor koji će vas upitati za informacije o oglasu koje će te morati da unesete (izuzetak je baner, koji je opcionalan).

6. **Filteri za tip posla:** Na meniju se nalaze filteri koji omogućavaju korisnicima da suže pretragu prema tipu posla, korisnici mogu selektovati jedan ili više tipova posla. Filteri takođe omogućavaju preciznije traženje kao što je grad, radno vreme, plata i drugo. Korišćenjem filtera, korisnici mogu izabrati poslove koji odgovaraju njihovim željama u vezi bilo čega.

### 3.1 Prijava i registracija
- ### Prijava
### ***Napomena!:*** <ins>Da bi ste se prijavili, prvo morate biti registrovani.</ins>
Klikom na dugme "Prijavi se" koje se nalazi u meniju sajta, izaći će vam prozor na sredini stranice, koji će u sebi imati sledeće upite:
- Email
- Lozinku
> <ins>Ako ste zaboravili lozinku, imate opciju da resetujute lozinku, klikom na odrećeni tekst, koji se nalazi ispod navedenih upita, pre dugmeta za podnošenje prijave.</ins>

Nakon što ste uneli podatke, kliknite na dugme "Prijava" koje se nalazi ispod svih upita, ako su vaši podaci tačni, bićete prijavljeni i preusmereni na početnu stranicu.\
Nakon prijave, dugmad za prijavu i registraciju će biti zamenjena slikom vašeg profila (ukoliko ste je stavili, u suprotnom biće prikazan placeholder slike), zajedno sa vašim korisničkim imenom i dugmetom za odjavu.
- ### Registracija
Ako nemate nalog, potrebno je da se registrujete kako biste imali potpuni pristup funkcionalnostima sajta. Možete se registrovati klikom na dugme "Registrujte se" koje se nalazi u meniju, nakon čega će vam izaći prozor na sredini stranice koje će sadržati sledeće upite:
- Korisničko ime
- Email adresa
- Lozinka
- Potvrda lozinke\
Nakon popunjavanja forme, kliknite na dugme "Registruj se", nakon toga, novi prozor će vam izaći, tražeći vam kôd. Na vaš email će biti poslat verifikacioni kôd. Unesite ga kako biste potvrdili svoj nalog.\

### ***Napomena!***: <ins>Mi vam nikada nećemo poslati email ili poruku, tražeći vaše podatke. Čuvajte se od prevara.</ins>
### 3.2 Pretraživanje
Pretraživanje oglasa se radi pomoću trake za pretraživanje prikazano na glavnoj strani ili u meniju. U njoj direktno možete ukucati naziv oglasa ukoliko sigurno znate oglas koji vas interesuje. Pored pretrage preko naziva oglasa, OPNP daje jos sledeće mogućnosti:
- **Pretraga po ključnim rečima:** Korisnici mogu upisivati specifične fraze ili reči vezane za poziciju, firmu, lokaciju, itd.

- **Automatski predlozi:** Dok korisnik upisuje, aplikacija može automatski predlagati ključne reči ili popularne pretrage.

- **Pretraga po kategorijama:** Pored slobodnog unosa, korisnici mogu odabrati određene kategorije industrije koje ih zanima (npr. "IT", "Marketing", "Zdravstvo") za precizniju pretragu.
### 3.2.1 Filteri
Filteri vam omogućavaju da jos više i detaljnije sužite vaš prikaz oglasa na one koji vas najviše zanimaju, sa njima možete izolovati industrije i pozicije koje vama odgovaraju.
> Na primer: Filtrirajući mesto rada na "Kafić", vama će biti prikazivani samo poslovi vezani za tu vrstu radne ustanove, to bi mogli biti:
> - Konobar
> - Šanker
>  
> ove pozicije možete dalje filtrirati, klikom na opciju "Konobar", dobijat ćete samo oglase gde se kraži konobar u kafićima.

### 3.3 Upravljanje svojim oglasima
Nakon regisracije i prijave, dobit ćete mogućnost objave svojih oglasa, klikom na dugme "Objavite oglas", koje se nalazi ispod dugmeta za odjavu u meniju. Nakon klika, izaći će vam prozor koji vam daje sledeće upite:
- Baner (opcionalno, baner birate tako što unosite sliku sa vašeg uređaja)
- Naziv oglasa
- Opis posla
- Tip radnika koji je tražen
- Ime i adresu firme/poslovnog mesta/preduzeća
- Email (možete ostaviti prazno ukoliko želite da koristite email sa vašeg naloga)
- Broj telefona (opcionalan, stojaće pored unesenog email-a)
- Platu
- Radno vreme
Nakon uspešnog objavljivanja oglasa, na njima ćete imati dugmad za uređivanje oglasa i brisanje oglasa, koja se nalaze na gornjem desnom uglu oglasa. Ovu mogućnost imate samo nad oglasima koje ste vi objavili. Ukoliko želite da vidite sve vaše oglase, idite u meni i kliknite na vašu profilnu sliku (ukoliko niste postavili sliku, kliknite na placeholder) ili na vaše ime i otićiće te na vaš profil, gde će biti prikazani svi oglasi koje ste objavili, profili su detaljnije objašnjeni u sledećem polju.
## 4. Profili
Korisnik ima mogućnost proveravati profile drugih korisnika, uglavnom poslodavaca. Na profilima se mogu naći slika (ukoliko je postavljena, u suprotnom se pojavljuje placeholder), korisničko ime i opis. Ispod dela u kome se nalaze prethodno navedene informacije, mogu se naći oglasi koje je korisnik objavio.
### 4.1 Uređivanje
Prijavljeni korisnik ima mogućnost daljeg uređivanja svog profila nakon registracije. Korisnik na svom profilu imaće dugme u gornjem desnom uglu, koje ga vodi ka stranici za izmenu prfoila. Na toj stranici se mogu promeniti informacije koje su unete pri registraciji, a takođe se mogu dodati i sledeće stavke:
- Profilna slika
- Baner profila
- Opis
- Kontaktni email i/ili telefon
- Adresa firme/poslovnog mesta/preduzeća\
Ispod svih ovih upita, nalazi se dugme za brisanje naloga, koje korisnik može da iskoristi ako bi mu to zatrebalo.
### 4.2 Oglasi
Korsnik može ući na svoj profill ili profil drugog korisnika kako bi mogao videti sve oglase koje su objavljeni sa tog profila. Korisnik takođe ima mogućnosti filtriranja i sortiranja na prethodno navedene načine.
> Pogledajte <ins>2.2 Prikaz oglasa</ins> i <ins>3.2.1 Filteri</ins>
