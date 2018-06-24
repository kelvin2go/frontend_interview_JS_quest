# frontend_interview_JS_quest

[Trello](https://trello.com/) is a collaborative tool that organizes tasks into Kanban style. It is good for an overview of the project but difficult to keep track of one's tasks when there are too many boards / cards assigned.

Use the [Trello API](https://trello.com/docs/index.html) to create a Web app that has the following functions. You can assume that all users have the latest version of the Google Chrome browser.

1. Display the _mentions_ of the user in a Google Inbox style interface. User can click "Read" manually to mark a message as Read, and can reply to mentions directly in the Web app, which would result in a new comment being posted to the corresponding card. Since there is no "Read" state API for _mentions_ provided by Trello, your app should persist the "Read" states _on the client side_ (local storage, WebSQL, etc.)

2. Another section provides a search function for cards. It represent each _board_ as a column, and in each column, there are dividers that denote _lists_. So each column reads like this, vertically: <|List1| [Card 1] [Card 2] [Card 3] |List 2| [Card 4] [Card 5]>. The topic use case for this can be to have one big screen to displayed cards assigned to one's self, such as by the query "@me -list:Done"

Your solution will be assessed on:
 
1. Correctness
2. Performance
3. Extra UI features / animations / aesthetics / responsive UI / attention to details
4. Code Style / Terseness / Proper use of latest technologies 
5. Production ready tuned build for: 
  - any static SPA or Nodejs Hosting (express, heroku, ... )
  - show what have modify for the production build for webpack configuration 

Bonus:
- preferred in Vuejs, Reactjs
- Material Design (css or components library)

You are free to use any dialects of JavaScript -- such as ES6, CoffeeScript, LiveScript, TypeScript, Haste, etc. You are also encouraged to use latest frameworks 


Please include clear building instructions. If we struggle too much to build your app your submission will be discarded.
