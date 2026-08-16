# lenny-ts.github.io

Landing page personale, stile cyberpunk/CRT ispirato a netsky.me.
Single-file (`index.html` + CSS inline), nessun build step, nessuna dipendenza.
Hostato su GitHub Pages.

## File
- `index.html` — l'intero sito (HTML + CSS + SVG inline)
- `avatar.svg` — placeholder avatar geometrico (sostituibile)

## Personalizzazione
Cerca `TODO` in `index.html` per i punti da modificare:
- `<title>` / meta `og:title` → tuo nome
- `.tagline` → la tua frase
- `href` dei bottoni (`github.com/lenny-ts`, `mailto:you@example.com`, terzo link)
- `avatar.svg` → sostituisci con una tua immagine (puoi usare un `.png`/`.jpg` aggiornando `src`)

## Deploy
Repo "user site" → va online su `https://lenny-ts.github.io/`.

1. GitHub → Settings → Pages → Source: `Deploy from a branch` → `main` / `/(root)`
2. Ogni `git push` su `main` aggiorna il sito (~1 min)

## Sviluppo locale
Apri `index.html` nel browser. Niente server richiesto (font da Google Fonts CDN).

## Stack replicato da netsky.me (ma senza framework)
- Tema nero/rosso + grigi mute
- Font Chakra Petch + Share Tech Mono
- Overlay scanline CRT
- Bottoni con angolo tagliato (clip-path) + animazione scan on hover
- Glow rosso su hover/focus
- `prefers-reduced-motion` rispettato
