# Come Contribuire

Grazie per il tuo interesse nel contribuire a questo progetto! 🎉

Questo documento fornisce linee guida per contribuire al repository **opensource-contributors** del Linux Day UniMe 2025.

## 🎯 Tipi di Contributi

Accettiamo diversi tipi di contributi:

### 1. Aggiungere il tuo profilo contributor
Il contributo principale! Segui le istruzioni nel [README](README.md) per aggiungere il tuo profilo.

### 2. Migliorare la documentazione
- Correggere errori di battitura
- Migliorare le spiegazioni
- Aggiungere esempi
- Tradurre contenuti

### 3. Segnalare bug o problemi
- Usa le [GitHub Issues](https://github.com/linux-day-unime-2025/opensource-contributors/issues)
- Descrivi il problema in dettaglio
- Includi steps per riprodurlo

### 4. Proporre miglioramenti
- Apri una Issue con label `enhancement`
- Spiega chiaramente il beneficio
- Discuti con la community

## 🚀 Processo di Contribuzione

### Passo 1: Fork e Clone

```bash
# Fork del repository su GitHub, poi:
git clone https://github.com/TUO-USERNAME/opensource-contributors.git
cd opensource-contributors
```

### Passo 2: Crea un Branch

```bash
git checkout -b tipo/breve-descrizione
```

Tipi di branch:
- `feature/nome-feature` - nuove funzionalità
- `fix/nome-fix` - correzioni di bug
- `docs/nome-modifica` - modifiche alla documentazione
- `add-contributor-NOME` - aggiunta profilo contributor

### Passo 3: Fai le tue modifiche

- Segui le convenzioni di stile del progetto
- Scrivi messaggi di commit chiari
- Testa le tue modifiche

### Passo 4: Commit

```bash
git add .
git commit -m "tipo: Descrizione breve delle modifiche"
```

Convenzioni per i commit:
- `feat:` - nuova funzionalità
- `fix:` - correzione bug
- `docs:` - modifiche documentazione
- `style:` - formattazione, senza modifiche al codice
- `refactor:` - refactoring del codice
- `test:` - aggiunta o modifica test
- `chore:` - manutenzione generale

Esempi:
```
feat: Add contributor profile for Mario Rossi
docs: Update FAQ section with SSH troubleshooting
fix: Correct typo in contributing guidelines
```

### Passo 5: Push

```bash
git push origin tipo/breve-descrizione
```

### Passo 6: Pull Request

1. Vai sul tuo fork su GitHub
2. Clicca "Compare & pull request"
3. Compila il template della PR:
   - Titolo chiaro e descrittivo
   - Descrizione dettagliata delle modifiche
   - Riferimenti a Issue correlate (se applicabile)
4. Aspetta la review!

## 📋 Template Pull Request

```markdown
## Descrizione
Breve descrizione delle modifiche apportate.

## Tipo di modifica
- [ ] Aggiunta profilo contributor
- [ ] Bug fix
- [ ] Nuova funzionalità
- [ ] Modifica documentazione
- [ ] Altro (specifica): 

## Checklist
- [ ] Il mio codice segue le convenzioni di stile del progetto
- [ ] Ho verificato il mio codice (self-review)
- [ ] Ho commentato il codice, specialmente nelle parti complesse
- [ ] Ho aggiornato la documentazione di conseguenza
- [ ] Le mie modifiche non generano nuovi warning
- [ ] Ho testato le mie modifiche

## Issue correlate
Closes #(numero issue)
```

## 🎨 Linee Guida per i Profili Contributor

### Struttura del file

File: `contributors/TUONOME.md`

```markdown
# Nome Cognome

## 👋 Chi sono
2-3 righe di presentazione.

## 💡 Perché sono qui
Motivazione per l'interesse nell'open source.

## 🛠️ Competenze
- Skill 1
- Skill 2
- Skill 3

## 📫 Contatti
- GitHub: [@username](https://github.com/username)
- Email: email@example.com (opzionale)
```

### Best Practices

✅ **Fai:**
- Usa il tuo vero nome o username GitHub
- Mantieni il contenuto professionale
- Sii autentico e sincero
- Usa link funzionanti

❌ **Evita:**
- Informazioni sensibili (numeri di telefono, indirizzi)
- Linguaggio offensivo
- Contenuti inappropriati
- Link spam o promozionali

## 🔍 Code Review

### Come reviewer
Se hai permessi di review:

- Sii rispettoso e costruttivo
- Spiega il "perché" dei tuoi commenti
- Suggerisci soluzioni, non solo problemi
- Approva quando soddisfatto

### Come contributor
Se ricevi feedback:

- Non prenderla sul personale
- Chiedi chiarimenti se necessario
- Fai le modifiche richieste
- Ringrazia per il feedback!

## 🐛 Segnalare Bug

Quando segnali un bug, includi:

1. **Descrizione chiara** del problema
2. **Steps per riprodurre** il bug
3. **Comportamento atteso** vs **comportamento attuale**
4. **Screenshot** (se applicabile)
5. **Ambiente**: OS, browser, versione Git, etc.

Template:
```markdown
## 🐛 Bug Report

### Descrizione
[Cosa non funziona]

### Steps per riprodurre
1. Vai a...
2. Clicca su...
3. Vedi errore...

### Comportamento atteso
[Cosa dovrebbe succedere]

### Comportamento attuale
[Cosa succede invece]

### Ambiente
- OS: [es. Windows 10]
- Git version: [es. 2.42.0]
- Browser: [es. Chrome 120]
```

## ✨ Proporre Miglioramenti

Per proporre un miglioramento:

1. Apri una [Issue](https://github.com/linux-day-unime-2025/opensource-contributors/issues)
2. Usa label `enhancement`
3. Descrivi chiaramente il miglioramento
4. Spiega i benefici
5. Proponi un'implementazione (se possibile)

Template:
```markdown
## 💡 Proposta di Miglioramento

### Descrizione
[Cosa vuoi migliorare]

### Problema attuale
[Qual è la limitazione o il problema]

### Soluzione proposta
[Come risolverlo]

### Alternative considerate
[Altre possibili soluzioni]

### Benefici
- Beneficio 1
- Beneficio 2
```

## 📞 Ottenere Aiuto

Se hai bisogno di aiuto:

- 📚 Leggi il [README](README.md) e la documentazione
- 🔍 Cerca nelle [Issues](https://github.com/linux-day-unime-2025/opensource-contributors/issues) esistenti
- 💬 Apri una nuova Issue con label `question`
- 🙋 Chiedi durante il workshop

## 🙏 Riconoscimenti

Tutti i contributor saranno automaticamente aggiunti alla lista dei contributor del progetto!

Ogni contributo, grande o piccolo, è prezioso. Grazie per essere parte della community! 💙

## 📜 Licenza

Contribuendo a questo progetto, accetti che i tuoi contributi saranno rilasciati sotto la [MIT License](LICENSE).

---

**Grazie per contribuire! 🎉**

*Linux Day UniMe 2025 - Impara, condividi, collabora nel mondo open source*
