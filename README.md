# Predavanja FMF

## O repozitoriju

V repozitoriju so zbrani zapiski s predavanj nekaterih predmetov iz časa mojega študija na Fakulteti za matematiko in fiziko Univerze v Ljubljani.
Nastajali so med predavanji, zato je možno, da vsebujejo kako napako. Popravki so vedno dobrodošli.

---

## Navodila za sestavljanje pdf datotek

Za stvarno kazalo uporabljam program `xindy`, ki samodejno uredi kazalo po slovenski abecedi. Za uporabo z `latexmk` uporabimo ukaz
```latexmk -pdf -e "$makeindex='texindy -L slovenian -C utf8';" <ime tex datoteke>```.

pdf datotek vam ni potrebno sestavljati lokalno - za vsako posodobljeno tex datoteko bo ob pull requestu github action preveril, ali mora
posodobiti še pdf, in ga v tem primeru samodejno dodal k pull requestu (skratka, pull requesti, v katerih so bile spremenjene le .tex
datoteke, so popolnoma sprejemljivi).

---

## Popravki

Na popravke lahko opozorite na več načinov. Lahko odprete nov Issue, pri čemer mi boste zelo olajšali delo, če dodate reference na vrstico kode,
v kateri je prišlo do napake. Preprosto kliknete številko vrstice, <kbd>•••</kbd>, nato pa `Reference in new issue`. Bolj izkušeni uporabniki
LaTeXa in Gita lahko popravek vnesete sami s pull requestom. Če vam nič od tega ne ustreza, mi lahko pošljete DM z napako.

---

## Citati

Na začetek vsakega novega poglavja dodam po en citat, ki ga ja nekdo izrekel med predavanji ali vajami v tistem delu. Predloge za citate zbiram v
posebnih tekstovnih datotekah. Za predlog novega citata ga lahko preprosto dodate v ustrezno datoteko, kar lahko naredite tudi na strani GitHub. Pri
tem upoštevajte naslednji format:

	"Priporočil bi vam, da vam internet ne pade."
	- prof. dr. Miran Černe, 7. 12. 2020

---

## Povezave

[Discord](https://discord.gg/BJcTTAVFWv)
