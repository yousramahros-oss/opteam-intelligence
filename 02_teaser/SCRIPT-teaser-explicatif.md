# TEASER EXPLICATIF « GROGNON » — Script de production complet

> **La famille la plus dysfonctionnelle du monde.**
> Court métrage IA · Format **9:16 vertical** · Durée ~45 s · 8 plans + logo
> Fil conducteur : une **voix-off de bande-annonce** présente (explique) la famille, perso par perso.

---

## 0. STACK TECHNIQUE RECOMMANDÉ (les meilleurs outils par étape)

| Étape | Outil recommandé | Pourquoi |
|---|---|---|
| **Plans vidéo** | **Grok Imagine** (image → vidéo) | Réussit déjà pile votre style 3D cartoon, là où Veo/Flow dérivent. C'est votre moteur principal. |
| **Images-clés** | Grok (ou Nano Banana / Midjourney) | Générer un *start frame* net avant d'animer = + de contrôle, - de morphing. |
| **Cohérence persos** | Réf 3D on-model (pas les planches 2D) | Donner à l'IA une image déjà en 3D → elle garde le look au lieu de le réinventer. |
| **Voix** | ElevenLabs (ou voix Grok si bonnes) | Pour les voix très typées (graisseuse, rauque, qui mue) → contrôle total, calées au montage. |
| **Musique** | Suno / banque orchestrale épique | Une seule montée épique-parodique sur tout le teaser. |
| **Montage** | CapCut ou DaVinci Resolve (gratuits) | Gèrent le 9:16, le mix audio, le logo. |
| **Upscale final** | Topaz Video / upscale 1080p-4K | Les clips Grok sortent en ~464×688 → on upscale à la fin. |

### Règles d'or (apprises à la dure)
1. **Un plan = un mouvement simple.** Les actions complexes (sortir de voiture, s'asseoir) morphent → on montre l'avant/l'après, pas le geste galère.
2. **Détail + réalisme vont sur l'IMAGE de départ**, pas sur le prompt d'animation (l'image porte le look).
3. **Toujours garder** la ligne : *« personnage cartoon exagéré rendu ultra-réaliste, PAS un vrai humain »* → sinon l'ultra-réalisme transforme les persos en vraies personnes.
4. **Mots-clés mouvement réaliste** : `poids et inertie réalistes` · `physique réaliste` · `anatomie stable` · `pas de morphing`.

---

## 1. DESIGN LOCK (fiches verrouillées)

**GROGNON** — colosse obèse 2m, chauve, crâne en dôme poreux. Mono-sourcil noir qui **cache totalement les yeux**. Deux pans de peau poreux pendants. Costume violet à rayures, médaillon doré, gantelets steampunk à fouets tressés.
› **Voix :** très grave, rauque, lente, respiration lourde, « Hrrrr… ».
› **Décor :** portail doré / manoir gothique, pluie, brume (univers sombre).

**GIOVANNA** — **bébé géant** (proportions de nourrisson : grosse tête, mini-corps, membres courts boudinés), très grosse, robe rose à froufrous, nœud rose, mono-sourcil cachant les yeux, médaillon « G ». A **un mal fou à marcher → roule comme une boule**.
› **Voix :** GRAISSEUSE, huileuse, mi-grave mi-aiguë, nasillarde, capricieuse — « Giovannaaaa… ».
› **Décor :** palais **rose & or** opulent (univers kitsch, opposé à Grognon).

**SANPLERIEN** — très grand, très maigre, sale malgré lui, cheveux blond/châtain en bataille, t-shirt & short déchirés, pieds nus, 2 dents de devant, immenses yeux tristes. Le seul gentil, souffre-douleur.
› **Voix :** qui mue, aiguë, cassée.
› **Décor :** la misère — sous-sol/cage, puis le caddie tiré par la limo.

**GIOVANNI** — « boss baby », bébé rondouillard, costume blanc de luxe, nœud pap rose, montre en or, une mèche bouclée, menton relevé, narcissique.
› **Voix :** « Giovanniii… » façon star de cinéma.
› **Décor :** couloir d'école chic, miroirs.

**GIOVANNIA** — bébé mignonne, robe rose élégante, longs cils, **pas de mono-sourcil**, sourire en coin, la plus populaire.
› **Voix :** « Giovannia… » douce et prétentieuse.
› **Décor :** école, lumière glamour.

---

## 1★. TEASER — VERSION DÉFINITIVE (★ À UTILISER ★)

> Ton : humour noir, second degré, vache. Structure : **documentaire animalier de luxe
> qui se fait saboter de l'intérieur**, jusqu'au chaos. Registres mixés : voix docu
> (clinique) + visuels pub de luxe + inserts vlog/sous-titres de Giovanna + final en
> réaction en chaîne muette.
>
> **Moteur comique** = fiche clinique glauque, dite à plat + *(beat)* + chute absurde,
> pire, ou dark-mignon.

### Les armes comiques (sur tout le teaser)
1. **Running gag du fouet** — Grognon ponctue les transitions d'un CLAC sur Sanplerien en fond, l'air de rien.
2. **Gag des sous-titres** — chacun ne dit que son prénom ; les sous-titres « traduisent » une punchline vacharde.
3. **Voix docu clinique sur visuels de pub de luxe** (le contraste = l'humour).
4. **Escalade** — commence « docu chic », finit en chaos absurde.
5. **Canon** : Grognon n'est PAS aveugle — yeux cachés sous le sourcil, il voit tout (mystère : homme ? reptilien ? son comptable ?).

### Le teaser, plan par plan

**P0 (noir)** — respiration rauque « Hrrrr ».
> « Dieu a créé l'homme à son image. Puis il a vu les Grognon… et il a demandé un remboursement. »
> *(titre doré, luxe : GROGNON)*

**P1 — La meute** *(limo rose, ralenti sublime, god-rays)* :
> « Une fortune bâtie sur trois piliers : le pétrole, l'évasion fiscale… et une crypto qui a ruiné 400 000 familles en un week-end. »
> *(reveal : la limo rouillée, kitsch)* « Le bon goût, lui, ne figurait pas à l'héritage. »

**P2 — Le mâle dominant** *(Grognon, hero shot)* :
> « Classification de l'espèce : inconnue. Sous le sourcil, personne n'a jamais regardé deux fois. Les survivants non plus. »
> « On n'a jamais vu ses yeux. Lui, en revanche, voit tout. »
> 🎭 Il tend la main à baiser, royal → CLAC dans son dos, sans tourner la tête.
> « On lui a diagnostiqué de l'empathie, une fois. » *(beat)* « C'était une erreur de laboratoire. »
> 📰 « Un bunker en Nouvelle-Zélande, une fusée privée, un taux d'imposition de zéro virgule zéro. »
> 🦎 HOOK : le sourcil se soulève d'un millimètre → une pupille verticale de reptile fixe la caméra → SNAP. « …C'était sûrement la lumière. »

**P3 — La femelle choyée** *(Giovanna, luxe ralenti)* :
> « On ignore son âge. On ignore si elle grandit. On sait juste qu'elle a mangé sa jumelle in utero. » *(beat)* « Par gourmandise. »
> 📱 *(vlog, filtre rose, cœurs)* « Giovannaaa » → **sous-titre :** *« placement de produit du jour : la misère des autres. (non sponsorisé) »*
> 🎭 Elle roule hors de la limo, aplatit le jardinier. « Remplacé par une IA dès lundi. L'IA a démissionné. »

**P4 — La parade** *(Giovanni, miroir)* :
> « Le jeune mâle déploie sa plus belle parade : lui-même. »
> « Giovanni a sauvé une vie, une fois. » *(beat)* « La sienne. Dans un miroir. »
> « Giovanni. » → **sous-titre :** *« je me suis dragué. j'ai dit oui. »*
> 🎭 Baiser au miroir → il explose. **ting** → un prof perd la vue. « Giovanni a trouvé ça flatteur. »

**P5 — La convoitée** *(Giovannia)* :
> « Onze cœurs brisés. Deux familles détruites. » *(beat)* « Elle est en CP. »
> « Giovannia. » → **sous-titre :** *« j'ai vu ta story. j'ai prié pour toi. »*
> Giovanni, fondu : « Giovanni. » → *« elle m'a parlé. »* — « Elle ne lui a pas parlé. »

**P6 — Le prédateur** *(Giovanna jalouse)* :
> « Chez cette espèce, la jalousie ne se gère pas. Elle se facture aux assurances. »
> « GIOVANNAAA !! » → **sous-titre :** *« JE BRÛLE L'ÉCOLE. ET JE DÉDUIS ÇA DES IMPÔTS. »*

**P7 — Effondrement** *(réaction en chaîne muette, puis pause sur Sanplerien)* :
> Giovanna charge → roule → explose Giovanni dans le miroir → l'éclat tranche la corde du caddie → Sanplerien décolle derrière la limo lancée. 📰 *(en fond, les domestiques-IA fuient avec des pancartes « ON DEMANDE L'ASILE »)*.
> *(le ton s'adoucit)* « Et lui, c'est Sanplerien. L'aîné. Le seul gentil. »
> « Pour Noël, il a eu une orange. » *(beat)* « En photo. »
> « Il a reçu une lettre d'amour, une fois. Mauvaise adresse. » *(beat)* « Il l'a gardée quand même. »
> 🎭 Catapulté vers un mur, radieux : « C'est le plus beau jour de ma vie. » CLAC.
> « …La sélection naturelle reprend ses droits. »

**P8 — Logo** *(titre doré, fissuré, roussi)* :
> « GROGNON. Un homme ? Un reptilien ? Son comptable ? » *(beat)* « On ne saura jamais. C'est mieux pour tout le monde. »
> « Interdite dans quatre pays. Invitée d'honneur à Davos. »
> **La famille la plus dysfonctionnelle du monde.**
> Noir : « …Giovannaaaa ? » → *« on mange quoi ce soir ? »* — Sanplerien *(depuis la cage)* : « …moi ? » — Grognon : « Hrrrr. » — Sanplerien : « cool. » CLAC. Noir.

---

## 2. LE SCRIPT — 8 PLANS (visuel détaillé)

> Chaque plan = un **prompt IMAGE** (ultra détaillé) + un **prompt ANIMATION** (mouvement simple + son).
> La **voix-off (VO)** grave de bande-annonce relie le tout et « explique » la famille.

### PLAN 0 — OUVERTURE NOIRE (~4 s) · 🟢
Écran noir (montage, pas de génération).
🔊 Respiration rauque dans le noir → « Hrrrr… » → gros raclement de gorge → silence.

---

### PLAN 1 — L'ARRIVÉE (~6 s) · 🟢
**IMAGE :**
```
Plan large cinématographique 9:16, contre-plongée. Longue limousine rose déglinguée,
dorures, rouille, chromes constellés de pluie, qui franchit un immense portail doré
ouvragé. Au-delà : allée pavée trempée qui reflète, fontaines baroques, statues,
lampadaires à gaz, manoir gothique sombre en silhouette sur un ciel d'orage. Brume,
feuilles mortes, god-rays. Rendu 3D cinéma Unreal Engine 5 / Octane, hyper réaliste,
ambiance épique et menaçante. Design cartoon exagéré conservé. 4K.
```
**ANIMATION :**
```
La limousine rose avance lentement et franchit le portail doré vers la caméra,
poussière et rayons de lumière, léger travelling avant, ralenti épique. Physique
réaliste, pas de morphing.
```
🔊 Fanfare orchestrale épique, tonnerre. **VO grave :** « Dans la famille la plus riche du monde… »

---

### PLAN 2 — GROGNON, LE PÈRE (~6 s) · 🟢 ✅ *(validé)*
**IMAGE :**
```
Grognon, colosse obèse 2m, debout de plein pied au centre de l'allée pavée mouillée,
face caméra, contre-plongée basse qui le rend titanesque. Crâne chauve en dôme
poreux, UN SEUL énorme mono-sourcil noir horizontal qui cache TOTALEMENT ses yeux,
petite bouche grognon, deux ÉNORMES pans de peau poreux pendants jusqu'au torse.
Costume trois pièces violet à rayures, gros boutons dorés, médaillon doré, pochette.
Gantelets steampunk (laiton, rivets) d'où sortent deux fouets tressés traînant au
sol. La limo rose garée en retrait à droite. Il pleut, flaques, portail doré, manoir
gothique, fontaines, brume, god-rays, liseré violet-or (rim light). Rendu 3D cinéma
Unreal Engine 5 / Octane, subsurface scattering, ray-tracing, 4K. Personnage cartoon
exagéré rendu ultra-réaliste, PAS un vrai humain.
```
**ANIMATION :**
```
Grognon marche lentement vers la caméra d'un pas lourd et grounded. Poids et inertie
réalistes : son corps massif se balance, ses deux pans de peau oscillent avec la
gravité à chaque pas, les fouets tressés se balancent. Yeux invisibles sous le
mono-sourcil. Brume qui s'écarte, léger travelling avant. Anatomie stable, PAS de
morphing. Audio : montée orchestrale grave, respiration rauque "Hrrrr".
```
🔊 **VO :** « …il y a le père. On ne voit jamais ses yeux. On sent juste sa colère. »

---

### PLAN 3 — GIOVANNA, LA PRINCESSE (~7 s) · 🟢 ✅ *(validé)*
**IMAGE :**
```
Giovanna, un BÉBÉ aux PROPORTIONS DE NOURRISSON très marquées (tête énorme, tout
petit corps ultra-rond, bras et jambes courts et boudinés, mains et pieds minuscules)
mais ÉNORME et obèse, TOUTE PETITE TAILLE — minuscule au milieu d'un grand hall
(arrive à peine à la hauteur des marches). Seule dans le plan. Visage poupon, joues
immenses, peau poreuse avec taches de rousseur. Presque chauve, une mèche + gros nœud
rose satiné. Mono-sourcil noir cachant TOTALEMENT ses yeux, petite bouche capricieuse.
Robe rose luxueuse à froufrous et dentelle, satin brillant, médaillon doré « G »,
bracelet de perles, chaussures roses vernies, petit sac rose « G ». Décor : grand hall
de palais ROSE ET OR, marbre rose, lustres en cristal, colonnes dorées, escalier de
velours rose, roses, pétales qui tombent. Lumière chaude, halo rose-doré. Rendu 3D
cinéma Unreal Engine 5 / Octane, ultra-réaliste, 4K. Personnage cartoon exagéré aux
proportions de bébé, PAS une adulte, PAS un vrai humain.
```
**ANIMATION :**
```
On voit clairement qu'elle a un MAL FOU à marcher : elle titube comme un bébé, jambes
écartées, se dandine lourdement en soufflant, vacille. Au bout de 2-3 pas elle BASCULE
et ROULE une fois sur elle-même comme une grosse boule rose (forme ronde stable, elle
roule comme une balle sans se déformer), puis se redresse à quatre pattes et repart en
titubant vers la caméra. Comique, ralenti. Poids et inertie réalistes, joues et jupon
qui rebondissent. Anatomie stable, PAS de morphing. Audio : cordes kitsch, sa voix
GRAISSEUSE mi-grave mi-aiguë et nasillarde "Giovannaaaa… Giovannaaa".
```
🔊 **VO :** « Sa fille adorée. La princesse. »

---

### PLAN 4 — GIOVANNI, LE BEAU GOSSE (~6 s) · 🟢 · CUT SEC
**IMAGE :**
```
Coupe sèche. Giovanni, un BÉBÉ aux proportions de nourrisson (grosse tête, petit corps
rond), qui se prend pour le plus beau. Costume blanc de luxe parfaitement repassé,
nœud papillon rose, montre en or, chaussures vernies blanches, une unique mèche
bouclée sur le crâne, menton relevé, air narcissique. Debout devant un grand miroir
doré. Décor : couloir d'école chic et luxueux, sol de marbre, casiers dorés, colonnes,
lumière du matin par de grandes fenêtres, reflets. Rendu 3D cinéma Unreal Engine 5 /
Octane, ultra-réaliste, 4K. Personnage cartoon exagéré aux proportions de bébé, PAS un
vrai humain. Étincelle sur ses dents.
```
**ANIMATION :**
```
Giovanni s'admire dans le miroir, ajuste son nœud papillon, recoiffe sa mèche unique
avec suffisance, puis envoie un baiser à son propre reflet. Mouvement lent et posé,
physique réaliste, anatomie stable, PAS de morphing. Audio : voix suave de star
"Giooovanniii…", petit "ting" d'étincelle.
```
🔊 **VO :** « Le plus beau garçon de l'école… d'après lui. »

---

### PLAN 5 — GIOVANNIA, LA POPULAIRE (~6 s) · 🟢
**IMAGE :**
```
Giovannia, un BÉBÉ mignon aux proportions de nourrisson, plus mince et gracieuse,
robe rose élégante, une mèche avec nœud rose, PAS de mono-sourcil, longs cils, sourire
en coin malicieux, petit sac de luxe. Elle passe dans un couloir d'école chic. En
retrait, Giovanni (bébé en costume blanc) la regarde. Décor : couloir d'école luxueux,
marbre, casiers dorés, grandes fenêtres, contre-jour glamour, petits cœurs et
étincelles. Rendu 3D cinéma Unreal Engine 5 / Octane, ultra-réaliste, 4K. Personnages
cartoon exagérés aux proportions de bébé, PAS de vrais humains.
```
**ANIMATION :**
```
Giovannia passe devant Giovanni d'une démarche glamour au ralenti, lui lance un regard
en coin et un sourire. Ils se fixent comme dans une romance hollywoodienne, contre-jour,
cœurs et étincelles flottants. Mouvement simple et fluide, anatomie stable, PAS de
morphing. Audio : cordes romantiques, elle dit "Giovannia…" douce et prétentieuse.
```
🔊 **VO :** « Celle que tout le monde regarde. »

---

### PLAN 6 — GIOVANNA JALOUSE (~4 s) · 🟢 · EXPLOSION
**IMAGE :**
```
Gros plan serré sur le visage de Giovanna (bébé géant, mono-sourcil cachant les yeux,
nœud rose). Décor flou du couloir d'école / palais rose derrière. Rendu 3D cinéma
ultra-réaliste, 4K. Personnage cartoon exagéré, PAS un vrai humain.
```
**ANIMATION :**
```
Snap-zoom brutal sur son visage. Ses joues gonflent, elle devient rouge de rage, tout
son corps tremble de jalousie cartoon. Mouvement bref et net, anatomie stable, PAS de
morphing. Audio : disque rayé (record scratch) puis hurlement furieux
"GIOVANNNAAAAAAAAAA !!".
```
🔊 **VO :** « …et celle que personne ne regarde. »

---

### PLAN 7 — SANPLERIEN (~7 s) · 🟡 *(surveiller le filtre)*
**IMAGE :**
```
Sanplerien, grand et très maigre, cheveux blond/châtain en bataille, visage sale,
immenses yeux tristes au bord des larmes, deux grandes dents de devant, t-shirt et
short déchirés, pieds nus. Assis tant bien que mal dans un caddie de supermarché
rouillé attaché par une chaîne derrière la limousine rose, sur une route de campagne.
Décor : longue route, champs flous, poteaux, nuage de poussière, ciel de fin de
journée. Rendu 3D cinéma Unreal Engine 5 / Octane, ultra-réaliste, 4K. Personnage
cartoon exagéré, PAS un vrai humain.
```
**ANIMATION :**
```
Coupe brutale. Le caddie tiré à toute vitesse rebondit violemment sur la route, et
Sanplerien est ballotté et rebondit comme du caoutchouc, façon slapstick cartoon
élastique, nuage de poussière, énergie "wacky races". Il crie "AAAAHH !". À la fin, un
coup de fouet claque HORS-CHAMP (son seul, aucun contact montré). Comique, zéro
douleur, zéro sang. Anatomie stable. Audio : musique de course frénétique, bruits de
rebonds, "AAAAHH", un "CLAC !" sec de fouet hors-champ.
```
🔊 **VO :** « Et puis… il y a lui. » *(ton qui chute — le seul gentil, le souffre-douleur)*

---

### PLAN 8 — NOIR FINAL + LOGO (~5 s) · 🟢
Écran noir (montage), puis apparition du logo.
🔊 Dans le noir → « Hrrrr… » + un « CLAC ! » sec → silence → puis, tout petit : « …Giovannaaaa ? »
🎨 Logo **GROGNON** (lettrage luxe violet & or) + sous-titre :
> **GROGNON — La famille la plus dysfonctionnelle du monde.**

---

## 3. MONTAGE, MUSIQUE & VOIX

**Rythme :** cuts secs entre les persos (c'est le gag — chacun dans son monde). Accélération progressive jusqu'au chaos du Plan 7, coupe nette, silence, logo.

**Musique :** UNE seule montée orchestrale épique-parodique qui enfle du Plan 1 au Plan 6, **coupe net au CLAC** (Plan 7), silence, puis sting final sur le logo.

**Voix-off :** grave, sérieuse, façon bande-annonce de blockbuster — le contraste avec l'absurde fait l'humour. À générer à part (ElevenLabs) et caler au montage.

**Voix persos :** générées séparément pour un contrôle total (graisseuse pour Giovanna, rauque pour Grognon, qui mue pour Sanplerien, star pour Giovanni, douce-prétentieuse pour Giovannia), puis synchronisées.

**Table de montage :**

> VO = version définitive (§1★). Ci-dessous = repères courts pour le montage.

| # | Plan | Durée | VO (repère) | Son perso | État |
|---|------|-------|-----|-----------|------|
| 0 | Noir | 4 s | « …remboursement. » | « Hrrrr » | ⬜ |
| 1 | Limo/portail | 6 s | « …le crime d'origine / crypto… » | fanfare | ⬜ |
| 2 | Grognon | 6 s | « …il voit tout » + 🦎 flash reptilien | « Hrrrr » | ✅ |
| 3 | Giovanna | 7 s | « …mangé sa jumelle. Par gourmandise. » | « Giovannaaaa » (graisseuse) | ✅ |
| 4 | Giovanni | 6 s | « …la sienne. Dans un miroir. » | « Giovanniii » | ⬜ |
| 5 | Giovannia | 6 s | « …11 cœurs brisés. Elle est en CP. » | « Giovannia » | ⬜ |
| 6 | Giovanna jalouse | 4 s | « …déduis ça des impôts. » | « GIOVANNNAAAA !! » | ⬜ |
| 7 | Sanplerien | 7 s | « …une orange. En photo. » + chaos | « merci » + CLAC | ⬜ |
| 8 | Logo | 5 s | « homme ? reptilien ? son comptable ? » | « …moi ? » → « cool. » | ⬜ |

---

## 4. WORKFLOW DE PRODUCTION (ordre conseillé)
1. **Figer une réf 3D on-model** par perso (comme Grognon & Giovanna déjà faits).
2. Générer le **start frame** de chaque plan (image ultra-détaillée ci-dessus).
3. **Animer** chaque frame (prompt animation, 2-3 variantes, garder la meilleure).
4. Générer **voix + bruitages + musique** à part.
5. **Monter** en 9:16 (CapCut/DaVinci), caler l'audio, ajouter le logo.
6. **Upscaler** le tout (Topaz) → export final 1080p/4K.

**Fait :** Plan 2 (Grognon) ✅ · Plan 3 (Giovanna) ✅
**Reste :** Plans 1, 4, 5, 6, 7 + voix + musique + montage.
