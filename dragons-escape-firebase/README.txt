DRAGON'S ESCAPE - Firebase Hosting (gratis Spark plan)

Dit project bevat de actuele Dragon's Escape-game inclusief de gedetailleerde draak,
objecten, grotere kapotte causeway en bruine verzamelbare flesjes.
Alle game-afbeeldingen zitten al in public/index.html.

1. Maak een Firebase-project: https://console.firebase.google.com/
2. Kies in Firebase de Spark (No cost) optie.
3. Installeer Node.js (als je dit nog niet hebt) en open Terminal op je Mac.
4. Installeer Firebase CLI:
   npm install -g firebase-tools
5. Log in:
   firebase login
6. Ga via Terminal naar DEZE uitgepakte map (de map met firebase.json).
   Voorbeeld:
   cd ~/Downloads/dragons-escape-firebase
7. Publiceer naar het project dat je in stap 1 hebt aangemaakt:
   firebase deploy --only hosting --project JOUW_PROJECT_ID

Vervang JOUW_PROJECT_ID door de Project ID die Firebase aangeeft.
Na publicatie krijg je een link zoals https://jouw-project-id.web.app.

Bij een nieuwe versie hoef je alleen public/index.html te vervangen en hetzelfde
firebase deploy commando uit te voeren.

Let op: kies Firebase Hosting (classic), niet Firebase App Hosting.
Spark is gratis tot de Firebase Hosting quota. Zie firebase.google.com/pricing.
