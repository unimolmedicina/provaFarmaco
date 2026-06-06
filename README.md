# Simulatore Farmacologia 2

Web app React/Vite per simulazioni d'esame e allenamento.

## Funzioni

- Simulazione esame: 30 domande / 30 minuti
- Allenamento per argomento
- Feedback immediato in allenamento
- Statistiche salvate nel browser
- Esportazione/importazione statistiche in JSON
- Deploy pronto per GitHub Pages con GitHub Actions

## Sviluppo locale

```bash
npm install
npm run dev
```

## Deploy su GitHub Pages

1. Crea un nuovo repository GitHub.
2. Carica tutti i file di questa cartella nella root del repository.
3. Vai in `Settings > Pages`.
4. In `Build and deployment`, scegli `GitHub Actions`.
5. Fai commit/push su `main`.
6. Attendi il workflow `Deploy to GitHub Pages`.
7. Torna in `Settings > Pages` e apri il link pubblicato.

## Statistiche

Le statistiche sono salvate nel LocalStorage del browser. Usa `Esporta statistiche` per fare backup e `Importa statistiche` per unire statistiche da un altro browser/dispositivo.
