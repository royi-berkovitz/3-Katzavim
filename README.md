# שלושה קצבים — אתר סטטי

אתר סטטי לגמרי, ללא build. מעלים את התיקייה כמו שהיא ל-GitHub ומחברים ל-Vercel.

## העלאה
1. חלצו את ה-ZIP. תוכן התיקייה (index.html, assets/, data/ וכו') צריך להיות בשורש הריפו.
2. Vercel → Add New Project → בחירת הריפו.
3. Framework Preset: **Other**. Build Command: ריק. Output Directory: ריק (שורש).
4. Deploy.

## עמודים
| קובץ | עמוד |
|---|---|
| index.html / Home.dc.html | עמוד הבית |
| Cuts.dc.html | הנתחים שלנו |
| Category.dc.html?cat=beef / poultry / lamb / fish | קטגוריה |
| Recipes.dc.html | מה על האש? |
| Recipe.dc.html?slug=… | מתכון |
| ShoppingList.dc.html | רשימת קניות (נפתח מעמוד מתכון) |
| Tips.dc.html | טיפים מהקצבים |
| Story.dc.html | הסיפור שלנו |
| Branch.dc.html?b=holon / givat | סניף |
| Kosher.dc.html | כשרות |
| Club.dc.html | מועדון הלקוחות |
| Contact.dc.html | צור קשר |
| Gallery.dc.html | גלריה |

SiteHeader.dc.html / SiteFooter.dc.html — רכיבים משותפים, נטענים בכל עמוד. support.js — חובה, נטען בכל עמוד.

## תוכן
- data/content.json — מתכונים, טיפים, קטגוריות, סניפים ושעות.
- assets/ — תמונות ווידאו. חלק מהתמונות נטענות ישירות מ-3katzavim.web3d-studio.co.il / 3katzavim.co.il — הדומיינים צריכים להישאר זמינים (או להעתיק את הקבצים מקומית).

## פתוח
- גלריה: לחיבור אינסטגרם — כתובת פיד (Behold / SnapWidget) בפרופ feedUrl ב-Gallery.dc.html; כתובת החשבון ב-igUrl.
- 28 מתכונים בלי מצרכים/שלבים — מקשרים למתכון המקורי.
- נוסח כשרות והטבות מועדון — לאישור הבעלים.
