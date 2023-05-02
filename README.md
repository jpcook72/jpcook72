## Projects:
### [PostgreSQL code-generator](https://github.com/jpcook72/PostgreSQL-code-generator)
I find it very helpful to use database schema design tools to visualize a project’s database structure. But since the external diagram and the actual code to write the database are completely separate entities, they can easily get out of sync. This app solves this problem by auto-generating the database code straight from your diagram.
- Tech: TypeScript, JavaScript, Node, Express, React, Jest, React Testing Library, and Heroku
- [Presentation Video](https://www.youtube.com/watch?v=r2XFSdZUbB4&feature=youtu.be)
- [Tests](https://github.com/jpcook72/PostgreSQL-code-generator/tree/master/client/__tests__)
- [pg-auto-write](https://github.com/jpcook72/pg-auto-write): npm module used to connect PostgreSQL code-generator with your code-base
    - Tech: JavaScript, Node, Express, Jest
    - [Tests](https://github.com/jpcook72/pg-auto-write/blob/master/test.js)

### [Deckr](https://github.com/FSA-Deckr/deckr)
Deckr is a virtual multiplayer card table with in-game video chat. It posed an interesting problem in delivering a multiplayer game where players require a synchronized environment and state (especially when dealing with the randomness of in-game physics).
- Tech: Node, Express, Vanilla JavaScript, Phaser 3, socket.io, and Heroku
- [Presentation Video](https://www.youtube.com/watch?v=yY7VpztKcyg&list=PLx0iOsdUOUmmy76FSJXiZ4_GkucjbLPdr&index=5)
