![IP5306 charger](https://github.com/LaskaKit/IP5306-Charger/blob/main/img/2.jpg)

# IP5306 charger - boost měnič a nabíječka li-ion/li-po baterie v jednom
Hledáš vhodný nabíjecí modul pro tvou Li-Polku, který by zároveň měl i napájecí výstup pro tvoje zařízení? Tak to seš na správné stránce - představujeme ti náš IP5306 Charger.
Deska IP5306 Charger umí jak nabít tvou li-ionku/li-polku, tak obsahuje i step-up (boost) s výstupním napětím 5V a dokáže dodat proud až 2,4A do zátěže.
Jedním stiskem tlačítka zapneš výstup, dvojitým stiskem zase vypneš.

Vstupní napětí se může pohybovat v rozmezí 4,5 - 5,5V a maximální nabíjecí proud může být až 2,1A. Čip IP5306 umí sám ochránit akumulátor před podvybitím, přebitím i nadproudem.
Obvod zároveň obsahuje i inteligentní detekci připojeného zařízení. Pokud výstupní proud klesne pod 50 mA, výstup se automaticky vypne.

IP5306 má velmi vysokou účinnost jak v nabíjení, tak i v boost režimu. V obou případech hodně nad 90%.

## Vybíjení
Kapacita | #1 LED | #2 LED | #3 LED | #4 LED
--- | --- | --- | --- |---
C >= 75% | svítí | svítí | svítí | svítí
50% <= C < 75% | svítí | svítí | svítí | -
25% <= C < 50% | svítí | svítí | - | -
3% <= C < 25% | svítí | - | - | -
0% <= C 3% | bliká (1,5 Hz) | - | - | -

# Nabíjení
Kapacita | #1 LED | #2 LED | #3 LED | #4 LED
--- | --- | --- | --- |---
100% nabito | svítí | svítí | svítí | svítí
 C >= 75 % | svítí | svítí | svítí | bliká (1,5 Hz)
50% <= C < 75% | svítí | svítí | bliká (1,5 Hz) | -
25% <= C < 50% | svítí | bliká (1,5 Hz) | - | -
<25% | bliká (1,5 Hz) | - | - | -

Vlastní spotřeba desky je pouhých 50 uA.

Modul najdeš na e-shopu https://www.laskarduino.cz/laskakit-nabijecka-li-ion-clanku-boost-ip5306-5v-2-1a/

![IP5306 charger](https://github.com/LaskaKit/IP5306-Charger/blob/main/img/1.jpg)
