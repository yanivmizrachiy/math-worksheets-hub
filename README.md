# 🎓 Math Worksheets Hub | מרכז דפי העבודה במתמטיקה

[![MIT License](https://img.shields.io/badge/License-MIT-green.svg)](https://choosealicense.com/licenses/mit/)
[![GitHub Stars](https://img.shields.io/github/stars/yanivmizrachiy/math-worksheets-hub.svg)](https://github.com/yanivmizrachiy/math-worksheets-hub/stargazers)
[![Issues](https://img.shields.io/github/issues/yanivmizrachiy/math-worksheets-hub.svg)](https://github.com/yanivmizrachiy/math-worksheets-hub/issues)

> **מרכז מאוחד לכל דפי העבודה במתמטיקה - תבניות, כלי יצירה אוטומטיים, ודפי תרגול מוכנים לכיתות ז'-י"ב**

## 📖 אודות הפרויקט

**Math Worksheets Hub** הוא פרויקט מאוחד שמרכז את כל המשאבים שלך ליצירת דפי עבודה במתמטיקה במקום אחד.
הפרויקט כולל:

- 📝 **תבניות מוכנות** - מאות תבניות לנושאים שונים
- 🤖 **כלי יצירה אוטומטי** - צור דפי עבודה מותאמים אישית בקליק
- 📚 **דפי תרגול מוכנים** - מאגר עצום של דפי עבודה מוכנים לכיתות ז'-י"ב
- 🎯 **ארגון לפי כיתות ונושאים** - מבנה ברור ונגיש

---

## 🏗️ מבנה הפרויקט

```
math-worksheets-hub/
├── README.md
├── templates/              # תבניות דפי עבודה
│   ├── algebra/           # אלגברה
│   ├── geometry/          # גיאומטריה
│   ├── calculus/          # חשבון אינפיניטסימלי
│   └── general/           # כללי
├── worksheets/            # דפי עבודה מוכנים
│   ├── grade-7/          # כיתה ז'
│   ├── grade-8/          # כיתה ח'
│   ├── grade-9/          # כיתה ט'
│   ├── grade-10/         # כיתה י'
│   ├── grade-11/         # כיתה י"א
│   └── grade-12/         # כיתה י"ב
├── generator/             # כלי יצירה אוטומטי
│   ├── index.html        # ממשק היצירה
│   ├── js/               # לוגיקה
│   └── css/              # עיצוב
├── assets/               # תמונות ומשאבים
└── docs/                 # תיעוד
```

---

## 🚀 תכונות עיקריות

### ✨ מה כולל הפרויקט?

#### 📝 תבניות מוכנות לשימוש
- תבניות HTML/PDF מעוצבות
- תמיכה בעברית RTL מלאה
- נושאים: אלגברה, גיאומטריה, חשבון דיפרנציאלי ואינטגרלי, סטטיסטיקה ועוד

#### 🤖 כלי יצירה אוטומטי
- ממשק משתמש ידידותי
- יצירת דפי עבודה בהתאמה אישית
- ייצוא ל-PDF/HTML
- שמירת תבניות מותאמות אישית

#### 📚 מאגר דפי תרגול
- מאות דפי עבודה מוכנים
- מסווג לפי כיתות (ז'-י"ב)
- מסווג לפי נושאים
- כולל פתרונות מפורטים

#### 🎯 ארגון חכם
- חיפוש מהיר לפי נושא/כיתה
- סימון דפי עבודה מועדפים
- מערכת תיוג

---

## 💻 התחלה מהירה

### דרישות מקדימות
- דפדפן מודרני (Chrome, Firefox, Edge, Safari)
- (אופציונלי) Node.js לכלי היצירה המתקדם

### שימוש בסיסי

1. **שכפל את הפרויקט**
```bash
git clone https://github.com/yanivmizrachiy/math-worksheets-hub.git
cd math-worksheets-hub
```

2. **פתח דפי עבודה מוכנים**
- עבור לתיקייה `worksheets/`
- בחר כיתה וקובץ HTML
- פתח בדפדפן

3. **השתמש בכלי היצירה**
```bash
cd generator
open index.html  # Mac/Linux
start index.html # Windows
```

### התקנת כלי היצירה המתקדם (אופציונלי)
```bash
cd generator
npm install
npm start
```

---

## 📚 מדריך שימוש

### יצירת דף עבודה חדש

1. פתח את כלי היצירה (`generator/index.html`)
2. בחר כיתה ונושא
3. הוסף שאלות או בחר מהמאגר
4. התאם אישית את העיצוב
5. ייצא ל-PDF או הדפס

### שימוש בתבניות

1. עבור ל-`templates/`
2. בחר תבנית מתאימה
3. ערוך את ה-HTML
4. שמור ושתף

---

## 🎯 איחוד ריפוזיטוריז

פרויקט זה מאחד את הריפוזיטוריז הבאים:

| ריפו מקורי | תיאור | מיקום חדש |
|------------|--------|----------|
| `math-worksheets` | דפי עבודה כלליים | `worksheets/general/` |
| `homerh-math-worksheets` | דפי עבודה לבית | `worksheets/homework/` |
| `math-worksheet` | דף בודד | `templates/single/` |
| `math-worksheet-lab` | מעבדה ליצירה | `generator/` |

---

## 🤝 תרומה לפרויקט

תרומות מתקבלות בברכה! 🎉

### איך לתרום?

1. Fork את הפרויקט
2. צור branch חדש (`git checkout -b feature/AmazingFeature`)
3. Commit את השינויים (`git commit -m 'Add some AmazingFeature'`)
4. Push ל-branch (`git push origin feature/AmazingFeature`)
5. פתח Pull Request

### רעיונות לתרומה
- ➕ הוספת דפי עבודה חדשים
- 🎨 שיפור עיצוב
- 🐛 תיקון באגים
- 📖 שיפור תיעוד
- 🌍 תרגומים לשפות נוספות

---

## 📜 רישיון

פרויקט זה מופץ תחת רישיון MIT - ראה קובץ [LICENSE](LICENSE) לפרטים.

---

## 👤 יוצר

**יניב מזרחי**
- GitHub: [@yanivmizrachiy](https://github.com/yanivmizrachiy)
- Email: yanivmiz77@gmail.com

---

## ⭐ תן כוכב!

אם הפרויקט עזר לך, אנא תן לו ⭐ כוכב!

---

## 📞 צור קשר

יש לך שאלות? רעיונות? בעיות?
- פתח [Issue](https://github.com/yanivmizrachiy/math-worksheets-hub/issues)
- שלח אימייל: yanivmiz77@gmail.com

---

**נוצר עם ❤️ למורים ותלמידים במתמטיקה**
