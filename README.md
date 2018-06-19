# Magical-theory
Magical theory je súbor vypracovaných štátnicových otázok k štúdiu Experimentálnej a časticovej fyziky na FJFI ČVUT. Nájdeš tu spracované otázky k predmetom Subatómová fyzika, Experimentálne metódy jadrovej a subjadrovej fyziky a Jadrová spektroskopia. 

## Ako prispieť?
V prípade, že by si chcel prispieť do tohto diela, tu nájdeš návod ako na to. V prvom rade si stiahni zdrojové súbory, a to tak, že v prázdnom priečinku zadáš príkazy
```git clone https://github.com/jakubcimerman/Magical-theory.git```

Celá zložka sa ti stiahne do počítača. Ak sa chystáš niečo upraviť, najskôr si vytvor nový **branch**. To urobíš príkazom
```git checkout -b [name_of_your_branch]```
Názov branchu je dobré voliť štýlom `your_name/co_sa_chystas_zmenit`. 

Následne môžeš ľubovoľne upravovať súbory. Nezabudni však vždy predtým, ako začneš nejaký súbor upravovať, že si musíš updatovať aktuálnu verziu súborov, a to jednoducho príkazom
```git pull origin master```
Keď zmeny dokončíš, skontroluj si, ktoré súbory si zmenil príkazom
```git status```

Potom vytvor **commit** príkazmi
```git add . ``` alebo ``` git add [path_to_file]```
```git commit -m "Your message" ```
Do správy jednoducho zhrň jednou vetou, aké zmeny sa nachádzajú v danom commite. 

Následne môžeš svoje zmeny uploadovať príkazom
```git push origin [name_of_your_branch]```
Keď máš zmeny nahraté, môžeš vytvoriť `pull request` (najlepšie cez stránku github.com) a tým spraviť návrh na mergenutie tvojich zmien do master branch.

## Pravidlá pri písaní dokumentu
Dokument je písaný česko-slovensky (ideálne je nemiešať tieto dva jazyky v rámci jednej kapitoly). Všetky obrázky sa nachádzajú v priečinku `images`.

## Kontakt
V prípade akýchkoľvek otázok ma kontaktuj na `jakub.cimerman(at)gmail.com`