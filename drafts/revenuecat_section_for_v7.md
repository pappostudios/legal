# RevenueCat text removed from the v6 drafts, for privacy v7 (app 1.6.1)

App 1.6.0 ships without RevenueCat, so this text left `privacy_policy_v6.html` and `delete_account.html`. It is
copied here unchanged from `v6-draft` at `167caab`. Section numbers are the v6 ones. Check the facts against the
1.6.1 code before reusing it: what is sent, and which user id (it assumes the Firebase uid, which arrives with the
login work).

## privacy_policy_v6.html

### "מה השתנה בגרסה זו"

```html
<li><strong>רכישות:</strong> הוספנו את RevenueCat, שירות שמנהל עבורנו את מצב הרכישות והמנויים, כדי שפרו יעבוד בכל המכשירים שלכם ונדע על ביטולים והחזרים (סעיף 5).</li>
```

### Section 2א, the sentence

```html
מדידת השימוש והרכישות פועלות בנפרד, כמפורט בסעיפים 4 ו-5.
```

### Section 5, all of it

```html
<h2>5. רכישות ומנויים — RevenueCat</h2>
<p>כדי לנהל את הגישה לפרו בכל המכשירים שלכם ולזהות ביטולים והחזרים, אנחנו משתמשים בשירות של RevenueCat, Inc.</p>
<ol type="a">
  <li><strong>מה נמסר ל-RevenueCat:</strong> מצב הרכישה והמנוי, המוצר, התאריכים, מזהי העסקה בחנות, שפת המכשיר והמטבע, פרטים טכניים בסיסיים של המכשיר, ומזהה משתמש באפליקציה: מזהה המשתמש של Firebase אם התחברתם, ואחרת מזהה אקראי.</li>
  <li><strong>פרטי התשלום:</strong> מטופלים על ידי Apple ו-Google בלבד. הם אינם מגיעים אלינו ואינם מגיעים ל-RevenueCat.</li>
  <li><strong>מקום העיבוד:</strong> RevenueCat מעבדת את הנתונים מחוץ לישראל, בארצות הברית.</li>
</ol>
```

### Section 10ה

```html
<li><strong>רישומי רכישות:</strong> מחיקת החשבון אינה מוחקת את רישומי הרכישות אצל Apple, Google ו-RevenueCat, ואינה מבטלת מנוי פעיל. אפשר לבקש מאיתנו בדוא"ל למחוק את הרשומה שלכם ב-RevenueCat.</li>
```

### Section 12א, the sentence

```html
מדידת השימוש ורישום הרכישות פועלים בלי קשר לחשבון, כמפורט בסעיפים 4 ו-5.
```

### Section 12ב, the purpose

```html
ניהול הגישה לפרו וזיהוי ביטולים והחזרים,
```

### Section 12ג, the recipients

```html
<li><strong>מקבלי המידע:</strong> Google, המספקת לנו הזדהות ואחסון (Firebase), מדידת שימוש (Firebase Analytics) ודוא"ל (Gmail), ו-RevenueCat, Inc., המנהלת עבורנו את מצב הרכישות. Apple ו-Google מטפלות ברכישות עצמן. איננו מוסרים את המידע לאף גורם נוסף, ואיננו מוכרים אותו.</li>
```

### Section 12ד

```html
<li><strong>מקום האחסון:</strong> המידע נשמר ומעובד בשרתים של Google ושל RevenueCat, שעשויים להיות ממוקמים מחוץ לישראל.</li>
```

## delete_account.html

### Section 4א

```html
<li><strong>רישומי רכישות ומנויים:</strong> הרישומים של הרכישות והמנויים נשמרים אצל Apple ואצל Google, וכן אצל RevenueCat, השירות שמנהל עבורנו את מצבם. מחיקת החשבון אינה מוחקת אותם. אפשר לבקש מאיתנו בדוא"ל למחוק את הרשומה שלכם ב-RevenueCat. מחיקת החשבון אינה מבטלת מנוי פעיל, ואיננו יכולים לבטל מנוי עבורכם. את המנוי יש לבטל בהגדרות החנות (App Store או Google Play), לפני המחיקה או אחריה.</li>
```
