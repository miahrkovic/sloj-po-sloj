# Sloj po sloj 🦜

2D igra o pokretanju male 3D print firme u Zaprešiću. Igraš dva lika: **Miu**, koja vodi papire, kupce i obiteljski vrtić, i **Marvina**, koji printa, dizajnira i popravlja printere.

**Igraj:** https://miahrkovic.github.io/sloj-po-sloj/

**1 sekunda u stvarnosti = 1 minuta u igri.** Kad oboje rade, vrijeme ide brže, a noć i čekanje mogu se preskočiti.

## Kako igrati

- Na **karti** šalješ likove na lokacije: stan, radionica, Zavod, ured za obrt, Porezna, banka, FINA, bilježnik, vrtić, kafić, Box Now, pošta, roditelji.
- Svaki lik ima svoj **mobitel**: poruke, mail, kalendar, banka, oglasnik, Bambu aplikacija, računi, Instagram, e-Građani…
- **Žvonini zadaci** kažu što je sljedeće (npr. „Idi po papir X u FINU”), a hint objasni kako.
- Kartica **Čekamo** odbrojava sve što čekaš (rješenja, certifikati, dostave, printovi).
- Pazi na živce, umor i glad.

## Otvaranje firme u 10 koraka

1. Prostor i ugovor o najmu
2. Zavod za zapošljavanje i potpora
3. Registracija obrta
4. Porezna, mirovinsko i zdravstveno
5. Poslovni račun u banci
6. FINA certifikat i aplikacija za račune
7. Filament i preseljenje printera
8. Financiranje
9. Režije i usluge
10. Prva narudžba i prvi fiskalizirani račun

## Što sve ima

- **Šalteri** s redovima, marendom i papirima koji fale; online usluge preko e-Građana; poslovni sastanci video pozivom.
- **Kupci**: ponude s klizačem cijene, stalni i zahtjevni kupci, poruke o narudžbi (produženje roka, popust, fotka napretka), Google recenzije.
- **Printanje**: filament u 6 boja, pregled prije printa, kamera i timelapse, dijagnostika kvara.
- **Webshop s uređivanjem**, galerija proizvoda, sezone (Valentinovo, Majčin dan, škola, advent).
- **Firma**: faze od garaže do hale, automatika, knjigovodstveni stol, tjedni planer, kalendar, ciljevi, godišnji pregled.
- **Teške odluke**, inspekcije (s karticom što ispraviti), proslave prekretnica.
- **Vrtić**: zadaci u vrtiću i misija preuzimanja vrtića od mame.
- **Prvi zaposlenik**: oglas, intervju, probni rad.
- Animirana karta s godišnjim dobima, radionica koja raste s firmom, tamni način, veći tekst.

## Račun i igra za dvoje

- Prijava korisničkim imenom i PIN-om, pa igru nastavljaš na svakom uređaju. Može i bez računa.
- **2 igrača**: tko napravi igru, dobije kod od 6 znakova; drugi ga upiše i dobije drugi lik.
- Spremanje radi preko besplatnog Supabase projekta (`players`, `games`, funkcije `sps_*`; PIN se sprema kao hash).

## Napomene

- Iznosi, paketi banaka, cijene i pravila **izmišljeni su ili pojednostavljeni za igru**.
- Za testiranje dodaj `#brzo` na kraj adrese: vrijeme ide 10 puta brže.
