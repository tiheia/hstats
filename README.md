🏐 Håndballstatistikk - Øyestad
En komplett web-app for live statistikk under håndballkamper. Registrer mål, redninger, assist, soner og tekniske feil i sanntid.
🚀 Bruk appen
Live app: hstats.netlify.app
✨ Funksjoner
Før kampen

Velg serie: Lokal/Region (2x25 min) eller egendefinerte innstillinger
Legg inn motstander: Navn på motstanderlaget
Velg spillere: Kun spillere som deltar i kampen
Startoppstilling: Velg hvilke spillere som starter på banen

Under kampen

⏱️ Timer med start/stopp/timeout
⚡ Rask registrering med "Mest brukte spillere" øverst
🎯 Målvakter: Redning/Mål imot + sone
⚽ Utespillere: Mål/Bom/Teknisk + sone + assist
📍 8 soner + Straffekast + Kontring
⏸️ Timeout: Registrer hvem som tar timeout (Øyestad eller motstander)
✏️ Rediger hendelser: Rett feil underveis
🔄 Bytt spillere: Enkelt å bytte hvem som er på banen
📋 Hendelseslogg: Se alle hendelser gruppert per omgang

Etter kampen

📊 Lagstatistikk:

Mål scoret/sluppet inn per sone
Bom og tekniske feil
Redninger per sone


📥 CSV-eksport: Last ned all data for analyse
🔄 Omgangssammendrag: Se statistikk per omgang eller hele kampen

📱 Installasjon
Mobil (anbefalt)

Åpne appen i Safari/Chrome
Trykk på "Del" → "Legg til på hjemmeskjermen"
Appen fungerer nå som en egen app!

PC/Tablet

Åpne URL i nettleseren
Lagre som bokmerke for rask tilgang

🎮 Slik bruker du appen
1. Opprett kamp
Serie → Motstander → Velg spillere → Startoppstilling
2. Under kampen

Start klokken for å begynne registrering
Klikk på spillernavn → Velg handling → Velg sone
For mål: Velg også assist (spillere sortert etter antall assist)
Mest brukte spillere vises øverst (målvakter først)
Stopp klokken for å pause registrering
Timeout-knapp for å registrere timeout

3. Mellom omganger

Se sammendrag med lagstatistikk
Velg ny startoppstilling for neste omgang

4. Etter kampen

Se sluttstatistikk med sonefordeling
Last ned CSV for videre analyse
Avslutt og start ny kamp

📊 Spillerliste
Målvakter (🥅)

Patrick F
Theo
Ulrik

Utespillere
Adrian A, Adrian B, Demyd, Fabian, Felix, Jacob, Jonas, Loke, Markus, Mateo, Mats, Nicolay, Ole, Oskar, Patrick W., Sebastian, Stokka, Theodor
💾 Datalagring

Lokal lagring: Data lagres i nettleseren
Ingen cloud: Alt lagres lokalt på enheten
Backup: Last alltid ned CSV etter kampen!
Ikke tøm cache før du har lastet ned CSV

🔄 Oppdatering
Appen oppdateres automatisk ved endringer i GitHub-repositoryet via Netlify.
🛠️ Teknisk

Frontend: React 18
Styling: Tailwind CSS
Hosting: Netlify
Ikoner: Lucide (inline SVG)

📝 CSV-format
Eksportert CSV inneholder:
csvOmgang,Spiller,Handling,Sone,Assist
1,Jonas,Mål,Sone 3,Felix
1,Patrick F,Redning,Sone 2,
2,Mats,Bom,Sone 5,
🐛 Feilsøking
Problem: Appen viser ikke data fra forrige kamp

Løsning: Data lagres per økt. Last ned CSV før du lukker nettleseren.

Problem: Klokken stopper ikke

Løsning: Oppdater siden (data bevares i nettleseren)

Problem: Kan ikke laste ned CSV

Løsning: Sjekk nettleserens nedlastingsinnstillinger

📧 Support
Har du spørsmål eller forslag? Ta kontakt!
📄 Lisens
Denne appen er laget for Øyestad håndball.
