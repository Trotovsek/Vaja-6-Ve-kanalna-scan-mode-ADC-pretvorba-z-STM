# Vaja-6-Ve-kanalna-scan-mode-ADC-pretvorba-z-STM
c) Glede na vašo razvojno ploščico in razširitveno vezje z tipkami ter
potenciometri, izberite ustrezni analogni vhod, na katerem je vezan
potenciometer. Kateri pin je to? PC0
d) Določite in aktivirajte še dva analogna vhoda za zunanja potenciometra. To
bosta pina PC1 in PC2 .
Izbrani pini naj bodo vsi v isti grupi/skupini! Katera skupina je to? ADC.
g) Glede na uporabljene potenciometre izberite-obkljukajte ustrezni kanal/pin. Na zaslonu se vam mora
usterzno pobarvati izbrani pin v zeleno barvo. Kaj se izpiše poleg pinov? ADC_IN10, ADC_IN11 in
ADC_IN12.
i) V Configuration kliknemo ADC gumb. V Parameter settings izberite ločljivost pretvorbe na 8-bitno, torej
je območje vrednosti od 0 ÷ 255. Clock Prescaler nastavite tako, da bo izračunana frekvenca vzorčenja 4
MHz. Koliko bo izbrana vrednost parametra? Synchronous clock divided by 4.
k) Ustrezno spremenite vrednost paramtera Number of Conversion, ki bo znašal (ni možno) .
l) Čas vzorčenja Sampling Time izberite 239.5 cikla. Koliko je čas vzorčenja v mikro sekundah?
126.
m) V zavihku DMA Settings kliknite Add in v nastalem polju »select« izberite možnost ADC. Dolžina podatka
pretvorbe bo 1 Byte, zato ustrezno popravite izbirno polje Data Width?: byte
d) Kaj pomeni kratica DMA? Direct memory access.


Pri k) ni bilo možno izbrati Number of Conversion. potrebno je bilo tudi odadti potenciometer, na katerega smo pricinli žice in ga povezali na ploščo.
