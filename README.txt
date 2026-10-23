RIKKEN V2 ONLINE - eerste werkende testversie

1. Firebase Console > Firestore Database > Rules: plak firestore.rules en klik Publish.
   LET OP: hiermee vervang je de tijdelijke regel die alles blokkeert.
2. Upload index.html, manifest.webmanifest, sw.js, icon-192.png, icon-512.png
   naar de hoofdmap van GitHub repository Rikken-V2 (NIET firestore.rules).
3. Settings > Pages > Deploy from a branch > main > /(root).
4. Open https://adieben-cpu.github.io/Rikken-V2/
5. Maak een groep en deel de groepslink. De maker is de spelleider.

Beveiliging: iedere bezoeker krijgt een anonieme Firebase-identiteit.
De groepslink bevat een willekeurige groeps-ID; wie de link kent kan de stand
lezen. Alleen het apparaat dat de groep maakte kan schrijven. Verwijder dus
niet de browsergegevens van de groepsmaker zonder herstelplan.

LET OP: dit is een TESTVERSIE. Regels kunnen worden aangepast, maar controleer
de puntentelling voor gebruik. Firestore beperkt de documentgrootte tot 1 MiB;
maak bij veel rondes een nieuwe partij. De app biedt nog geen automatisch
herstel van groepsbeheerder of import van oude V1-data.
