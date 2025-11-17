### :robot: Umíme.to Auto Solver
Automatický solver pro výukovou platformu Umíme.to s využitím AI. Řeší matematické a jazykové úlohy v reálném čase pomocí pokročilých modelů od Groq.

**:sparkles: Klíčové vlastnosti**
- Aktuální podpora pouze cvičení : Rozhodovačka
- Bez obou klíčů skript nevykonává žádné operace
- Oddělené ovládací prvky
- Hlavní tlačítko: Výhradně pro START/STOP auto-řešení
- Nastavovací tlačítko: Rychlý přístup ke konfiguraci klíčů

**:robot: AI Integrace**
- Llama 3.3 70B 
- Specializované prompty pro matematiku a jazykové úlohy
  
**:bar_chart: Monitoring**
- Statistiky vyřešených úloh s procentuální úspěšností
- Debug v F12 consoli (doporučno)

**:information_source: Info**
- AI není neomylné a často dělá chyby
- V případě že se script dostane do loopu, načtěte stránku znovu
- Script ke stažení naleznete v Releases

**:rocket: Požadavky Instalace** 
- Prohlížeč s podporou Violentmonkey

Postup: 
1. Nainstalujte extension pro správu userscriptů:
3. Violentmonkey 
4. Přidejte script do extension:
5. Otevřete dashboard Violentmonkey
6. Klikněte "+" pro nový script
7. Vložte obsah v6.4.16.js
8. Uložte (Ctrl+S)
9. Nastavte klíče (viz níže)
    
**:key: Konfigurace**
1. Získání Server Key (podání ticketu na https://dsc.gg/umt-solver)
2. Získání Groq Key
  - Vytvořte účet na https://console.groq.com
  - Přejděte na API Keys
  - Vytvořte nový klíč (začne gsk_)
3. Nastavení v browseru
Klikněte na :gear: (nastavovací tlačítko)
Zvolte:
:one: pro zadání Server Key
:two: pro zadání Groq Key
:three: pro kontrolu stavu
4. Po zadání klíčů proběhne automatická kontrola
Ujistěte se, že oba klíče jsou zelené :white_check_mark:

**:mobile_phone: Použití**
Spuštění automatického řešení
Klikněte na zelené tlačítko :robot:
Solver začne automaticky vyřešovat úlohy
Pro zastavení klikněte znovu (červené)

### Právní upozornění
**Tento script je určen pouze pro:**
- Vzdělávací účely
- Testování AI schopností
- Výzkumné účely
  
**NENÍ určeno pro:**
- Podvádění v testech
- Komercionalizaci
<img width="1625" height="793" alt="image" src="https://github.com/user-attachments/assets/6c44108f-8bb3-4dd5-b90d-86229160ff55" />

  
**Uživatel je zodpovědný za dodržování Terms of Service platformy Umíme.to a Groq.**

Pro bug reporty a feature requesty použijte GitHub Issues.
