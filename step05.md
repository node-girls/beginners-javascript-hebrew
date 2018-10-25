# &#x202b; שלב חמישי: הצהרות If-Else

&#x202b;
כעת, אנו הולכות להתחיל להוסיף קצת לוגיקה לקוד שלנו. עד כה, הדפסנו למסך את אותו הדבר בכל פעם שהרצנו את הקוד שלנו, אבל מה אם אנו רוצות להדפיס כל פעם משהו אחר, בהתאם לתנאי מסוים? בתכנות, יש משהו הנקרא הצהרות If/Else. הצהרות אלו בודקות תנאים, ומבצעות פעולות אחרות בהתבסס על התוצאה של בדיקות התנאי.

&#x202b;
המבנה של הצהרות If/Else ב-JavaScript נראה ככה:

```js
if (condition) {
  // do something
} else {
  // do something else
}
```

&#x202b;
בעיקרון, הקוד הזה מתורגם לעברית כך:

&#x202b;
"אם התנאי הוא נכון, עשה וכך - ואם לא, עשה משהו אחר".

## &#x202b; נסי זאת!

&#x202b;
מה אם אני רוצה להדפיס את "Hello World" למסך באמצעות `console.log` במידה ואני מרגישה שמחה, ומשהו אחר כאשר אני מרגישה עצובה?

&#x202b;
בואי נגדיר משתנה הנקרא happy שהערך שלו יהיה true או false (תלוי במצב הרוח שלך עכשיו):

```js
var happy = true;
```

&#x202b;
כעת, בואי נכתוב את הצהרת ה- If/Else שלנו. בתנאי שלנו, אנחנו רוצות לבדוק אם המשתנה happy שווה ל-true. שימי לב: ב-JavaScript, כאשר נרצה לבחון האם שני דברים הם זהים זה לזה, נצטרך להשתמש בסימן שווה שלוש פעמים ( === ), ולא פעם אחת ( = ).
תוכלי לקרוא על זה יותר בלינק [הבא](http://www.w3schools.com/js/js_operators.asp).

&#x202b;
ככה זה נראה:
```js
if (happy === true) {
  // do something
} else {
  // do something else
}
```


&#x202b;
כעת בואי נוסיף מה יקרה בכל שלב של התנאי. ההערות כתובות על מנת להסביר מה קורה בקוד:

```js
if (happy === true) {
  // if I am happy, print "Hello world!"
  console.log('Hello world!');
} else {
  // if I am sad, print a frowny face
  console.log(':(');
}
```


&#x202b;
כעת, הריצי את הקוד (אל תשכחי לשים את הגדרת המשתנה בראש הקובץ) וראי מה קורה! נסי לשנות את הערך של המשתנה happy מ-true ל-false

#### &#x202b; אתגר קטן

&#x202b;
כתבי הצהרת If/Else אשר בודקת האם למחרוזת יש יותר מ-10 אותיות. במידה ויש לה יותר מ-10 אותיות הדפיסי את המחרוזת הבאה: 'this is a long word!'. במידה ויש לה פחות מ-10 אותיות, הדפיסי את המחרוזת: 'this is a short word!'. ברגע שזה עובד, נסי זאת עם מילים אחרות, על מנת לקבל תוצאות אחרות.

&#x202b;
כדי לגלות מה האורך של מחרוזת, את יכולה להשתמש במתודה `length.`
לדוגמה:

 ```js
var word = 'coding';
var length = word.length; // evaluates to 6
```

&#x202b;
על מנת לגלות אם מספר כלשהו גדול מ-10, ניתן להשתמש באופרטור `<`, אשר בודק אם מספר גדול ממספר אחר. מידע נוסף על אופרטורים תוכלי למצוא בלינק [הבא](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Comparison_Operators).

&#x202b;
הנה מבנה שיכול לעזור לך להתחיל:

```js
var word = 'javascript';
​
if (condition) {
  // do something
} else {
  // do something else
}
```

### &#x202b; [לשלב 6 >>>>](https://github.com/node-girls/beginners-javascript-hebrew/blob/master/step06.md)