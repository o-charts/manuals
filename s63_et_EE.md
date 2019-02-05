---
layout: default_et_EE
---
# S-63 kasutajaloa tingimused

- S-63 plugin ei ole Androidile või iOS'le saadaval.

- Me ei müü S-63 kaarte, me ainult kindlustame S-63 *kasutajaloaga* kui nõutud vahendiga kaartide litsenseerimiseks S-63 kaartide edasimüüjatelt nagu [Chartworld](https://www.chartworld.com/shop/off_enc).

- S-63 kaardi soetamiseks ükspuha missuguselt varustajalt on sul vaja kasutajaluba. OpenCPN S-63 kasutajaloaga litsenseeritud kaarte saab kasutada ainult koos OpenCPN'ga nagu on määratud S-63 standardis.

- Sul on lubatud sama-aegselt kasutada iga sinu poolt soetatud kaarti 5-s *süsteemis* või sa võid neid säilitada juhuks kui su süsteem sureb. Me loome OpenCPN'i *paigaldusloa* iga individuaalse süsteemi jaoks. Paigaldusluba seob OpenCPN'i S-63 kaardikomplekti ühe süsteemiga. Ärge ajage OpenCPN'i paigaldusluba segamine S-63 kärjeloaga.

- *Süsteem* on kombinatsioon arvutist ja op.süs. Kui ükski neist muutub, tuvastatakse su süsteem kui uus, sa kaotad oma litsentsi ja sul tuleb kasutada uus paigaldusluba.

- Kui oled oma 5 võimalust ära kasutanud tuleb sul soetada uus kasutajaluba ja seega litsenseerida kaardid selle uue kasutajaloa jaoks. Kuna see on uus tsükkel, siis on sul jälle 5 võimalust paigalduseks (kasutajaluba).

- Su litsents peaks iga op.süs., OpenCPN või plugina uuenduse üle elama, kuid kui taaspaigaldad oma op.süs. kaotad oma litsentsi.

- Kui oled kasutajaloa kord juba litsenseerinud ei saa me seda hüvitada.

- Kui oled juba loonud paigaldusloa ühe süsteemi jaoks ei saa me seda tühistada või suunata erineva sedme/op.süs. kombinatsiooni juurde.

- Kontrolli S-63 kaartidega varustajate uuendamise ja aegumise tingimusi.

# Kasutajaloa/paigaldusloa ja S-63 kaartide paigaldus

![sammud](./assets/images/s63.png)

1. *Süsteem* on arvuti, mida sa kasutad OpenCPN'i jaoks. Selle süsteemi jaoks VAR'lt litsenseeritud kaardikomplekti saab kasutada ainult seal. Lae alla ja paigalda [S-63-plugin](https://opencpn.org/OpenCPN/plugins/s63.html) (ainult OpenCPN versioonile 4.6 ja uuem).
    
2. Mine OpenCPN, *Valikud → Pluginad → S63* ja aktiveeri ta. Seejärel mine OpenCPN, vahekaardile *Valikud → Kaardid → S63-kaardid → Võtmed/Load* ja loo süsteemi tuvastusfail (*sõrmejälg*) oma süsteemi jaoks klõpsates nuppu *Loo süsteemi tuvastusfail*.
    
3. Mine [o-charts poodi](https://o-charts.org/shop) ja osta kasutajaluba.
    
4. Mine [Mu S-63 kasutajaload](https://o-charts.org/shop/index.php?fc=module&module=ocpermits&controller=ocpermits) lehele ja loo paigaldusluba laadides sõrmejälje faili, mis sa ennem tekitasid, üles ja sidudes ta su S-63 kasutajaloaga.
    
5. Mine oma VAR (S-63 kaardi varustaja) poodi ja litsenseeri nii palju S-63 kaarte kui sul vaja on kasutades su OpenCPN S-63 kasutajaluba. Mõnikord VAR küsib "HW-ID", eira küsimust.
    
6. Lae alla ja paki oma S-63 kaardikomplekti failid lahti. Seal peab olema kaust nimega ROOT_ENC (sisaldab kaardikärgi) ja sa peaksid samuti leidma faili nimega PERMIT.txt koos ruutude loaga.
    
7. Mine OpenCPN, vaheleht *Valikud → Kaardid → S63-kaardid → Võtmed/Load*. Sisesta oma kasutajaluba ja testi seda klõpsates nuppu *Uus kasutajaluba*. Sisesta oma paigaldusluba ja testi seda klõpsates nuppu *Uus paigaldusluba*.
    
8. Mine OpenCPN, vaheleht *Valikud → Kaardid → S63-kaardid → Kaardikärjed*. Paigalda kärjeload kasutades nuppu *Impordi kärjeload*, et leida fail PERMIT.txt su S-63 kaardikomplekti seest. Impordi oma S-63 kaardikomplekt vajutades *Impordi kaardid/uuendused* kausta ENC_ROOT leidmiseks.
    
9. OpenCPN loob vajalikud eSENC-failid ja ongi kõik!

# Korduma Kippuvad Küsimused (aka FAQ)

> **Miks S-63 kaardid?**
> 
> Need on ametlikud ja üldiselt kõige ajakohastatum saadavalolev kaardimaterjal. Vabajaturul kasutatavate kaardiplotterite vektorkaardid on parimad tuletused (mõnel on lisatud muid lisaomadusi).
> 
> **Miks ma pean maksma selle kasutajaloa eest?**
> 
> Me peame seda tegevust juhtima ja vastutama IHO ees lõplikult. Struktuur ja kulud on hoitud miinimaalseina. Juhul kui meid saadab majanduslikus mõttes suur edu, läheb raha tagasi OpenCPN'i.
> 
> **Kui mitu süsteemi loevad kui kahesüsteemne buutimine?**
> 
> Iga riist-/tarkvara kombinatsioon on üks individuaalne ja vajab enda oma paigaldusluba.
> 
> **Ja kui ma installin tarkvara virtuaalmasinasse?**
> 
> See ei tööta seal. Meil tuleb vältida süsteemi kloonimist.
> 
> **Mul tuli enda op.süs. taaspaigaldada. Nüüd ei ole paigaldusluba enam kehtiv**
> 
> Palun loo uus paigaldusluba.
> 
> **Mu arvuti suri. Kas ma saan kaardid taastada?**
> 
> Ja, see juhtum laheb sulle "maksma" samuti ühe paigaldusloa oma uue arvuti jaoks.
> 
> **Kas ma saan oma paigaldusluba ja kaarte hoida USB-pulgal ja kanda neid erinevate süsteemide vahel?**
> 
> See oleks riistvaralise dongli olukord. Meil on tunne, et meil ei ole mõistlik saata USB-pulki või DVD'id üle kogu maailma. Seetõttu me valisime tarkvaralise dongli. Nii et täna on vastus - ei.
> 
> **Kui palju S-63 kaardid maksavad (ning miks nad mõnikord nii kallid on)?**
> 
> Jaehinna kinnitab iga HO eraldi. Nende kliendid on laevandustööstus või ametiasutused nagu valitsused, mitte vabaajaturg. See on teada-tuntud probleem ja ka põhjus, miks praegu on väga vähe S-63 kaartide kasutajaid selles rühmas. Me vajame palju lobitööd paremate lahenduste ja soodsamate hindade saamiseks. Abi või tugi nende poolt, kellel on õiged kontaktid, oleks teretulnud.
> 
> **Mu ajutine litsents hakkab aeguma. Mis juhtub?**
> 
> Kaart ei kao, kuid seal kuvatakse hoiatust.
> 
> **OpenCPN on avatud lähtekoodiga. Kus on selle plugina kood?**
> 
> Et töötada S-63 peame olema kindlad, et ükski krüpteerimata kärje koopia ei ole ligipääsetav tarkvara käitamise jooksul. Seetõttu on pluginal avatud lähtekoodi osa ja binaarne. Sarnaselt äriliste BSB4 või nv-kaartide pluginatega.
