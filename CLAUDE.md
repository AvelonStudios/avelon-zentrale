# AvèlonStudios Zentrale
Dashboard für AvèlonStudios. Gehostet auf Netlify, verbunden mit GitHub und Supabase.

## Wichtigste Datei
- index.html — die komplette Zentrale (HTML, CSS, JS in einer Datei)

## Datenbank (Supabase)
- URL: https://eurrqzerazjkasemmigu.supabase.co
- Tabellen: leads, todos
- Publishable Key steht bereits in index.html

## Design-System
- Hintergrund #060606 / #101010, Gold-Akzent #c9b97a
- Fonts: Cormorant Garamond (Headlines) + Jost (Body)

## Workflow nach JEDER Änderung an index.html
Immer automatisch: git add -A, git commit (sinnvolle Nachricht), git push.
Netlify deployt dann von selbst.
