# OBOS Bøler Cup – Dommerregistrering

Dette prosjektet er et statisk nettsted med:
- `index.html`: Dommerskjema
- `admin.html`: Adminpanel (passordbeskyttet)
- `_redirects`: Netlify-støtte for `/admin`

## 📦 Hvordan bruke

### 1. Last opp til GitHub
1. Gå til [https://github.com/new](https://github.com/new)
2. Lag et nytt repo, f.eks. `boler-cup-referee-site`
3. Last opp alle filene i denne ZIP-filen

### 2. Deploy til Netlify
1. Gå til [https://app.netlify.com/](https://app.netlify.com/)
2. Velg "Import from GitHub"
3. Koble til repoet du nettopp lagde
4. Deploy uten byggesteg (velg "No build command", publish dir: `/`)

✅ Når deploy er ferdig:
- `/` viser skjemaet
- `/admin` viser adminpanelet (passord: `admin2025`)
