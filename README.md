# Trustera

React/Vite prototyp realitní platformy připravený pro GitHub Pages.

## Lokální spuštění

```bash
npm install
npm run dev
```

## Nasazení na GitHub Pages

1. Vytvořte na GitHubu nový repozitář, například `trustera`.
2. Nahrajte do něj celý obsah této složky.
3. Otevřete **Settings → Pages**.
4. U **Source** vyberte **GitHub Actions**.
5. Otevřete **Actions** a zkontrolujte workflow `Deploy Trustera to GitHub Pages`.
6. Po dokončení se ve **Settings → Pages** zobrazí veřejná adresa.

Každý další push do větve `main` aplikaci automaticky znovu nasadí.

## Bezpečnost

Jde o frontendový prototyp. GitHub Pages je statický hosting a neposkytuje
bezpečný backend. Produkční autentizace, autorizace, platby, dokumenty a osobní
údaje musí být řešeny serverově. Do repozitáře nevkládejte privátní klíče,
hesla ani skutečné osobní údaje.
