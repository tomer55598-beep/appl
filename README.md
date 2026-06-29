# לוח-יום — React/Vite

פרויקט מלא שמכיל את האפליקציה עם:

- משימות
- תזונה יומית
- מים יומיים
- משקל
- היסטוריה של ימי תזונה ושתייה
- תמיכה בהתקנה למסך הבית כ־PWA

## הרצה במחשב

```bash
npm install
npm run dev
```

אחרי ההרצה יופיע קישור מקומי, בדרך כלל:

```bash
http://localhost:5173
```

## בנייה לפרסום

```bash
npm run build
```

## העלאה ל־GitHub/Vercel

1. העלה את כל התיקייה ל־GitHub.
2. ב־Vercel לחץ Import Project.
3. בחר את הריפו.
4. Framework Preset: Vite.
5. Build Command: `npm run build`.
6. Output Directory: `dist`.
7. Deploy.

## התקנה בטלפון

אחרי שהאתר באוויר:

### iPhone
פתח בספארי → Share → Add to Home Screen.

### Android
פתח בכרום → שלוש נקודות → Add to Home screen / Install app.

## איפה נשמרים הנתונים?

הנתונים נשמרים בדפדפן המקומי דרך `localStorage`. אם תמחק נתוני אתר/דפדפן, הנתונים יימחקו.
