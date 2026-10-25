# UltraRITHA Family

**Real Intelligent Total Habitat Automation**: a growing ecosystem of controllers, smart probes and displays for aquarium and terrarium automation.

*Un unico ecosistema, infinite possibilità.*

Developed by **CreativaRita**.

---

## English

### What is UltraRITHA?

UltraRITHA is a family of ESP32-based control units for managing aquariums and terrariums, together with probes, displays and a common communication protocol. Every model shares the same ecosystem, so you can start small and grow.

### The family

| Model | What it is |
|---|---|
| **Simpla** | Entry-level controller (ESP32-C3): thermostat, 2-channel PWM lighting, real-time clock, built-in web app with OTA updates. No display. |
| **Basic** | Same as Simpla, plus a 1.3" monochrome OLED display. |
| **Basic+** | Basic evolution (ESP32-C3) adding pH measurement and dosing. In development. |
| **Pro** | Coming soon. |
| **Monster** | The big master unit (ESP32-S3) for complete installations, with large touch display. |
| **T-Rex** | Master unit (ESP32-S3) for terrariums and paludariums, with a compact colour display over RS485. |
| **UltraProbe** | Smart probe nodes (ESP32-C3) that connect to the master. |
| **UltraLink** | The RS485 communication protocol shared by the whole family. |

Some models are still in development: folders are filled as each release is ready.

### Repository structure

```
UltraRITHA-Family/
├── Simpla-Basic/   Simpla, Basic and Basic+
├── Pro/
├── Monster/
├── T-Rex/
└── UltraLink/      Protocol documentation
```

Each model folder contains:

- `Free/`: free files (documentation, pinouts, example firmware, schematics, when available)
- `README.md`: details and the link to the **paid files**

### Free and paid files

Free files are in this repository. **Paid files are not stored here**: they are obtained through the link in each model's `README.md`.

### License

Free files are released under the custom license in [LICENSE](LICENSE): free for personal, non-commercial use. Commercial use, resale and use of the brand require written permission.

### Safety

These projects interface with mains-powered equipment (heaters, pumps, lights). Work on mains voltage only if you are qualified to do so. Use everything at your own risk.

### Contact

Questions and suggestions: open an [Issue](../../issues).

---

## Italiano

### Cos'è UltraRITHA?

UltraRITHA è una famiglia di centraline basate su ESP32 per la gestione di acquari e terrari, con sonde, display e un protocollo di comunicazione comune. Tutti i modelli fanno parte dello stesso ecosistema: si può partire dal modello base e crescere nel tempo.

### La famiglia

| Modello | Descrizione |
|---|---|
| **Simpla** | Centralina entry-level (ESP32-C3): termostato, luci PWM a 2 canali, orologio RTC, web app integrata con aggiornamenti OTA. Senza display. |
| **Basic** | Come Simpla, con display OLED monocromatico da 1.3". |
| **Basic+** | Evoluzione di Basic (ESP32-C3) con misura del pH e dosaggio. In sviluppo. |
| **Pro** | In arrivo. |
| **Monster** | La centralina master più grande (ESP32-S3) per impianti completi, con display touch di grandi dimensioni. |
| **T-Rex** | Centralina master (ESP32-S3) per terrari e paludari, con display a colori compatto via RS485. |
| **UltraProbe** | Sonde intelligenti (ESP32-C3) collegate al master. |
| **UltraLink** | Il protocollo di comunicazione RS485 comune a tutta la famiglia. |

Alcuni modelli sono ancora in sviluppo: le cartelle vengono riempite man mano che le versioni sono pronte.

### Struttura del repository

Vedi la sezione inglese. Ogni cartella di modello contiene `Free/` (file gratuiti) e un `README.md` con i dettagli e il link ai **file a pagamento**.

### File gratuiti e a pagamento

I file gratuiti sono in questo repository. **I file a pagamento non sono qui**: si ottengono tramite il link indicato nel `README.md` di ciascun modello.

### Licenza

I file gratuiti sono rilasciati con la licenza personalizzata in [LICENSE](LICENSE): uso personale e non commerciale. Uso commerciale, rivendita e uso del marchio richiedono autorizzazione scritta.

### Sicurezza

Questi progetti interagiscono con apparecchiature alimentate a rete (riscaldatori, pompe, luci). Intervieni sulla tensione di rete solo se sei qualificato. Usa tutto a tuo rischio.

### Contatti

Domande e suggerimenti: apri una [Issue](../../issues).
