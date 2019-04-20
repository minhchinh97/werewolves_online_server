# Werewolves Online Server
This repo contains the server-side source code of 'Werewolves Online' and its very first release. For more insights, read the relevant article at https://medium.com/@minhchinhduong97/developing-an-online-board-game-web-based-application-with-express-socket-io-and-react-js-efe6bf0db45

!IMPORTANT: for database infrastructure, view Mongoose Schema files under the folder <b>/mongoose-schema</b>

# Dependencies
- React.js
- Expressjs
- MongoDB/mLab/Mongoose
- Socket.io Client

# First release's update
- UI & UX are simply created with priorities to aim for supporting players using their small devices as mobiles.
- 'Waiting Room''s selecting cards panel holds 9 roles: 'Werewolves', 'Ordinary Townsfolk', 'Cupid', 'The Fox', ...
- Updated with rules in English and Vietnamese.
- Scalable application structure for future developments.

# Future improvements
- UI & UX will be enhenced with better graphics and user experience.
- Increase the number of roles.
- There will be two versions, one for smaller devices (width < 768px) and one for bigger devices (width >= 768px)
- History logs will be put in use for dead players to watch the game.
