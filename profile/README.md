<div align="center">

# Entherogen Audio

**Plugin audio psichedelici per mental core, industrial, acid e psytrance.**
*Psychedelic audio plugins: instruments and effects that bend perception.*

`VST3` · `AU` · `Standalone` &nbsp;|&nbsp; JUCE 8 · C++17 · interfaccia WebGL

</div>

---

## Cosa facciamo

Strumenti ed effetti pensati come esperienze, non come utility. Ogni plugin prende il nome da una
sostanza o da un'allucinazione e ne traduce l'effetto in DSP: il suono non viene solo colorato, viene
**falsificato, sciolto, deformato**. Hanno tutti un gesto principale, pochi controlli con nomi a tema e
un'interfaccia WebGL condivisa (`enterogen-ui`).

## Il catalogo

### Strumenti

| Plugin | Cos'è |
|---|---|
| **L5D-303** | Synth acid monofonico con sequencer *Blotter*. Il basso della TB-303 (scala a diodi, squelch, accent, slide) incontra la sezione sporca del Wasp (sync, ring, filtro CMOS). |
| **mu5hroom** | Synth FM a 4 operatori per i suoni alieni della psytrance high-tech: blip e bolle risonanti, zap, arpeggi gorgoglianti, bassline rolling. |
| **1b0gaine** | Generatore di droni modali metallici: un enorme corpo di metallo tenuto in vibrazione, inarmonico, con grana di lamiera e sub profondo. |

### Effetti

| Plugin | Cos'è |
|---|---|
| **Str4m0nio** | Effetto deliriante ispirato allo stramonio: aggiunge al suono allucinazioni credibili, come sussurri nel rumore, melodie fantasma, echi che anticipano il suono reale. |
| **4-HO-M3T** | Effetto di scioglimento: il suono esce spalmato e liquido, con scie che colano di intonazione, gocce e filtri che respirano. |
| **5-M30-DMT** | Drum mangler per breakcore e speedcore: taglia, ripete e inverte i colpi fino al *Breakthrough*, uno stutter che accelera ed esplode in un white-out. |

## Sotto il cofano

- **JUCE 8**, C++17, build con CMake su macOS (Windows e Linux dove indicato nei singoli repo)
- Test di rendering offline: niente NaN, niente clipping, niente clic; validazione con *pluginval*
- Nessuna allocazione né lock nel thread audio; latenza dichiarata all'host
- UI web (TypeScript, Vite, WebGL2) incorporata nel plugin

## Contatti

Account GitHub dell'organizzazione: [@Entherogen-Audio](https://github.com/Entherogen-Audio)

<sub>Dal catalogo alla pista: usali con giudizio.</sub>
