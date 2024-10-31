### Desítková soustava

Neboli dekadická soustava
- **Poziční soustava se základem 10:** Pro zápis se používají číslice 0, 1, 2, 3, 4, 5, 6, 7, 8, 9. Desítková soustava umožnuje přesný zápis libovolného celého čísla.
- **Záporné hodnoty:** Jsou označena na začátku znakem "-" (mínus).
- **Desetinné číslo:** Pomocí desetinné značky "," nebo "." lze zapsat libovolné reálné číslo s jakoukoli konečnou přesností.
### Dvojková soustava

Neboli binární soustava
- **Používá pouze dvě číslice:** 0, 1.
- **Používá se převážně v:** moderních digitálních počítačích neboť 0 nebo 1 odpovídají jednouchým stavům. (Vypnuto / Zapnuto).

### Šestnáctková soustava

Neboli hexadecimální soustava
- **Ne jen čísla:** Skládá se z čísel 0, 1, 2, 3, 4, 5, 6, 7, 8 a 9 a písmen A, B, C, D, E a F.
- **Hodnoty:** Písmena A - F reprezentují čísla s hodnotou 10 až 15. 
	- Např. 3F716 reprezentuje hodnotu, které v [[Číselné soustavy 2#Desítková soustava|Desítková soustava]] odpovídá číslu 3×162 + 15×161 + 7×160 = 1015.
- **Použití:** V IT pro zápis adresy paměti a určení barev v RGB.

### Vzájemné převody

- **Z desítkové do dvojkové:** Postupným dělením čísla 2 a zapisováním zbytků z těchto dělení odzadu.
    - Např. 10₁₀ = 1010₂
- **Z dvojkové do desítkové:** Součet mocnin dvojky s váhami odpovídajícími pozicím jedniček.
    - Např. 1010₂ = 1×2³ + 0×2² + 1×2¹ + 0×2⁰ = 10₁₀
- **Z desítkové do šestnáctkové:** Postupným dělením čísla 16 a zapisováním zbytků z těchto dělení odzadu.
    - Např. 255₁₀ = FF₁₆
- **Ze šestnáctkové do desítkové:** Součet mocnin šestnáctky s váhami odpovídajícími hodnotám číslic.
    - Např. 1A₁₆ = 1×16¹ + 10×16⁰ = 26₁₀


### Základní logické funkce (NOT, AND, OR)

Logické funkce jsou základními stavebními kameny digitálních obvodů a počítačové logiky. Zde jsou tři základní logické funkce:

## NOT (Negace)

- **Definice:** Negace je logická operace, která obrátí hodnotu svého vstupu.
- **Pravdivostní tabulka:**
![[./assets/Pasted image 20241031181620.png|Pasted image 20241031181620.png]]
- **Příklad:** Pokud je vstup A = 1, výstup NOT A bude 0.

## AND (Konkunkce)

- **Definice:** Konjunkce je logická operace, která má výstup 1 pouze tehdy, pokud jsou **oba vstupy 1.**
- **Pravdivostní tabulka:**
![[./assets/Pasted image 20241031181712.png|Pasted image 20241031181712.png]]
- **Příklad:** Pokud jsou vstupy A = 1 a B = 1, výstup A AND B bude 1.

## OR (Disjunkce)

- **Definice:** Disjunkce je logická operace, která má výstup 1, pokud je **alespoň jeden ze vstupů 1.**
- **Pravdivostní tabulka:**
![[./assets/Pasted image 20241031181732.png|Pasted image 20241031181732.png]]
- **Příklad:** Pokud jsou vstupy A = 1 a B = 0, výstup A OR B bude 1.


