# Previz Web

Webový prohlížeč scén z Previz Stream (GEN live). Tahle stránka se publikuje přes GitHub Pages:

- `index.html` – prohlížeč (three.js), stejný jako `web/viewer.html` v aplikaci
- `p/<kód>/model.bin` – publikované scény, zašifrované AES-256-GCM; klíč je jen v odkazu za `#` a na GitHub se nikdy nedostane

Složky v `p/` vytváří a maže aplikace Previz Stream (Export › WEB › Publikovat odkaz…). Bez klíče z odkazu jsou soubory nečitelné.
