🃏 HAWKS – Blackjack (Demo-Projekt)

Dies ist ein rein privates, nicht-kommerzielles Projekt zur Demonstration moderner Frontend-Entwicklung mit HTML, CSS und Vanilla JavaScript.
Das Spiel dient ausschließlich Lern- und Unterhaltungszwecken und enthält keinerlei Funktionen für Echtgeldspiele.

⚠️ Kein Glücksspiel

Dieses Spiel stellt kein Glücksspiel im Sinne des deutschen Glücksspielstaatsvertrags dar. Es gibt:

❌ keine Echtgeld-Einsätze

❌ keine Auszahlungen

❌ keine Verbindung zu Online-Casinos

Alle Hände/Spins sind rein virtuell ohne wirtschaftliche Relevanz.
Das Projekt richtet sich an Entwickler:innen, Hobby-Coder und interessierte Nutzer zur reinen Unterhaltung oder Weiterbildung.

✨ Features

🎨 Themes: Casino, Deutschland, Österreich, Frankreich, Tschechien

🧠 Strategy Coach (vereinfachte Basic Strategy mit Begründung & Status-Pills)

🏅 Achievements (z. B. Erster Sieg, Blackjack, Five-Card Charlie, Hot Streak, High Roller, 100 Hände)

🔥 Streak-Badge mit animierter Anzeige

🎚️ Lautstärke-Regler & Mute-Toggle

⚡ Turbo-Modus (schnellere Animationen & angepasste Lautstärke)

🔒 Admin-Panel (Deck-Anzahl, Penetration, Surrender erlauben)

💾 Persistenz via localStorage (Theme, Turbo, letzte Wette, Admin-Settings, Achievements)

🃠 3D-Tisch/Parallaxe & animiertes Kartengeben

📜 Rundenhistorie & Stats (Hände, Siege/Niederlagen/Push, Einsätze, Gewinn, Winrate)

Hinweis: „Auto-Hand“ ist im UI aktuell deaktiviert (#autoPlayButton { display: none !important; }), die Logik ist jedoch vorhanden.

🎮 Steuerung & Shortcuts
Aktion	Button	Shortcut
Geben	🎲 Geben	G
Karte ziehen	➕ Karte	H
Stehen	✋ Stehen	S
Double	2️⃣ Double	D
Split	⤵️ Split	P
Aufgeben	🏳️ Aufgabe	U
Versicherung	🛡️ Versicherung	I
Reset	🔄 Reset	R
Admin-Panel	–	Ctrl + Shift + L
Theme wählen	Dropdown oben rechts	–
Turbo ein/aus	⚡ Turbo	–
🧩 Technologien

HTML5

CSS3 (Custom Properties, responsive Layout, Glas-Panel-Look)

Vanilla JavaScript (ES6 Klassen, DOM, localStorage)

Audio via <audio>-Elemente

(Optional) Open-Source-Hosting über GitHub Pages

🚀 Schnellstart

Lokal ausführen

Datei index.html doppelklicken – fertig.
(Oder mit einem lokalen Webserver öffnen, z. B. npx serve.)

Deployment auf GitHub Pages

Neues Repo erstellen (z. B. hawks-blackjack).

Deinen HTML-Code als index.html ins Repo committen & pushen.

In den Repo-Einstellungen Settings → Pages:

Source: Deploy from a branch

Branch: main / /root

URL aus dem Pages-Block öffnen – live!

🗂️ Projektstruktur (Single-File)

Dieses Demo ist als Single-File-App angelegt:

HTML: Markup + UI-Struktur

<style>: Themes, Layout, Komponenten

<script>: Klasse BlackjackGame (State, Regeln, UI-Binding)

Du kannst CSS & JS bei Bedarf in eigene Dateien auslagern.

🔧 Admin-Einstellungen

Öffnen mit Ctrl + Shift + L (Default-Passwort: admin)

Decks: 1–12

Penetration: Mischen bei Rest-%

Surrender erlauben: an/aus

Persistenz-Keys (localStorage)
bjTheme, bjDecks, bjPen, bjSurrender, bjTurbo, bjLastBet, bjAchievements

🔊 Audio-Hinweise & Lizenzen

Die Soundeffekte werden per <audio> über freesound.org-Previews geladen:

Deal: 527604_7652097-lq.mp3

Win: 411090_5121236-lq.mp3

Lose: 544508_9944713-lq.mp3

Shuffle: 108779_1411102-lq.mp3

🧠 Urheberrecht & Nutzung

Der gesamte Code wurde selbst entwickelt bzw. mit Hilfe von ChatGPT generiert.
Grafiken/UI sind Eigenarbeit (CSS).
Audio gemäß den Creative-Commons-Bedingungen der jeweiligen Urheber.

Dieses Projekt wird ohne Lizenzdatei bereitgestellt.
Eine Nutzung/Weiterverwendung von Code-Teilen ist gestattet.
Ein Quellverweis auf dieses Projekt ist gern gesehen, aber nicht erforderlich.
(Achtung: Für Audio-Clips gelten die CC-Bedingungen inkl. Namensnennung!)

🛡️ Haftungsausschluss

Dieses Projekt wird „as is“ bereitgestellt.
Es gibt keine Garantie auf Funktionalität, Sicherheit oder rechtliche Unbedenklichkeit für andere Einsatzbereiche.
Die Nutzung des Codes und etwaig gehosteter Inhalte erfolgt auf eigenes Risiko.

🧭 Tipps & Troubleshooting

Theme-Wechsel nur, wenn keine Hand läuft (Sperrhinweis im UI).

Turbo reduziert Animationsdauer & passt Lautstärke an.

Bei stummem Audio: Systemlautstärke prüfen, Mute-Icon (🔊/🔇) klicken, oder Browser-Autoplay-Policy beachten.

Reset setzt State, Stats & UI zurück (Persistenz-Daten wie Achievements bleiben erhalten).

📜 Rechtlicher Hinweis (DE)

Dies ist kein Glücksspielangebot. Keine Einsätze, keine Gewinnausschüttung.
Die App dient nur Demo-, Lern- und Testzwecken.

Viel Spaß beim Ausprobieren! 🙌
Feedback, Issues oder Ideen? Einfach melden – oder forken & erweitern.
