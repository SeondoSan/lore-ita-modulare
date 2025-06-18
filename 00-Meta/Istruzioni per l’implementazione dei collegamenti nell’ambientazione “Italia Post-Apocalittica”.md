# Istruzioni per l'implementazione dei collegamenti nell'ambientazione "Italia Post-Apocalittica"

## Principi generali

1. **Approccio modulare**: Implementare i collegamenti un modulo alla volta, partendo dal modulo 02-Storia.
2. **Prioritizzazione**: Seguire la priorità indicata nei piani di implementazione (collegamenti di primo livello, secondo livello, terzo livello).
3. **Selezione strategica**: Per termini con molte occorrenze, collegare solo le occorrenze più significative (prima menzione in una sezione, definizioni, punti chiave).
4. **Verifica dei percorsi**: Assicurarsi che tutti i percorsi relativi siano corretti e funzionanti.
5. **Documentazione**: Tracciare i progressi aggiornando il piano di implementazione e il changelog.

## Procedura operativa

### Fase 1: Preparazione
1. Caricare il file da modificare
2. Caricare il piano di implementazione corrispondente
3. Identificare tutti i collegamenti da implementare

### Fase 2: Implementazione
1. Creare le ancore HTML necessarie con `<a id="nome-ancora"></a>` prima dei titoli delle sezioni rilevanti
2. Implementare i collegamenti utilizzando la sintassi `[Testo visualizzato](percorso-relativo#ancora)` 
3. Per percorsi all'interno dello stesso file, usare `[Testo](#ancora)`
4. Per percorsi verso altri moduli, usare `[Testo](../XX-modulo/XX.Y-file.md#ancora)`

### Fase 3: Verifica
1. Controllare che tutti i collegamenti siano stati implementati correttamente
2. Verificare che i percorsi relativi siano corretti
3. Assicurarsi che le ancore HTML esistano nei file di destinazione

## Implementazione per Modulo 02-Storia

### File 02.0-situazione-prebellica-panoramica.md
- Implementare 9 collegamenti prioritari verso concetti fondamentali
- Collegamenti principali: Progetto MegalopolIT, Guerra Euro-Mediorientale, Vault, aziende armiere

### File 02.1-nuova-italia.md
- Creare ancora HTML per il Progetto MegalopolIT
- Implementare collegamenti selettivi al Progetto MegalopolIT (2-3 occorrenze chiave)
- Collegare Napoli e la Rete dei canali

### File 02.2-decennio-buio.md
- Creare ancore HTML per Guerra Euro-Mediorientale e Crisi energetica
- Implementare collegamenti autorefenziali a queste ancore
- Collegare tecnologie di fusione nucleare

### File 02.3-italia-militare.md
- Creare 6 ancore HTML per concetti chiave
- Implementare collegamenti autorefenziali per Rinascimento Militare e aziende
- Collegare Muraglia Alpina, Vault e tecnologie di controllo mentale

### File 02.4-tensioni-finali.md
- Collegare Commonwealth Europeo, Vault-Tec, società di rifugi
- Implementare collegamenti alle tecnologie di controllo mentale
- Collegare Protocollo Tripartito

## Implementazione per Modulo 03-Geografia
(Seguirà dopo completamento del Modulo 02)

### File 03.0-geografia-panoramica.md
- Collegamenti a regioni geografiche principali (Rete dei Navigli, Zona Morta di Roma, ecc.)
- Collegamenti alle fazioni principali (Lega dei Navigli, Fratellanza Alpina, ecc.)

### File 03.1-morfologia-generale.md
- Collegamenti alle principali formazioni geografiche
- Collegamenti a regioni specifiche

### File 03.2-grande-guerra.md
- Collegamenti a zone di impatto e livelli di contaminazione
- Collegamenti ai sopravvissuti dei Vault

### File 03.3-regioni-nord.md
- Collegamenti alle creature che abitano le regioni (Gondolieri)
- Collegamenti alle fazioni che controllano il territorio (Lega dei Navigli, ecc.)

### File 03.4-regioni-centro.md
- Collegamenti alla Zona Morta di Roma e altre formazioni
- Collegamenti alle creature e fazioni della regione

### File 03.5-regioni-sud.md
- Collegamenti all'Arcipelago Campano
- Collegamenti alle Famiglie che controllano la regione

## Nota sulla creazione di ancore HTML

Le ancore HTML devono essere inserite immediatamente prima del titolo della sezione di riferimento, senza spazi tra l'ancora e il titolo. Esempio:

```markdown
<a id="guerra-euro-mediorientale-2052"></a>
## La Guerra Euro-Mediorientale (2052-2060)
```

## Tracciamento dei progressi

Per ogni file completato:
1. Contrassegnare nel piano di implementazione con ✅
2. Documentare nel changelog: `[MOD] Implementati collegamenti in XX.Y-nome-file.md`
3. Aggiungere nota sui collegamenti bidirezionali che dovranno essere implementati in altri moduli

---

Questo documento di istruzioni sarà utilizzato come riferimento per tutte le future sessioni di implementazione dei collegamenti, garantendo un approccio coerente e sistematico.