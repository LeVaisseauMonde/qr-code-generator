# ◰ QR Code Generator

> Créez des QR codes personnalisés avec logo — gratuit, sans inscription, sans pub

[![Live](https://img.shields.io/badge/LIVE-Essayer_l'outil-c8ff00?style=flat-square&labelColor=0a0a0a)](https://levaisseaumonde.github.io/qr-code-generator/)
[![BlackCrow](https://img.shields.io/badge/BlackCrow_OS-Hub-333?style=flat-square&labelColor=0a0a0a)](https://levaisseaumonde.github.io/BlackCrow/)

---

## Fonctionnalités

- Générer un QR code à partir de n'importe quelle URL ou texte
- Intégrer un logo personnalisé au centre du QR code
- Choisir la couleur du QR code et du fond
- Télécharger le résultat en PNG directement
- Traitement 100% local — aucune donnée envoyée

---

## Utilisation

1. Ouvrir [l'outil](https://levaisseaumonde.github.io/qr-code-generator/)
2. Saisir l'URL ou le texte à encoder
3. Personnaliser logo, couleurs, taille
4. Télécharger le QR code généré

Aucun compte requis. Aucune pub. Fonctionne hors-ligne une fois la page chargée.

---

## Intégration BlackCrow OS

Cet outil fait partie de la suite [BlackCrow OS](https://levaisseaumonde.github.io/BlackCrow/), l'interface système de l'univers [Le Vaisseau-Monde](https://www.vaisseau-monde.fr).

La navbar est chargée dynamiquement depuis le hub central :

```html
<div id="bc-navbar"></div>
<script>
  fetch('https://levaisseaumonde.github.io/BlackCrow/navbar.html')
    .then(r => r.text())
    .then(html => document.getElementById('bc-navbar').innerHTML = html);
</script>
```

---

## Liens

- 🌐 [vaisseau-monde.fr](https://www.vaisseau-monde.fr)
- 📺 [YouTube @VaisseauMonde](https://www.youtube.com/@VaisseauMonde)
- 🔗 [BlackCrow OS](https://levaisseaumonde.github.io/BlackCrow/)

---

*QLVVP 🖤*
