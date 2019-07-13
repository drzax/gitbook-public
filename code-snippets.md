# Code snippets

A quick console scraper to get your shopping list out of the Google Home shopping list app.

```javascript
Array.from(document.querySelectorAll('.listItemTitle')).reduce((l,i) => l + `${i.textContent}`.trim() + "\n", '')
```

