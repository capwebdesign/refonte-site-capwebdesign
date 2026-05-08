## Nouvelle charte Graphique - CapWebDesign

Ce document recense l'ensemble des éléments visuels du thème "Premium Dark" conçu pour CapWebDesign. Ces paramètres sont à intégrer dans les réglages globaux de votre constructeur de page (Blocksy/Spectra).

**1. Typographie**

Le site utilise une typographie unique, moderne et très lisible, idéale pour le web et les interfaces techniques.

Police principale (Titres et Corps de texte) : Inter (Google Fonts)

Graisses (Weights) utilisées :

300 (Light) : Textes très secondaires (rare).

400 (Regular) : Corps de texte standard, paragraphes.

500 (Medium) : Sous-titres, petits labels, liens de menu.

600 (Semi-Bold) : Boutons, titres de cartes, éléments mis en avant.

700 (Bold) : Titres de sections (H2, H3), prix.

800 (Extra-Bold) : Titre principal géant (H1), montants des prix.

**2. Palette de Couleurs : La Marque (Bleus)**

Ces couleurs constituent l'identité de CapWebDesign. Le bleu inspire la confiance, la technologie et le professionnalisme.

Bleu Principal (Boutons, icônes actives) : #3b82f6 (Variable: --brand-500)

Bleu Interaction (Survol des boutons) : #2563eb (Variable: --brand-600)

Bleu Lumineux (Textes en surbrillance, icônes) : #60a5fa (Variable: --brand-400)

Bleu Très Clair (Fonds discrets au survol) : #dbeafe (Variable: --brand-100)

Bleu Sombre (Fonds de cartes Premium) : #1e3a8a (Variable: --brand-900)

Cyan (Utilisé pour les dégradés éclatants) : #67e8f9 (Variable: --cyan-300)

**3. Palette de Couleurs : Les Fonds (Mode Sombre / Slate)**

Une déclinaison de gris-bleutés (Ardoise) qui donne ce rendu "Premium" très doux pour les yeux, moins agressif qu'un noir pur.

Fond Principal du site : #0f172a (Variable: --dark-900)

Fond Secondaire (Cartes, FAQ, Sections alternées) : #1e293b (Variable: --dark-800)

Bordures et Séparateurs : #334155 (Variable: --dark-700)

Bordures au survol : #475569 (Variable: --dark-600)

**4. Palette de Couleurs : Les Textes**

Texte Principal (Titres, H1, H2, H3) : #f8fafc (Blanc très légèrement cassé)

Texte Secondaire (Paragraphes, descriptions) : #94a3b8 (Gris clair/bleuté)

Texte Tertiaire (Mentions légales, petits labels) : #64748b (Gris moyen)

Texte Mis en avant (Highlight discret) : #cbd5e1

**5. Couleurs d'Accentuation (Catégories / Métiers)**

Utilisées dans le bloc "Nos Réalisations" pour différencier visuellement les secteurs d'activité, toujours associées à un fond transparent à 10%.

Plomberie (Bleu) : #60a5fa — Fond : rgba(96, 165, 250, 0.1)

Paysagiste (Vert) : #34d399 — Fond : rgba(52, 211, 153, 0.1)

Électricité (Jaune/Or) : #fbbf24 — Fond : rgba(251, 191, 36, 0.1)

Couverture/Toiture (Rouge/Corail) : #f87171 — Fond : rgba(248, 113, 113, 0.1)

**6. Dégradés (Gradients)**

Dégradé de Titre (H1 "artisans et indépendants") :

Linéaire vers la droite (to right).

Couleur de départ : #60a5fa

Couleur d'arrivée : #67e8f9

Dégradé Carte Tarifaire Premium ("L'Acquisition") :

Linéaire vers le bas (to bottom).

Couleur de départ : #1e3a8a

Couleur d'arrivée : #1e293b

Lueurs de fond (Hero Section & Contact - "Blob") :

Radial.

Couleur centrale : rgba(59, 130, 246, 0.15) (Bleu avec 15% d'opacité).

Fondu vers : rgba(15, 23, 42, 0) (Transparent).

**7. Effets UI (Bordures et Ombres)**

Ces paramètres donnent de la profondeur et du "rebond" à votre maquette.

Arrondis (Border-Radius) :

Boutons et Badges : Complètement ronds (9999px ou "Pilule").

Grandes Cartes (Tarifs, Contact) : 24px (1.5rem).

Petites Cartes (Services, Maquettes, Avis) : 16px (1rem).

Icônes et Champs de formulaire : 12px (0.75rem) ou 8px (0.5rem).

Ombres Portées (Box-Shadow) :

Bouton Principal : 0 4px 14px rgba(59, 130, 246, 0.3) (Ombre bleue diffuse).

Survol des Cartes : 0 20px 25px -5px rgba(59, 130, 246, 0.1) (Ombre bleutée large).

Bloc Contact : 0 20px 25px -5px rgba(0, 0, 0, 0.3) (Ombre noire profonde pour le détacher).

Effet Verre (Glassmorphism sur le Header) :

Couleur de fond : #0f172a avec opacité à 85%.

Flou d'arrière-plan (Backdrop-filter) : 12px.

**8. Guide de Transposition : WordPress + Blocksy + Spectra**

Cette section vous explique exactement où et comment intégrer la charte graphique dans vos outils pour reproduire fidèlement la maquette HTML.

Étape 1 : Réglages Globaux dans Blocksy (Apparence > Personnaliser)

Blocksy gère la "fondation" du site. En configurant cela en premier, Spectra héritera automatiquement de vos styles.

**A. Couleurs (Global Colors) :**
Remplissez la Palette de base (Global Palette) de Blocksy dans cet ordre :

Couleur Primaire (Color 1) : #3b82f6 (Bleu Principal)

Couleur Secondaire (Color 2) : #2563eb (Bleu Survol)

Texte Initial (Text Color) : #94a3b8 (Texte Secondaire)

Titres (Heading Color) : #f8fafc (Texte Principal)

Bordures (Border Color) : #334155

Fond du Site (Site Background) : #0f172a (Fond Principal)

**B. Typographie (Typography) :**

Police de base (Base Font) : Famille : Inter / Graisse : 400 / Taille de base : 16px.

Titres (Headings) : Famille : Inter / Graisse : 700 (H2, H3). Laissez H1 à 800.

**C. Boutons (Buttons) :**

Type : Rempli (Filled).

Couleur de fond : Palette Couleur 1 (Normale) / Couleur 2 (Survol).

Rayon de bordure (Border Radius) : Lier les valeurs et mettre 100px ou 9999px pour l'effet "Pilule".

Ombre portée (Box Shadow) : Activer l'ombre. Couleur : #3b82f6, Opacité : 30%, Décalage Y : 4px, Flou : 14px.

**D. En-tête (Header) :**

Ligne Principale (Main Row) : Dans l'onglet Design, définissez la couleur de fond sur #0f172a à 85% d'opacité.

Effet Verre : Activez l'option "Effet de flou en arrière-plan" (Backdrop Filter) si disponible dans Blocksy Pro, sinon un CSS additionnel sera nécessaire (backdrop-filter: blur(12px);).

Menu : Couleur du texte par défaut à #94a3b8, au survol à #f8fafc.

Étape 2 : Réglages Globaux dans Spectra (Paramètres Spectra)

Avant de construire vos pages, assurez-vous que Spectra s'aligne sur Blocksy.

Héritage : Dans les réglages de Spectra, vérifiez que l'option "Hériter des couleurs et de la typographie du thème" est bien activée.

Largeur du Conteneur : Définissez la largeur globale du conteneur (Global Container Width) sur 1200px (cela correspond au --container-max de la maquette).

Étape 3 : Construction des Blocs avec Spectra

Voici les correspondances pour recréer les blocs de la maquette :

A. Les Sections (Fonds alternés) :

Utilisez le bloc "Conteneur" (Container) de Spectra.

Réglez-le sur "Pleine largeur" avec un conteneur interne "Encadré" (Boxed).

Pour la couleur de fond (Onglet Style > Arrière-plan) : alternez entre vide (hérite du #0f172a de Blocksy) et #1e293b (Fond Secondaire) pour bien séparer les zones (ex: FAQ, Services).

B. Les Cartes (Services, Maquettes, Avis) :

Utilisez un bloc "Conteneur" enfant (ou le bloc "Boîte d'info" de Spectra).

Fond : #1e293b ou #0f172a (selon la section mère).

Bordure : Continue, 1px, couleur #334155. Au survol (Hover), passez la bordure à #3b82f6 (Bleu Principal).

Rayon (Border Radius) : 16px.

Ombre (Box Shadow) - Onglet Survol (Hover) : Décalage Y : 20px, Flou : 25px, Couleur #3b82f6 avec 10% d'opacité.

C. Dégradé de texte (Le H1) :

Sélectionnez votre titre principal dans Spectra (bloc Titre avancé).

Dans l'onglet Style, au lieu d'une couleur unie, choisissez Dégradé.

Angle : 90° (vers la droite). Couleur 1 : #60a5fa / Couleur 2 : #67e8f9.

D. Les Icônes colorées (Bloc "Nos réalisations") :

Dans un bloc "Boîte d'info" Spectra, utilisez les réglages de l'icône.

Couleur de l'icône : ex. #60a5fa (Plomberie).

Couleur de fond de l'icône : utilisez la même couleur mais baissez la jauge d'opacité (Alpha) à 0.10 (10%).

Arrondi de l'icône : 12px.
