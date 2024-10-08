<div dir="rtl">
   
# Algorithms

### 🔍 מהו אלגוריתם?
**אלגוריתם** הוא סדרת הוראות מוגדרת ומפורטת לפתרון בעיה או לביצוע משימה מסוימת. כל אלגוריתם בנוי מצעדים רציפים ושיטתיים, המבוצעים באופן מדויק, כשהמטרה היא להגיע לפתרון אופטימלי בתוך זמן ומשאבים מינימליים.

---

### 📊 דוגמאות לאלגוריתמים:
1. **🔄 מיון בועות (Bubble Sort):**
   - **מה זה?** אלגוריתם פשוט למיון רשימה של פריטים בסדר עולה או יורד.
   - **איך זה עובד?** האלגוריתם משווה בין זוגות סמוכים של פריטים ברשימה ומחליף את מקומם אם הם אינם מסודרים בסדר הנכון. תהליך זה נמשך באופן חוזר ונשנה עד שכל הרשימה מסודרת.
   - **שימושים:** אידיאלי ללימוד בסיסי של עקרונות מיון, אך אינו יעיל במיוחד לרשימות גדולות.

2. **🔍 חיפוש בינארי (Binary Search):**
   - **מה זה?** אלגוריתם לחיפוש פריט מסוים ברשימה מסודרת.
   - **איך זה עובד?** מתחילים בחלוקת הרשימה לחצי, בודקים את האמצע, ואם הפריט המבוקש קטן או גדול מהאמצע, ממשיכים בחיפוש במחצית המתאימה בלבד, עד למציאת הפריט או הבנתו שהוא לא קיים.
   - **שימושים:** חיפוש בינארי יעיל במיוחד כאשר עובדים עם נתונים מסודרים, כמו ספריות, מסדי נתונים, או חיפושים אינטרנטיים.

3. **🛤️ אלגוריתם דייקסטרה (Dijkstra's Algorithm):**
   - **מה זה?** אלגוריתם למציאת המסלול הקצר ביותר בין שני קודקודים בגרף.
   - **איך זה עובד?** הוא מתעדף צמתים בגרף על פי מרחק מהצומת ההתחלתי ומתקדם תוך חישוב המרחק הקצר ביותר לכל צומת.
   - **שימושים:** ניווט, תכנון מסלולים (כמו ב-GPS), אופטימיזציה של רשתות.

4. **🧠 אלגוריתם למידת מכונה (Machine Learning Algorithm):**
   - **מה זה?** אלגוריתם המאפשר למכונות ללמוד מדוגמאות ונתונים ולשפר את ביצועיהן ללא תכנות מפורש.
   - **איך זה עובד?** משתמש בסטים גדולים של נתונים לצורך אימון, ומפתח מודלים שמסוגלים לנבא תוצאות או לקבל החלטות.
   - **שימושים:** זיהוי תמונות, עיבוד שפה טבעית, סינון דואר זבל, רפואה מותאמת אישית.

---

### ⚙️ תכונות של אלגוריתם:
- **🧩 דטרמיניסטיות:** 
  - **מה זה?** האלגוריתם תמיד יפיק את אותו פלט עבור אותו קלט, כלומר, התוצאה היא צפויה.
  - **דוגמה:** חישוב סכום של מספרים תמיד ייתן את אותה תוצאה.
  
- **⏳ סופיות:** 
  - **מה זה?** האלגוריתם מסתיים לאחר מספר סופי של צעדים, כלומר, לא ימשיך לפעול לנצח.
  - **דוגמה:** אלגוריתם חישוב ממוצע מפסיק כאשר כל המספרים נספרו.

- **⚡ יעילות:** 
  - **מה זה?** האלגוריתם נמדד לפי הזמן והמשאבים (כמו זיכרון) שהוא דורש כדי להשלים את המשימה.
  - **דוגמה:** חיפוש בינארי יעיל יותר מחיפוש ליניארי ברשימות גדולות.

- **♻️ אופטימיזציה:** 
  - **מה זה?** האלגוריתם נועד להשיג את המטרה בצורה האופטימלית ביותר, תוך מינימום משאבים.
  - **דוגמה:** מיון מהיר (Quick Sort) שמסדר רשימה בסיבוכיות של O(n log n).

---

### 🌐 שימושים באלגוריתמים:
- **💻 מדעי המחשב:**
  - **שימושים:** חישוב נתונים, אופטימיזציה של תוכנות, אבטחת מידע, דחיסת נתונים.
  - **דוגמה:** אלגוריתמי חיפוש ומיון בסיסיים נמצאים בכל יישום מחשב, מחיפוש קבצים ועד גוגל.

- **➗ מתמטיקה:**
  - **שימושים:** פתרון משוואות, חישוב ערכים, אופטימיזציה מתמטית.
  - **דוגמה:** אלגוריתמים לניתוח גרפים מורכבים.

- **🏗️ הנדסה:**
  - **שימושים:** תכנון ובקרת תהליכים, ניתוח מערכות מורכבות.
  - **דוגמה:** אלגוריתמים המשמשים לתכנון מסלולי רובוטים, ניתוח מבנים ועוד.

- **📉 כלכלה:**
  - **שימושים:** ניתוח סיכונים, חיזוי שוק, אופטימיזציה של תיקי השקעות.
  - **דוגמה:** אלגוריתמים של למידת מכונה לחיזוי מגמות כלכליות.

- **📱 טכנולוגיה יומיומית:**
  - **שימושים:** עיבוד שפה טבעית, זיהוי פנים, הצעות תוכן מותאם.
  - **דוגמה:** מנועי המלצות כמו אלו של נטפליקס או יוטיוב.

---

אלגוריתמים הם הלב הפועם של עולם הטכנולוגיה. הם הבסיס לתוכנות, לאפליקציות, ולמערכות המודרניות שאנו משתמשים בהן ביום-יום. היכולת לעצב ולפתח אלגוריתמים מתקדמים היא המפתח לפיתוח עתיד טכנולוגי מתקדם יותר.

</div>
