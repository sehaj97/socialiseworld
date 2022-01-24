# socialiseworld - a Social Network API

### Description

*An API for a social network web application where users can share their thoughts, react to friends’ thoughts, and create a friend list.*

# :hammer: Tools
[Insomnia](https://insomnia.rest/)

[Node.js](https://nodejs.org/en/)

[Express.js](https://expressjs.com/)

[Moment.js](https://www.npmjs.com/package/moment)

[Mongoose](https://www.npmjs.com/package/mongoose)

[MongoDB](https://www.mongodb.com/)

### User Story

```text
AS A social media startup
I WANT an API for my social network that uses a NoSQL database
SO THAT my website can handle large amounts of unstructured data
```

### Acceptance Criteria

```text
GIVEN a social network API
WHEN I enter the command to invoke the application
THEN my server is started and the Mongoose models are synced to the MongoDB database
WHEN I open API GET routes in Insomnia for users and thoughts
THEN the data for each of these routes is displayed in a formatted JSON
WHEN I test API POST, PUT, and DELETE routes in Insomnia
THEN I am able to successfully create, update, and delete users and thoughts in my database
WHEN I test API POST and DELETE routes in Insomnia
THEN I am able to successfully create and delete reactions to thoughts and add and remove friends to a user’s friend list
```


# :memo: Instructions

To run the application, use the following command:

    node server.js

# Credits
[GitHub: sehaj97](https://github.com/sehaj97)