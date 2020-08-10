---
title: Functional Thoughts
date: "2020-08-09"
template: "post"
draft: false
slug: "functional-thoughts"
category: "Programming"
tags:
  - "Functional"
  - "Javascript"
  - "Web Development"
description: "A test post dedicated to my love of arrow functions."
socialImage: "/media/42-line-bible.jpg"
---

Just thinking about arrow functions.

```js
const sum = arr.reduce((acc, idx) => acc + idx, 0);
```

They're neat. They're concise. They're probably the most beautiful a piece of Javascript could possibly look without just turning into a Lisp.

```js
let sum = 0;
for (let i = 0; i < arr.length; i++) {
    sum += arr[i];
}
```

Now look at this. Disgusting. Miss me with this Java nonsense.

```js
const double = arr.map(x => x * 2);
```

Ahh. Back in the good place. Thank you.
