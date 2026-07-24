# GROGNON — Court métrage IA

Production d'un court métrage généré par IA dans **l'univers de Grognon**
(personnages inventés en famille). Pipeline : model sheets → prompts vidéo (Veo 3) → montage.

- **Format :** 9:16 vertical (TikTok / Reels / Shorts)
- **Style :** semi-réaliste caricatural, rendu 3D peint (voir model sheets)
- **Vidéo :** Google **Veo 3** (dialogues + bruitages + musique en audio natif)

## Structure du repo

```
01_bible/        La bible : personnages, univers, décors, objets
02_teaser/       Le teaser 45 s : kit de prompts Veo prêts à coller
03_references/   ⚠️ Déposer ici vos model sheets (réf images pour Veo)
```

## Où on en est
- ✅ Model sheets des 5 personnages + décors + objets (faits)
- ✅ Bible écrite → `01_bible/personnages-et-univers.md`
- ✅ Découpage + prompts Veo du teaser → `02_teaser/veo-prompts-teaser.md`
- ⬜ Générer les 8 plans dans Veo
- ⬜ Voix / bruitages / musique
- ⬜ Montage 9:16 (CapCut / DaVinci Resolve)

## Prochaine étape
Ouvrir `02_teaser/veo-prompts-teaser.md`, déposer les model sheets dans `03_references/`,
puis générer plan par plan dans Veo (2–3 variantes / plan). Voir les ⚠️ filtre sur les plans 7 & 8.
