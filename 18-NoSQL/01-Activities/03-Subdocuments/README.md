# 🏗️ Implement Subdocuments in a Mongoose Schema

Work with a partner to implement the following user story:

* As a developer, I want to nest a child document in a parent document.

## Acceptance Criteria

* It is done when I define a new schema named `bookSchema` for the subdocument.

* It is done when the `bookSchema` has two properties: `title` and `price`.

* It is done when the `books` subdocument is nested in the parent document.

* It is done when I have created a model named `Library`.

* It is done when I have created an array of three books using the `bookSchema`.

* It is done when I have created a new instance of the `Library` model which includes the `books` subdocument.

* It is done when I test the `GET` route in Insomnia and the subdocuments are nested in the parent document.

## Assets

The following code snippet demonstrates the web application's appearance and functionality:

```js
{
  _id: '611d5dbd896f452ac77fec21',
  name: 'Books',
  books: [
    {
      _id: '611d5dbd896f452ac77fec22',
      title: 'Diary of Anne Frank',
      price: 10
    },
    {
      _id: '611d5dbd896f452ac77fec23',
      title: 'One Thousand Years of Solitude',
      price: 20
    },
    {
      _id: '611d5dbd896f452ac77fec24',
      title: 'History of Hogwarts',
      price: 5
    }
  ],
  lastAccessed: '2021-08-18T19:21:33.017Z',
  __v: 0
}
```

---

## 💡 Hints

* When is subdocument data saved?

## 🏆 Bonus

If you have completed this activity, work through the following challenge with your partner to further your knowledge:

* What method can we use to remove a subdocument?

Use [Google](https://www.google.com) or another search engine to research this.

---
© 2022 Trilogy Education Services, LLC, a 2U, Inc. brand. Confidential and Proprietary. All Rights Reserved.
