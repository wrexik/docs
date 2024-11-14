### Diody a LED diody
#### Dioda
![[./assets/Pasted image 20241114190028.png|Pasted image 20241114190028.png]]
Součástka s nepatrným odporem při zapojení správným směrem. Pokud je však zapojena obráceně, proud nepropustí.

- **Druhy:**
  - P-N dioda
  - Zenerova dioda
  - Schottky dioda

- **Použití:**
  - Usměrňování proudu
  - Ochrana obvodů (ochrana proti přepětí)
  - Regulace napětí (Zenerova dioda)

#### LED dioda
![[./assets/Pasted image 20241114195751.png|Pasted image 20241114195751.png]]
LED dioda při správném zapojení do obvodu emituje světlo, nefunguje však, když je zapojena naopak.

- **Použití:**
  - Osvětlení (dekorační, signalizační)
  - Indikace (stav zařízení, upozornění)
  - Displeje (např. displeje hodinek nebo elektronických zařízení)

### Bipolární tranzistory NPN a PNP 
![[./assets/Pasted image 20241114202159.jpg|Pasted image 20241114202159.jpg]]
#### Tranzistory NPN 
![[./assets/Pasted image 20241114200736.png|Pasted image 20241114200736.png]]Tranzistor typu NPN je tvořen třemi vrstvami: N (negativní), P (pozitivní) a N (negativní). V tomto typu tranzistoru proud protéká od kolektoru k emitoru při zapojení v aktivním režimu. 

- **Pracovní princip:** 
	- Při zapojení do obvodu je na bázi kladné napětí vůči emitoru, což umožňuje průchod proudu z kolektoru na emitor. 
	- **Použití:**
		- Spínače (v obvodech pro přepínání) 
		- Zesilovače (pro zesílení signálů) - Řízení výkonu (v regulačních obvodech) 
#### Tranzistory PNP 
![[./assets/Pasted image 20241114200731.png|Pasted image 20241114200731.png]] Tranzistor typu PNP má opačnou strukturu než NPN, s vrstvami P (pozitivní), N (negativní) a P (pozitivní). U tohoto typu tranzistoru proud protéká od emitoru k kolektoru při zapojení v aktivním režimu. 

- **Pracovní princip:** 
	- Na bázi je záporné napětí vůči emitoru, což umožňuje proudění proudu z emitora do kolektoru. 
- **Použití:** 
	- Spínače (pro řízení záporných napětí) 
	- Zesilovače (pro aplikace vyžadující záporné napětí) 
	- Invertory (pro změnu polarity signálu)

### Bipolární Tranzistory FET, MOSFET 

- **Dají se použít jako:** 
	- Zesilovače 
	- Spínače 
	- Logická součástka
	
#### MOSFET
![[./assets/Pasted image 20241114213924.png|Pasted image 20241114213924.png]]MOSFET (Metal-Oxide-Semiconductor Field-Effect Transistor) je nejrozšířenější druh tranzistorů řízených elektrickým polem, u nichž je vodivost kanálu mezi elektrodami Source (S) a Drain (D) řízena napětím mezi elektrodou Gate (G). - 

**Výhody:** 
	- Velmi vysoká vstupní impedance 
	- Rychlé přepínací časy 
	- Ideální pro digitální a výkonové aplikace 
- **Rozdíly:** 
	- Vyšší odolnost vůči teplotním změnám ve srovnání s JFET 
	- Možnost dosažení vyšší frekvence přepínání
	
#### FET (Field-Effect Transistor)

![[../../../Pasted image 20241114222006.png|Pasted image 20241114222006]]

FET (Field-Effect Transistor) je druh tranzistoru řízeného elektrickým polem, kde je vodivost kanálu mezi elektrodami **Source (S)** a **Drain (D)** řízena napětím mezi **Gate (G)** a **Source (S)**.

- Výhody:
	- Vysoká vstupní impedance
	- Nízký šum
	- Vhodný pro analogové obvody a zesilovače

- **Rozdíly:**
	- **JFET** má nižší přepínací rychlost ve srovnání s **MOSFET**
	- **JFET** vykazuje vyšší šum při vyšších frekvencích oproti **MOSFET**


### Tranzistor - Základní Zapojení

#### Tranzistor jako Zesilovač
Tranzistor může fungovat jako zesilovač, když je nastaven do **aktivního režimu**. To znamená, že malý vstupní signál na **gate** způsobí větší změnu proudu mezi **drain** a **source**, což vede k zesílení signálu.

- **MOSFET**: Zapojení s **source** nebo **drain** umožňuje zesílení napětí.

#### Tranzistor jako Spínač
Tranzistor může fungovat jako **spínač**, když je přepnut mezi dvěma stavy: **zaporu** (off) nebo **sepnutý** (on).

- **MOSFET**: Když je **gate** napájen, tranzistor se sepne a umožní průchod proudu mezi **drain** a **source**.

Tranzistor v režimu spínače je efektivní pro řízení elektrických zařízení nebo pro vytváření logických funkcí.

