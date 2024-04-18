## Role based access controll Nodejs

Folder structure
````
rbca/
│
├── helpers/
│   ├── db.js
│   ├── errorHandler.js
│   ├── jwt.js
│   └── role.js
│
├── models/
│   └── user.js
│
├── public/
│   └── stylesheets/
│       └── style.css
│
├── routes/
│   ├── index.js
│   └── user.controllers.js
│
├── services/
│   └── user.services.js
│
├── views/
│   ├── error.jade
│   ├── index.jade
│   └── layout.jade
│
├── .gitignore
├── README.md
├── app.js
├── config.json
├── package-lock.json
└── package.json
````

### Dependencies
 -bcryptjs@^2.4.3 
 -cookie-parser@~1.4.4 
 -cors@^2.8.5 
 -debug@~2.6.9 
 express@~4.16.1 
 -express-jwt@^6.0.0 
 -http-errors@~1.6.3 
 -jade@~1.11.0 
 -jsonwebtoken@^8.5.1 
 -mongoose@^5.9.25 
 -morgan@~1.9.1 
 -rootpath@^0.1.2
