# IT-Tuki ja Kyberturvallisuus Työkalut (IT Support & Cybersecurity Tools)

Tämä arkisto sisältää Pythonilla kehitettyjä työkaluja järjestelmänhallintaan ja tietoturvaan. Projektit on suunniteltu automatisoimaan rutiinitehtäviä ja parantamaan tietoturvaa.

## Sisältö (Projects)

### 1. Automaattinen Varmuuskopiointi (Järjestelmätuki)
Tämä työkalu on suunniteltu varmistamaan tietojen eheys (Data Integrity) ja saatavuus.
- **Tiedosto:** `varmuuskopiointi.py`
- **Toiminta:** Luo aikaleimalla varustetun varmuuskopion tärkeästä tiedostosta "Varmuuskopiot"-kansioon.
- **Käyttö:** Suorita kaksoisnapsauttamalla `kaynnista_varmuuskopiointi.bat`.

### 2. Vahva Salasana Generaattori (Kyberturvallisuus)
Tämä työkalu perustuu korkean entropian periaatteeseen brute-force-hyökkäyksiä vastaan.
- **Tiedosto:** `salasana_generaattori.py`
- **Toiminta:** Luo satunnaisia, vahvoja salasanoja (sisältää kirjaimia, numeroita ja erikoismerkkejä) NIST-suositusten mukaisesti.
- **Käyttö:** Suorita kaksoisnapsauttamalla `kaynnista_generaattori.bat`.

## Vaatimukset (Requirements)
- Python 3.x on oltava asennettuna järjestelmään.
- Skriptit toimivat suoraan Windows-ympäristössä `.bat`-tiedostojen avulla.
