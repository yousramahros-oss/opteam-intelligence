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

## 1★. COUCHE COMÉDIE — VO vacharde + gags (★ LA VERSION À UTILISER ★)

> **Ton visé :** humour noir, second degré, vache — façon Simpson mais plus méchant.
> **Moteur comique :** une voix-off ultra-sérieuse et pompeuse qui vend des horreurs
> comme du luxe. Plus c'est grave dit, plus c'est drôle. (Le visuel reste celui,
> ultra-détaillé, de la section 2 ci-dessous ; ici on ajoute la VO et les gags.)

### Les 3 armes comiques (à garder sur TOUT le teaser)
1. **Running gag du fouet** — Grognon ponctue chaque transition d'un CLAC sur
   Sanplerien en arrière-plan, l'air de rien (cruauté de fond façon Simpson).
2. **La VO qui vend l'horreur comme du luxe** (second degré permanent).
3. **L'escalade** — ça commence « journée chic normale », ça finit en chaos absurde.

### VO + gags, plan par plan

**P0 (noir)** — « Hrrrr… » *(raclement de gorge)*

**P1 (limo)** — VO grave et solennelle :
> « Dans la famille la plus riche du monde… l'argent ne fait pas le bonheur. »
> *(beat)* « Il fait bien mieux. Il fait souffrir les autres. »
> 🎭 GAG : la limo est si longue qu'elle franchit encore le portail 6 s plus tard.

**P2 (Grognon)** :
> « Voici Grognon. Milliardaire. Tyran. Et, accessoirement, père. »
> 🎭 GAG : il fait « coucou » d'une main à Giovanna, plein d'amour, pendant que son
> autre gantelet fouette Sanplerien hors-champ — CLAC — sans tourner la tête (il n'a
> pas d'yeux de toute façon).

**P3 (Giovanna)** :
> « Sa fille chérie. Un petit ange. Un petit trésor. Un petit quintal. »
> 🎭 GAG : elle ne descend pas, elle TOMBE et ROULE comme un rocher, écrase un massif
> de roses. Grognon essuie une larme de fierté.

**P4 (Giovanni)** :
> « Giovanni est le plus beau garçon de l'école. C'est lui qui l'a décidé. »
> 🎭 GAG : il embrasse son reflet, le miroir se fissure ; étincelle sur sa dent —
> ting — un élève s'écroule au fond, aveuglé.

**P5 (Giovannia)** :
> « Giovannia, la plus populaire. Et la seule, dans ce teaser, à être objectivement
> mignonne. »
> 🎭 GAG : elle passe au ralenti, pétales, un couloir entier de bébés tombe en
> pâmoison.

**P6 (Giovanna jalouse)** :
> « Giovanna est persuadée que Giovanni l'aime. »
> *(cut sec sur Giovanni qui mime un haut-le-cœur)*
> « Giovanni, lui, a déjà changé d'école trois fois. »
> → « GIOVANNNAAAAAAAA !! »

**P7 (Sanplerien)** — le ton chute, l'air de rien :
> « Ah. Et il y a Sanplerien. Le seul gentil de la famille. »
> *(beat)* « C'est sûrement pour ça qu'ils l'aiment pas. »
> « Il dort dans une cage, va à l'école en caddie, se fait fouetter pour un oui, pour
> un non… » *(beat)* « …surtout pour rien. »
> 🎭 GAG : ballotté à 120 km/h dans le caddie, il adresse un petit POUCE LEVÉ résigné
> à la caméra. CLAC.

**P8 (logo)** — « Hrrrr… » + CLAC + silence.
> **GROGNON — La famille la plus dysfonctionnelle du monde.**
> *(kicker, en petit, après un temps)* « À côté, la vôtre est parfaite. »
> *Dernier souffle dans le noir : « …Giovannaaaa ? » — CLAC.*

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

| # | Plan | Durée | VO | Son perso | État |
|---|------|-------|-----|-----------|------|
| 0 | Noir | 4 s | — | « Hrrrr » + raclement | ⬜ |
| 1 | Limo/portail | 6 s | « …la plus riche du monde… » | fanfare | ⬜ |
| 2 | Grognon | 6 s | « …le père. » | « Hrrrr » | ✅ |
| 3 | Giovanna | 7 s | « …la princesse. » | « Giovannaaaa » (graisseuse) | ✅ |
| 4 | Giovanni | 6 s | « …le plus beau, d'après lui. » | « Giovanniii » | ⬜ |
| 5 | Giovannia | 6 s | « …que tout le monde regarde. » | « Giovannia » | ⬜ |
| 6 | Giovanna jalouse | 4 s | « …que personne ne regarde. » | « GIOVANNNAAAA !! » | ⬜ |
| 7 | Sanplerien | 7 s | « …il y a lui. » | « AAAHH » + CLAC | ⬜ |
| 8 | Logo | 5 s | « La famille la plus dysfonctionnelle du monde. » | « …Giovannaaaa ? » | ⬜ |

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
