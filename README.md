# Laserski mikrofon
Ko slišimo za laserski mikrofon, pogosto pomislimo na _tajne agente_ in _high-tech_ prisluškovalne naprave. Le te so navadno težko dostopna stvar, a laserski mikrofon ne spada v to kategorijo. Sestavimo ga lahko na vsaki mizi s spajkalnikom in osnovnimi elektronskimi komponentami.

![alt text](slike/uvod.png "Postavljen sistem laserskega mikrofona")

##Kako deluje?
Najbolj očitna komponenta, ki jo potrebujemo, je **laser**. Tega bomo usmerili proti oddaljenemu objektu, ki je dober **odbojnik** svetlobe (zrcalo, okno, steklo na stenski sliki, ...) tako, da odbije laserski žarek nazaj v naš **dekoder**, ki svetlobo dekodira v zvok.
Zvok, ki nastaja v bližini odbojnika, povzroči, da odbojnik rahlo vibrira, kar opazimo kot majhne spremembe pozicije odbitega laserskega žarka. Takšne spremembe pomenijo nihanje količine svetlobe v neki točki. Če na to točko postavimo prej omenjeni dekoder, bomo slišali zvok.
![alt text](http://www.detective-store.com/5721-thickbox_default/laser-listening-device-spectra-laser-microphone-m.jpg "Shema postavitve")


## Dekoder
Za gradnjo potrebujemo naslednje dele:
- upori:
   * 1 kΩ
   * 10 kΩ
- kondenzatorji:
   * 0.01 μF
   * 10 μF
   * 470 μF
- potenciometer: 50 ali 100 kΩ
- fototranzistor: katerikoli NPN s prozornnim ohišjem
- integrirani ojačevalec: LM386
- banana za slušalke
- 9V baterija
- stikalo

## Odbojnik

## Laser

## Stojalo
POSTAVITEV!

## Audacity
Prikaži Peak
Predvajaj zvok pred snemanjem
Filtri

##Težave

######V nadeljevanju:
Zakaj fototranzistor namesto fotoupora?

Zakaj baterija namesto adapterja?

direkten izhod na zvočnik ne bo dal pravih rezultatov, priklopi na računalnik

drama z ojačevalcem in novim vezjem
 
jakost laserja + odboj na steklu/cdju/zrcalni membrani

kaj je to + uvod: za kaj je primeren, za kaj ni. kaj vse je treba upoštevati pri vzpostavitviji sistema