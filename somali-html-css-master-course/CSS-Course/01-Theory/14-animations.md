# Cashar 14: Animations

## Ujeeddo
Faham fikradda **Animations** oo ku dabaq tusaale dhab ah.

## Theory — Sharaxaad
@keyframes waxay qeexdaa dhaqdhaqaaq. Ixtiraam prefers-reduced-motion.

## Tusaale
```css
@keyframes fadeIn { from { opacity: 0; } to { opacity: 1; } }
.card { animation: fadeIn .5s ease; }
@media (prefers-reduced-motion: reduce) { *, *::before, *::after { animation-duration: .01ms !important; transition-duration: .01ms !important; } }
```

## Layli
1. Akhri sharaxaadda, kuna qor saddex qodob oo aad fahantay.
2. Fur faylka code-ka casharkan oo tijaabi.
3. Wax ka beddel ugu yaraan laba meelood oo eeg natiijada.

## Su’aalo is-hubin
- Maxay tahay shaqada fikraddan?
- Goorma ayaad ku isticmaali lahayd website?
- Maxaa dhacaya haddii aad ka saarto qayb ka mid ah code-ka?
