# NOBLE חשבונות – דשבורד

דשבורד הוצאות חי המתחבר ישירות ל-Google Sheets.

## 🚀 העלאה ל-GitHub Pages (5 דקות)

### שלב 1 – פתח את ה-Sheet לציבור
1. פתח את Google Sheet שלך
2. לחץ **Share** (שיתוף) → **Change to anyone with the link**
3. ודא שההרשאה היא **Viewer** בלבד

### שלב 2 – צור Repository ב-GitHub
1. היכנס ל-[github.com](https://github.com) → **New repository**
2. שם: `noble-dashboard` (או כל שם אחר)
3. בחר **Public**
4. לחץ **Create repository**

### שלב 3 – העלה את הקובץ
1. בדף ה-repository לחץ **Add file** → **Upload files**
2. גרור את קובץ `noble_dashboard_live.html`
3. **שנה את שם הקובץ ל-** `index.html` לפני ההעלאה
4. לחץ **Commit changes**

### שלב 4 – הפעל GitHub Pages
1. לך ל-**Settings** של ה-repository
2. בתפריט הצדדי: **Pages**
3. תחת **Source**: בחר **Deploy from a branch**
4. Branch: **main** | Folder: **/ (root)**
5. לחץ **Save**

### שלב 5 – קבל את הקישור
אחרי ~2 דקות תקבל קישור בצורה:
```
https://YOUR_USERNAME.github.io/noble-dashboard/
```

## 🔄 עדכון נתונים
- הדשבורד שולף נתונים מ-Google Sheets בכל טעינה
- מתרענן אוטומטית כל 5 דקות
- כפתור ↺ לרענון ידני

## 📊 מה יש בדשבורד
- כרטיסי KPI: סה"כ הוצאות, אשראי, קופה, הכנסות, יתרה
- סינון לפי: חודש, קטגוריה, אמצעי תשלום, מקור, טווח תאריכים, חיפוש חופשי
- מיון לפי כל עמודה
- גרף הוצאות לפי חודש (לחיצה מסננת)
- גרף קטגוריות מתעדכן לפי סינון
- סיכום קופה קטנה ורשימת הכנסות
