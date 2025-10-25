# 🌟 Open Source Contributors - Linux Day UniMe 2025

Benvenuto nel tuo primo contributo open source! Questo è un repository pratico per imparare il workflow collaborativo di Git e GitHub.

## 🎯 Obiettivo

Imparerai a:
- 🍴 Fare **fork** di un repository
- 📥 **Clonare** il tuo fork localmente
- 🌿 Creare e lavorare con i **branch**
- 💾 Fare **commit** delle tue modifiche
- 📤 Fare **push** su GitHub
- 🔀 Aprire una **Pull Request**

## 🚀 Come Contribuire

### Passo 1: Fork questo repository

Clicca sul pulsante **Fork** in alto a destra per creare una copia di questo repository nel tuo account GitHub.

### Passo 2: Clona il tuo fork

Scegli il metodo che preferisci:

**Con SSH:**
```bash
git clone git@github.com:TUO-USERNAME/opensource-contributors.git
cd opensource-contributors
```

**Con HTTPS:**
```bash
git clone https://github.com/TUO-USERNAME/opensource-contributors.git
cd opensource-contributors
```

### Passo 3: Crea un nuovo branch

```bash
git checkout -b add-contributor-TUONOME
```

> 💡 **Suggerimento:** Sostituisci `TUONOME` con il tuo nome o username!

### Passo 4: Aggiungi il tuo profilo

Crea un nuovo file nella cartella `contributors/` chiamato `TUONOME.md` con il seguente contenuto:

```markdown
# Nome Cognome

## 👋 Chi sono
Breve descrizione di te (2-3 righe). Ad esempio: studente, developer, appassionato di tecnologia, etc.

## 💡 Perché sono qui
Spiega brevemente perché ti interessa l'open source e cosa vorresti imparare.

## 🛠️ Competenze
- Linguaggio di programmazione 1
- Linguaggio di programmazione 2
- Framework o tecnologia preferita
- Altro...

## 📫 Contatti
- GitHub: [@tuousername](https://github.com/tuousername)
- Email: tua-email@example.com (opzionale)
- LinkedIn: [Tuo Nome](https://linkedin.com/in/tuoprofilo) (opzionale)
```

### Passo 5: Commit delle modifiche

```bash
git add contributors/TUONOME.md
git commit -m "Add contributor: TUONOME"
```

> 💡 **Best Practice:** Usa messaggi di commit chiari e descrittivi!

### Passo 6: Push sul tuo fork

```bash
git push origin add-contributor-TUONOME
```

### Passo 7: Apri una Pull Request

1. Vai sul **tuo fork** su GitHub
2. Vedrai un banner giallo con il pulsante **"Compare & pull request"** - cliccaci!
3. Assicurati che:
   - **base repository:** `linux-day-unime-2025/opensource-contributors`
   - **base:** `main`
   - **head repository:** `TUO-USERNAME/opensource-contributors`
   - **compare:** `add-contributor-TUONOME`
4. Scrivi un titolo descrittivo: `Add contributor: TUONOME`
5. Nella descrizione, scrivi qualcosa come:
   ```
   Ciao! 👋

   Partecipo al workshop Git del Linux Day UniMe 2025.
   Ho aggiunto il mio profilo alla lista dei contributor.

   Grazie per l'opportunità di contribuire!
   ```
6. Clicca su **"Create pull request"**

🎉 **Complimenti!** Hai appena creato la tua prima Pull Request!

## 📝 Usare le GitHub Issues

Le Issues sono il modo per comunicare nel progetto: segnalare bug, proporre miglioramenti, fare domande.

### Come aprire una Issue

1. Vai sulla tab **Issues** di questo repository
2. Clicca su **New issue**
3. Scegli un titolo chiaro, ad esempio:
   - 🐛 "Bug: Il link nella documentazione non funziona"
   - ✨ "Suggerimento: Aggiungere sezione FAQ al README"
   - ❓ "Domanda: Come configuro SSH su Windows?"
4. Descrivi il problema o il suggerimento in dettaglio
5. Aggiungi una **label** appropriata (se disponibile):
   - `bug` per errori
   - `enhancement` per miglioramenti
   - `question` per domande
   - `documentation` per la documentazione
6. Clicca **Submit new issue**

### Template per Issues

**Per suggerimenti:**
```markdown
## 💡 Suggerimento

Sarebbe utile aggiungere [TUA IDEA] perché [MOTIVAZIONE].

### Dettagli
[Descrizione più approfondita]

### Benefici
- Beneficio 1
- Beneficio 2
```

**Per bug:**
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
```

## 👥 Contributors

Grazie a tutti i contributor del Linux Day UniMe 2025! 🎉

<!-- La lista dei contributor verrà generata automaticamente -->

## 📚 Risorse Utili

- [Git Documentation](https://git-scm.com/doc)
- [GitHub Docs](https://docs.github.com)
- [GitHub Skills](https://skills.github.com/)
- [First Contributions](https://github.com/firstcontributions/first-contributions)
- [How to Contribute to Open Source](https://opensource.guide/how-to-contribute/)

## 🤝 Code of Conduct

Questo progetto segue il [Contributor Covenant Code of Conduct](CODE_OF_CONDUCT.md). Partecipando, ti impegni a mantenere un ambiente rispettoso e inclusivo per tutti.

### In breve:
- ✅ Sii rispettoso e inclusivo
- ✅ Accetta feedback costruttivi
- ✅ Focalizzati su ciò che è meglio per la community
- ❌ Non tollerare comportamenti offensivi o discriminatori

## 📄 Licenza

Questo progetto è rilasciato sotto licenza MIT. Vedi il file [LICENSE](LICENSE) per i dettagli.

## ❓ FAQ

### Come faccio a sincronizzare il mio fork con l'originale?

```bash
# Aggiungi il repository originale come remote "upstream"
git remote add upstream https://github.com/linux-day-unime-2025/opensource-contributors.git

# Scarica le modifiche
git fetch upstream

# Unisci le modifiche nel tuo branch main
git checkout main
git merge upstream/main

# Push sul tuo fork
git push origin main
```

### Ho fatto un errore nel mio commit, come lo correggo?

Se non hai ancora fatto push:
```bash
git commit --amend
```

Se hai già fatto push, puoi fare un nuovo commit con la correzione.

### La mia Pull Request ha conflitti, cosa faccio?

1. Sincronizza il tuo fork (vedi sopra)
2. Passa al tuo branch: `git checkout add-contributor-TUONOME`
3. Unisci main: `git merge main`
4. Risolvi i conflitti nei file
5. Aggiungi e committa: `git add .` e `git commit`
6. Push: `git push origin add-contributor-TUONOME`

### Posso contribuire anche dopo il workshop?

Assolutamente sì! Il repository rimane aperto per contributi. Puoi:
- Aggiornare il tuo profilo
- Aiutare altri con le Issues
- Proporre miglioramenti alla documentazione
- Condividere risorse utili

## 💬 Supporto

- 🐛 **Trovato un bug?** Apri una [Issue](https://github.com/linux-day-unime-2025/opensource-contributors/issues)
- ❓ **Hai una domanda?** Chiedi nelle [Discussions](https://github.com/linux-day-unime-2025/opensource-contributors/discussions)
- 💡 **Hai un suggerimento?** Apri una Issue con label `enhancement`

## 🙏 Ringraziamenti

Grazie a tutti i partecipanti del workshop "Git: collaborare senza caos" per aver reso possibile questo progetto!

Un ringraziamento speciale al **Linux Day UniMe 2025** per l'organizzazione dell'evento.

---

**🐧 Linux Day UniMe 2025**  
*Impara, condividi, collabora nel mondo open source*

Made with ❤️ by the open source community
