# Code snippets

A quick console scraper to get your shopping list out of the Google Home shopping list app.

```javascript
Array.from(document.querySelectorAll('.listItemTitle')).reduce((l,i) => l + `${i.textContent}`.trim() + "\n", '')
```

Ordinal number modifiers in JS

```javascript
const getGetOrdinal = n => {
   const s=["th","st","nd","rd"],
       v=n%100;
   return n+(s[(v-20)%10]||s[v]||s[0]);
}
```

