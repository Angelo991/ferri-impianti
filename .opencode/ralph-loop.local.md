---
active: true
iteration: 0
maxIterations: 100
---

/ralph-loop "Usa la skill loop-sicuro e la skill frontend-design.
COSA: crea il sito di una pagina descritto in brief-idraulico.md (leggilo tutto).
Pezzi da fare, uno per giro: 1) prima schermata con il pulsante 'Chiama 333 456 7890'
che usa il link tel:+393334567890; 2) i 4 servizi; 3) 'Perché sceglierci' con 3 motivi
(preventivo gratuito, oltre 15 anni di esperienza, garanzia 2 anni);
4) orari e zona servita, email info@ferri-impianti.it.
DOVE: cartella sito, un solo file index.html con lo stile dentro.
COME CONTROLLARE: dopo ogni pezzo usa playwright con larghezza 390 pixel (telefono):
fai uno screenshot, controlla che il pulsante di chiamata si veda nella prima schermata
e che non ci sia scorrimento orizzontale. Poi salva con:
git add -A e git commit -m 'descrizione del pezzo' (se la cartella non è un progetto Git: git init -b main).
Tieni il diario in progresso.md e scrivi verifiche.md alla fine.
Quando tutti i pezzi sono fatti, chiedi a @revisore di controllare sito/index.html
e correggi gli errori che trova, poi salva con Git.
QUANDO È FINITO: i 4 pezzi sono fatti e verificati con playwright, il revisore non
trova errori gravi, tutto è salvato con Git. Allora scrivi <promise>DONE</promise>."
