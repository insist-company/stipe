# STIPE — sito ufficiale

Tre pagine statiche in italiano, senza dipendenze, JavaScript, cookie o risorse esterne caricate dal sito. Il tema segue le preferenze chiare/scure del dispositivo.

## File

- `index.html`: Home e collegamento definitivo all’App Store.
- `supporto.html`: contatti e quattro FAQ.
- `privacy.html`: informativa fornita, con l’email di supporto nel contatto privacy.
- `style.css`: stile condiviso e layout responsive.
- `.nojekyll`: pubblicazione statica senza elaborazione Jekyll.

## Pubblicazione gratuita su GitHub Pages

1. Accedi a GitHub, seleziona **+ → New repository**, chiamalo `stipe`, scegli **Public** e crea il repository. Un repository pubblico consente di usare Pages con GitHub Free.
2. Nel repository seleziona **uploading an existing file**, oppure **Add file → Upload files**. Carica i file contenuti in questa cartella direttamente nella radice del repository, senza la cartella esterna `stipe`. Includi `.nojekyll`, che su macOS è nascosto (Cmd + Maiusc + punto per mostrarlo). Conferma con **Commit changes** sul branch `main`.
3. Apri **Settings → Pages**. In **Build and deployment**, scegli **Source → Deploy from a branch**; seleziona **main**, cartella **/(root)** e premi **Save**.
4. Attendi il completamento della pubblicazione. La sezione Pages mostrerà l’indirizzo pubblico. Le modifiche successive caricate sullo stesso branch aggiorneranno il sito.

Con nome utente `TUO-USERNAME` e repository `stipe`, gli indirizzi saranno:

- Home: `https://TUO-USERNAME.github.io/stipe/`
- Supporto: `https://TUO-USERNAME.github.io/stipe/supporto.html`
- Privacy: `https://TUO-USERNAME.github.io/stipe/privacy.html`

In App Store Connect usa l’indirizzo di Supporto per il campo Support URL e quello di Privacy per Privacy Policy URL. Il sito diventerà pubblico dopo la pubblicazione GitHub Pages.

Se scegli un altro nome per il repository, sostituisci `stipe` negli URL. Se il repository si chiama esattamente `TUO-USERNAME.github.io`, gli URL non hanno il segmento `/stipe`.

## Anteprima locale

Apri `index.html` nel browser. Tutti i percorsi sono relativi e funzionano anche senza server.

## Contenuti

L’email usata nelle pagine Supporto e Privacy è `perlagloria.vision@gmail.com`. Il collegamento App Store è `https://apps.apple.com/app/id6821166747`, mantenuto indipendentemente dalla sua disponibilità pubblica.

Documentazione GitHub: https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site
