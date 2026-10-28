# 🛒 Indkøbsliste

Hurtig og overskuelig indkøbsliste bygget som en statisk web-app ([index.html](index.html)) til **GitHub Pages** med Firebase (Authentication + Firestore realtids-synkronisering).

## Funktioner
- **`Vare/Butik`-kommando med dropdown**: Skriv f.eks. `Mælk/Netto` (med case-insensitive dropdown-forslag) eller blot `Gulerødder` (havner under *Generelt*).
- **Automatisk Link-Preview**: Indsæt et produktlink (f.eks. fra Harald Nyborg, Bauhaus, Biltema, Billigblomst), så hentes titel, produktbillede og butiksnavn automatisk.
- **Realtids-synkronisering & Auto-login**: Synkroniserer på tværs af enheder via Firebase Authentication (`browserLocalPersistence`) og Cloud Firestore, med lokal `localStorage` cache.
- **GitHub Pages klar**: Kører direkte fra `index.html` uden behov for ekstra server eller build-step.
