### Logické funkce a způsoby jejich vyjadřování

- **Logické funkce:** jsou matematické funkce, které vrací hodnotu TRUE (1) nebo FALSE (0) na základě logických operací s vstupy.

- **Základní logické operace:**
	- **AND (∧):** Výstup je TRUE, pouze pokud jsou všechny vstupy TRUE.
	- **OR (∨):** Výstup je TRUE, pokud je alespoň jeden vstup TRUE.
	- **NOT (¬):** Inverze vstupu, TRUE se stane FALSE a naopak.
	
- **Způsoby vyjadřování logických funkcí:**
	- **Algebraický tvar:** Použití logických operátorů, např. F=A∧B
	- **Pravdivostní tabulka:** Ukazuje výstupy pro všechny kombinace vstupů.
		![[./assets/Pasted image 20241108175323.jpg|Pasted image 20241108175323.jpg]]
	- **Vennovy diagramy:** Grafické znázornění vztahů mezi množinami.
		![[./assets/Pasted image 20241108175239.png|Pasted image 20241108175239.png]]
	- **Karnaughova mapa (K-map):** Používá se k minimalizaci logických funkcí.
		![[./assets/Pasted image 20241108175130.png|Pasted image 20241108175130.png]]
### Zákony Booleovy algebry
- **Co to je:** Booleovou algebrou, jakožto jednoduchým a přesným prostředkem, popisujeme logické obvody a navrhujeme je, když známe vstupní logickou funkci.

- **Proč?:** Booleova algebra je důležitý pomocník, který slouží k minimalizaci logických funkcí pomocí zákonů a pravidel. Ne vždy se nám podaří řešit úkol, kde se objevuje nějaká jednoduchá funkce.

Pracuje pouze se **3 operacemi** viz ==Základní logické operace== nahoře

### Karnaughova mapa (K-map)

Karnaughova mapa (K-map) je grafický nástroj používaný pro minimalizaci logických funkcí. Tento nástroj pomáhá snižovat počet logických operací (AND, OR, NOT) potřebných k realizaci dané funkce.

- **K čemu slouží:**
	- **Minimalizace logických funkcí**: Umožňuje jednoduché zjednodušení logických výrazů, což vede ke snížení počtu potřebných logických operací a komponent.
	- **Vizualizace logických funkcí**: Poskytuje grafické znázornění logických funkcí, což usnadňuje pochopení a analýzu jejich struktury.
	- **Optimalizace digitálních obvodů**: Pomáhá navrhovat efektivnější digitální obvody tím, že minimalizuje počet logických hradel a spojů.

#### Příklad minimalizace

Představme si logickou funkci se třemi vstupy **A**,**B**,**C**
A výstupem Výstup (**Q**).

##### Funkce:

| A   | B   | C   | Výstup (Q) |
| --- | --- | --- | ---------- |
| 0   | 0   | 0   | 0          |
| 0   | 0   | 1   | 1          |
| 0   | 1   | 0   | 1          |
| 0   | 1   | 1   | 1          |
| 1   | 0   | 0   | 0          |
| 1   | 0   | 1   | 1          |
| 1   | 1   | 0   | 1          |
| 1   | 1   | 1   | 0          |

##### K-map:
K-map má mřížku, která odpovídá všem možným kombinacím vstupních proměnných.

|     | BC=00 | BC=01 | BC=11 | BC=10 |
| --- | ----- | ----- | ----- | ----- |
| A=0 | 0     | 1     | 1     | 1     |
| A=1 | 0     | 1     | 0     | 1     |
Seskupování jedniček:
- Skupina 1 (A=0): buňky (0, 01), (0, 11), (0, 10)
- Skupina 2 (A=1): buňky (1, 01), (1, 10)

### Návrh kombinačního logického obvodu

...


