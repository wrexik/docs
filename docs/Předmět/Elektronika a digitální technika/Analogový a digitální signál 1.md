### 1. Grafické Vyjádření Analogového Signálu

Analogový signál je plynulý a může mít nekonečně mnoho hodnot v určitém rozsahu. Grafické znázornění analogového signálu vypadá jako spojitá křivka, která se mění v čase.

[![880Hz sine wave.png](https://upload.wikimedia.org/wikipedia/commons/thumb/b/bc/880Hz_sine_wave.png/400px-880Hz_sine_wave.png)](https://commons.wikimedia.org/wiki/File:880Hz_sine_wave.png "File:880Hz sine wave.png")

### 2. Druhy Zkreslení Analogového Signálu

Analogové signály mohou být zkresleny různými způsoby, například:

- **Harmonické zkreslení**: Způsobené nelinearitou zařízení, které generuje vyšší harmonické frekvence signálu (THD). Harmonická je frekvence, která je násobkem základní frekvence. V evropské napěťové síti je základní frekvence 50 Hz. Násobky této frekvence jsou harmonické, tedy 100 Hz, 150 Hz, 200 Hz
- **Intermodulační zkreslení**: Vzniká, když se v zařízení míchají dvě nebo více frekvencí, což vede ke vzniku dalších frekvencí, které nejsou v původním signálu.
- **Šum**: Náhodné variace signálu způsobené různými zdroji, jako jsou teplotní šumy, šumové napětí v obvodech apod.
- **Zkreslení fázového posunu**: Změny fáze signálu, které mohou způsobit jeho zpoždění nebo deformaci.
- **Amplitude Modulation (AM) zkreslení**: Změna amplitudy signálu kvůli nežádoucím vlivům.

### 3. Grafické Vyjádření Digitálního Signálu

Digitální signál je diskrétní a má omezený počet hodnot, obvykle dvě: 0 a 1. Grafické znázornění digitálního signálu se skládá z řady obdélníkových pulzů.

[![Digitální signál](https://upload.wikimedia.org/wikipedia/commons/thumb/9/9a/Digital.signal.svg/2560px-Digital.signal.svg.png)](https://commons.wikimedia.org/wiki/File:Digital.signal.svg "File:Digital.signal.svg")

### 4. Regenerace Digitálního Signálu

 Regenerace digitálního signálu se používá k obnově signálu na jeho původní kvalitu po přenosu, který mohl způsobit degradaci. Zahrnuje equalizaci, amplifikaci, restaurování hodin a **detekci a opravu chyb**. Proces regenerace zahrnuje:

- **Equalizace**: Kompenzace frekvenční odezvy přenosového kanálu.
- **Amplifikace**: Zvýšení úrovně signálu na potřebnou hodnotu.
- **Restaurování hodin**: Synchronizace signálu s časovou referencí.
- **Detekce a oprava chyb**: Identifikace a oprava chyb v signálu.

### 5. Zabezpečení proti Chybovosti při Přenosu a Ukládání

K zabezpečení digitálních signálů proti chybovosti se používají různé metody:

- **Redundantní kódování**: Přidání nadbytečných dat k signálu, které umožňují detekci a opravu chyb.
- **Kontrolní součty**: Výpočet kontrolních součtů pro detekci chyb (např. CRC - Cyclic Redundancy Check).
- **Paritní bity**: Přidání bitů, které indikují, zda počet jedniček v daném bloku dat je sudý nebo lichý.
- **Forward Error Correction (FEC)**: Metoda, která umožňuje detekci a opravu chyb přímo při přenosu bez nutnosti opakování.
- **Zálohování a replikace dat**: Ukládání kopií dat na různých místech pro ochranu před ztrátou nebo poškozením.

### Otázky

- **Grafické Vyjádření Analogového Signálu**
    
    - **Otázka:** Jaký je hlavní rozdíl mezi grafickým znázorněním analogového a digitálního signálu?
    
    - **Odpověď:** Analogový signál je plynulý a může mít nekonečně mnoho hodnot v určitém rozsahu, zatímco digitální signál je diskrétní a má omezený počet hodnot, obvykle dvě: 0 a 1.
- **Druhy Zkreslení Analogového Signálu**
    
    - **Otázka:** Popište harmonické zkreslení a uveďte, jak vzniká.

    - **Odpověď:** Harmonické zkreslení je způsobeno nelinearitou zařízení, které generuje vyšší harmonické frekvence signálu.
- **Grafické Vyjádření Digitálního Signálu**
    
    - **Otázka:** Jak vypadá grafické znázornění digitálního signálu a jaké hodnoty může nabývat?
    
    - **Odpověď:** Grafické znázornění digitálního signálu se skládá z řady obdélníkových pulzů a může nabývat hodnot 0 a 1.
- **Regenerace Digitálního Signálu**
    
    - **Otázka:** Jaký je účel regenerace digitálního signálu a jaké procesy zahrnuje?
    
    - **Odpověď:** Regenerace digitálního signálu se používá k obnově signálu na jeho původní kvalitu po přenosu, který mohl způsobit degradaci. Zahrnuje equalizaci, amplifikaci, restaurování hodin a detekci a opravu chyb.
- **Zabezpečení proti Chybovosti při Přenosu a Ukládání**
    
    - **Otázka:** Co je redundantní kódování a jak pomáhá při zabezpečení digitálních signálů?
    
    - **Odpověď:** Redundantní kódování přidává nadbytečná data k signálu, což umožňuje detekci a opravu chyb.
- **Druhy Zkreslení Analogového Signálu**
    
    - **Otázka:** Uveďte a popište tři různé druhy zkreslení, které mohou ovlivnit analogový signál.
    
    - **Odpověď:** Tři různé druhy zkreslení jsou:
        - Harmonické zkreslení: způsobené nelinearitou zařízení, generující vyšší harmonické frekvence signálu.
        - Intermodulační zkreslení: vzniká, když se v zařízení míchají dvě nebo více frekvencí, vedoucí ke vzniku dalších frekvencí.
        - Šum: náhodné variace signálu způsobené různými zdroji, jako jsou teplotní šumy nebo šumové napětí v obvodech.