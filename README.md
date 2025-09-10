# Composant Pricing Card

Un composant de carte tarifaire réutilisable, accessible et responsive, construit avec HTML/CSS pur.

## Fonctionnalités

- **3 variantes** : Starter (vert), Basic (bleu), Pro (violet)
- **Responsive design** : S'adapte à tous les écrans
- **Accessibilité WCAG 2.1 AA** : Navigation clavier, lecteurs d'écran
- **Variables CSS** : Personnalisation facile des couleurs et espacements
- **Méthodologie BEM** : Structure claire et maintenable

## Utilisation

### Structure de base

```html
<article class="pricing-card pricing-card--[variante]">
    <div class="pricing-card__badge">Badge</div>
    <div class="pricing-card__header">
        <h2 class="pricing-card__title">Titre</h2>
        <p class="pricing-card__subtitle">Description</p>
        <p class="pricing-card__price">€9.99 / mois</p>
    </div>
    <ul class="pricing-card__features">
        <li class="pricing-card__feature">Fonctionnalité</li>
    </ul>
    <a href="#" class="pricing-card__cta">Commencer l'essai</a>
</article>
```

### Créer une nouvelle variante

```css
.pricing-card--nouvelle-variante {
    --pricing-accent: #votre-couleur;
    --pricing-accent-hover: #votre-couleur-hover;
    --pricing-accent-light: #votre-couleur-claire;
}
```

## Personnalisation

### Variables disponibles

- **Couleurs** : `--pricing-accent`, `--pricing-accent-hover`, `--pricing-accent-light`
- **Typographie** : `--pricing-font-size-*`, `--pricing-font-weight-*`
- **Espacement** : `--pricing-space-*`, `--pricing-padding-*`
- **Bordures** : `--pricing-border-width-*`, `--pricing-radius-*`
- **Ombres** : `--pricing-shadow-*`

## Responsive

- **Mobile** : 1 colonne, padding réduit
- **Tablette** : 2-3 colonnes selon l'espace
- **Desktop** : 3 colonnes optimales

## Accessibilité

- Navigation clavier complète
- Support des lecteurs d'écran
- Contraste WCAG AA
- Focus visible
- Rôles ARIA appropriés

## Compatibilité

- Tous navigateurs modernes
- CSS Grid et Flexbox
- Variables CSS (CSS Custom Properties)

---

*Composant développé avec les meilleures pratiques d'accessibilité et de performance.*# Bonnes-pratiques-

