# Autonomous Decision Engine (ADE) - Sito Web

Questo sito web è stato creato per soddisfare i requisiti di verifica di Stripe per l'attivazione di un account Stripe.

## Scopo

Il sito contiene le informazioni legali e di contatto necessarie per la verifica dell'account Stripe, inclusi:
- Descrizione del servizio SaaS
- Informazioni sul fornitore (Matteo Tossut)
- Privacy Policy
- Termini di Servizio
- Dati di contatto per il supporto clienti

## Pubblicazione su GitHub Pages

Per pubblicare questo sito su GitHub Pages e ottenere un URL pubblico da utilizzare in Stripe, seguire questi passaggi esatti:

### Passo 1: Inizializzare il Repository Git

Se non hai già inizializzato Git in questa cartella:

```bash
cd ade-site
git init
git add .
git commit -m "Initial commit: ADE website for Stripe verification"
```

### Passo 2: Creare un Repository su GitHub

1. Vai su [GitHub.com](https://github.com) e accedi al tuo account
2. Clicca sul pulsante "+" in alto a destra e seleziona "New repository"
3. Scegli un nome per il repository (es. `ade-website` o `ade-site`)
4. Seleziona "Public" (deve essere pubblico per GitHub Pages gratuito)
5. **NON** inizializzare con README, .gitignore o licenza (abbiamo già i file)
6. Clicca "Create repository"

### Passo 3: Collegare il Repository Locale a GitHub

GitHub ti mostrerà le istruzioni. Esegui questi comandi (sostituisci `TUO_USERNAME` e `NOME_REPO` con i tuoi valori):

```bash
git remote add origin https://github.com/TUO_USERNAME/NOME_REPO.git
git branch -M main
git push -u origin main
```

### Passo 4: Attivare GitHub Pages

1. Vai alla pagina del repository su GitHub
2. Clicca su **"Settings"** (Impostazioni) nella barra superiore del repository
3. Scorri verso il basso fino alla sezione **"Pages"** nel menu laterale sinistro
4. Nella sezione "Source", seleziona:
   - **Branch:** `main`
   - **Folder:** `/ (root)`
5. Clicca **"Save"** (Salva)

### Passo 5: Attendere la Pubblicazione

GitHub impiegherà alcuni minuti per pubblicare il sito. Dopo qualche minuto:
1. Ricarica la pagina Settings → Pages
2. Vedrai un messaggio verde con l'URL del tuo sito pubblicato
3. L'URL sarà nel formato: `https://TUO_USERNAME.github.io/NOME_REPO/`

**Nota:** Se non vedi l'URL immediatamente, attendi 5-10 minuti e ricarica la pagina.

### Passo 6: Verificare il Sito

1. Apri l'URL fornito da GitHub Pages nel browser
2. Verifica che tutte le pagine siano accessibili:
   - Homepage: `https://TUO_USERNAME.github.io/NOME_REPO/`
   - Privacy Policy: `https://TUO_USERNAME.github.io/NOME_REPO/privacy.html`
   - Termini di Servizio: `https://TUO_USERNAME.github.io/NOME_REPO/terms.html`
3. Assicurati che il sito sia completamente pubblico e accessibile senza password

### Passo 7: Inserire l'URL in Stripe

1. Accedi al tuo account Stripe (o al processo di registrazione)
2. Vai alla sezione delle informazioni aziendali
3. Nel campo **"Sito web aziendale"** (o "Business website"), incolla l'URL completo:
   ```
   https://TUO_USERNAME.github.io/NOME_REPO/
   ```
4. Salva le modifiche

## Struttura del Sito

```
ade-site/
├── index.html      # Pagina principale con descrizione del servizio
├── privacy.html    # Privacy Policy completa
├── terms.html      # Termini di Servizio completi
└── README.md       # Questo file
```

## Requisiti Stripe

Questo sito soddisfa i requisiti di Stripe includendo:

✅ Descrizione chiara del servizio SaaS  
✅ Identificazione del fornitore (Matteo Tossut)  
✅ Dati di contatto pubblici (email e telefono)  
✅ Privacy Policy completa  
✅ Termini di Servizio completi  
✅ Sito pubblico e accessibile  
✅ Contenuto legale coerente per l'Italia  

## Note Importanti

- Il sito deve rimanere **pubblico** e **accessibile** per tutto il processo di verifica Stripe
- Non proteggere il sito con password o autenticazione
- Assicurati che l'URL funzioni correttamente prima di inserirlo in Stripe
- Se modifichi i contenuti, ricorda di fare commit e push su GitHub

## Supporto

Per domande o problemi relativi a questo sito, contattare:
- Email: tos.matteo@gmail.com
- Telefono: +39 340 786 1140

---

**Fornitore:** Matteo Tossut  
**Servizio:** Autonomous Decision Engine (ADE)  
**Paese:** Italia

