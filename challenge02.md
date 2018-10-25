# &#x202b; אתגר שני: כותבים מפורסמים

&#x202b;
הידעת? מערך יכול להיות גם מערך של אובייקטים? יצרנו לך מערך כזה פה. רוצי על המערך, ועבור כל אובייקט שיש בו, הדפיסי את המשפט הבא:

```js
"Hi, my name is {firstName} {lastName}. I am {age} years old, and work as a {occupation}."
```

&#x202b;
התעלמי מהסוגריים המסולסלים, הם שם רק כדי שתדעי איזו מילה יש להחליף במשהו אחר. המשפט הסופי נראה כך:

```js
"Hi, my name is Virginia Woolf. I am 59 years old, and work as a writer."
```

&#x202b;
להלך המערך:

```js
var writers = [
  {
    firstName: "Virginia",
    lastName: "Woolf",
    occupation: "writer",
    age: 59,
    alive: false
  },
  {
    firstName: "Zadie",
    lastName: "Smith",
    occupation: "writer",
    age: 41,
    alive: true
  },
  {
    firstName: "Jane",
    lastName: "Austen",
    occupation: "writer",
    age: 41,
    alive: false
  },
  {
    firstName: "bell",
    lastName: "hooks",
    occupation: "writer",
    age: 64,
    alive: true
  },
];
```

&#x202b;
אם תרצי אתגר נוסף: הדפיסי רק את הסופרים שנמצאים בחיים.

### &#x202b; [לאתגר 3 >>>>](https://github.com/node-girls/beginners-javascript-hebrew/blob/master/challenge03.md)
