**Ala loomine:** 
1. Puupulgaga diagonaalid (vasak- ja paremklikk). 
2. ***/ala loo suur <alaNimi>*** 
 
*Kommentaarid:* luuakse uus ala. Ala nimi on soovituslik panna formaadis "<mängija>_ala". Juba mitmenda ala puhul "<mängija>\_ala\_<nr>" (teine ala on siis "<mängija>_ala_2"). Ala miinimumsuurus on 5x5 ja maksimum 30x30 plokki ning üks mängija saab ise teha kuni 3 kaitseala. Alad tehakse automaatselt maast taevani. 
 
**Siseala loomine:** 
1. Pulgaga diagonaalid. 
2. ***/ala loo sise <alaNimi>*** 
 
*Kommentaarid:* luuakse suuremasse alasse uus siseala, mis peab asuma suurema ala sees. Siseala sisse sisealasid teha ei saa. Siseala nimi tuleks panna samas formaadis, mis tavaline ala. Kui on vaja siseala mängijaid hallata jms teha, siis selle <alaNimi> on "<suurealaNimi>.<sisealaNimi>" (nt kui suure ala nimi on "Lahemees47_ala" ja väikse oma pandi "albiino_kajakas_ala", siis tuleb kasutada nime "Lahemees47_ala.albiino_kajakas_ala". Tähtis on seal see punkt.). 
 
**Ala info vaatamine:** 
1. Ala info - ***/ala info [alaNimi]*** 
2. Oma alade nimekiri - ***/ala list suur*** 
3. Aladesse kuuluvate sisealade nimekiri - ***/ala list sise*** 
4. Ala piiride vaatamine - ***/ala piirid*** 
 
**Ala muutmine:** 
1. Ümbernimetamine - ***/ala nimi <vanaNimi> <uusNimi>*** 
 
**Muud ala käsud:** 
1. Teleportimise asukoha panemine - ***/ala punkt*** 
2. Ala juurde teleportimine - ***/ala mine <alaNimi>*** 
3. Alalt võõra välja viskamine - ***/ala viska <mängija>*** 
 
**Alasse kuuluvate mängijate haldamine:** 
1. Omaniku muutmine: ***/ala anna <alaNimi> <mängija>*** 
2. Liikme lisamine: ***/ala lisa <alaNimi> <mängija>*** 
3. Liikme eemaldamine: ***/ala eemalda <alaNimi> <mängija>*** 
 
*Kommentaarid:* omanikke saab alal olla vaid üks, kuid liikmeid saab olla mitu. Omanik saab muuta ala suurust, ala liikmeid, seda kustutada ja sinna sisealasid teha. Liikmed saavad alal normaalselt mängida, kuid ala muuta ei saa. 
 
**Ala kustutamine:** 
1. ***/ala kustuta <alaNimi>*** 
2. ***/ala kinnita*** 
