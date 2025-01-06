CSMA/CD  
5, 6 vrstva  
Tx vs fx / sx

# Tree topologie
Hierarchická topologie, kde uzly jsou uspořádány do stromové struktury.  
- Každý uzel (kromě kořenového) má jednoho rodiče a může mít více dětí.  
- Využívá se například v hierarchických sítích pro organizaci dat nebo zařízení.  

# Fx vs SX
Je rozdíl spektra LEDky která posílá světlo do kabelu, Sx na kratší vzdálenost právě kvůli spektru.

## TX vs FX vs SX
- **Tx**: twisted pairs, používá klasické kabely.  
- **Fx**: optická vlákna, používá optiku.  
- **Sx**: optická vlákna, stejný jako Fx, jen na **kratší vzdálenost** kvůli spektru světla.

# 1000Base-T
- Technologie pro gigabitový Ethernet.  
- Využívá **kroucené páry (twisted pairs)** kategorie 5e nebo vyšší.  
- Maximální délka kabelu: **100 metrů**.  
- Přenosová rychlost: **1 Gbit/s**.  

# 7. vrstva OSI - Aplikační vrstva
- Poskytuje síťové služby přímo aplikacím uživatele (např. HTTP, FTP, SMTP).  
- Zajišťuje komunikaci mezi softwarem a síťovými službami.

# 6. vrstva OSI - Prezentační vrstva
- Transformuje data do formátu, který je čitelný cílovým systémem.  
- Zajišťuje kódování, šifrování a kompresi dat.

# 5. vrstva OSI - Relační vrstva
- Udržuje a spravuje spojení mezi zařízeními.  
- Rozhoduje o režimu spojení:  
  - **Poloduplexní**: zařízení se střídají v příjmu a vysílání.  
  - **Plně duplexní**: zařízení komunikují současně.  

# NEXT
**Near End Cross Talk**  
Vyjadřuje nežádoucí pronikání signálů z jednoho páru do sousedících párů na stejném konci.

# FEXT
**Far End Cross Talk**  
Vyjadřuje nežádoucí pronikání signálů do jednoho páru a měří se na opačném konci na všech ostatních.

# CSMA/CD
**Carrier Sense Multiple Access with Collision Detection**  
- Stanice na síti naslouchají, zda je médium volné.  
- Pokud je volné, rámec odešlou.  
- Pokud dojde ke kolizi (dva rámce odeslány současně), stanice čekají náhodnou dobu a poté zkusí odeslání znovu.
