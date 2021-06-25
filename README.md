# Task Garden
Link: https://taskgardensei29.herokuapp.com/

![screenshot](https://imgur.com/RexudNn.png)

## Description
This is the Task Garden. It is an application that reward users when they complete their tasks. The rewards come in the form of 'growth' for your virtual plants that can be planted on your virtual farm(Garden). Various plants can be bought from the shop(Florist). The currency is earned by completing daily tasks(dailies) that are generated at random by the application.
  
After a user registers or log in, they will be brought to the dashboard. This is where a user can manage their tasks. They can add tasks, complete tasks, delete tasks and archive completed tasks. 
  
A feature of the Task Garden is upon creation of a task, the user will decide the urgency and importance of the task. This will help users prioritise the tasks that needs to be done. Each task upon creation can be assigned to a plant that has already been planted in the Garden. When a task that is assigned to a plant has been completed, the plant itself gains 'growth'. When 'growth' has maxed out, the plant will evolve from a sapling to a beautiful plant. Enjoy being productive!
## Planning and Development Process

### Technologices Used

This app was constructed with the following technologies:
```
Front-end:
- ReactJS: A JavaScript library for building user interfaces.  

Back-end:
- MongoDB: A source-available cross-platform document-oriented, NoSQL database program.
- Node.js: A JavaScript runtime built on Chrome's V8 JavaScript engine.
- Express: Fast, unopinionated, minimalist web framework for node.
```
#### Dependancies
#### Front-end:
##### React Bootstrap
The most popular front-end framework rebuilt for React. To install:
```javascript
npm install react-bootstrap bootstrap@4.6.0

{/* The following line can be included in your src/index.js or App.js file*/}
import 'bootstrap/dist/css/bootstrap.min.css';
```
##### Axios
Promise based HTTP client for the browser and node.js. To install:
```javascript
npx i axios
```
##### Redux
Redux is a predictable state container for JavaScript apps. To install:
```javascript
npx i --save redux
```
##### Moment
A JavaScript date library for parsing, validating, manipulating, and formatting dates. To install:
```javascript
npx i moment
```
##### Date-FNS
A Modern JavaScript date utility library. To install:
```javascript
npx i date-fns
```
##### React Datepicker
A simple and reusable Datepicker component for React using Date-FNS. To install:
```javascript
npx i react-datepicker --save
```

#### Back-end:
##### JsonWebToken
JSON Web Token (JWT) is an open standard (RFC 7519) that defines a compact and self-contained way for securely transmitting information between parties as a JSON object. To install:
```javascript
npx i jsonwebtoken
```
##### Bcrypt
A library to help you hash passwords. To install:
```javascript
npx i bcrypt
```
##### Passport
Passport is Express-compatible authentication middleware for Node.js. To install:
```javascript
npx i passport
```
##### Mongoose
Mongoose is a MongoDB object modeling tool designed to work in an asynchronous environment. To install:
```javascript
npx i mongoose
```

### User Stories

* As a user I want to have a dashboard that classifies my tasks so that I know what to priortise.
* As a user I want to be able to create tasks, delete tasks, complete tasks so that I can see what I have to do, have done and remove tasks that I do not need.
* As a user I want my tasks to be incentivised, so that I will want to complete my tasks.
* As a user I want to be able to buy plants so that I can build my own garden.
* As a user I want to be able to plant my plants in my garden so that I can grow them.
* As a user I want to be able to assign my tasks to plants so that I can grow them.
* As a user I want to earn coins to buy my plants so that I can plant them in the garden.


* As an admin I want to be able to add plants to the shop so that I can give users more choices in future.
* As an admin I want to be able to add Daily Tasks so that users can earn coins for their purchases.




### Wireframes

![screenshot](https://imgur.com/HhUNxeC.png)

Wireframes were developed on Figma  
Link: https://www.figma.com/proto/k2KVINSObww30BnGk1XcRN/Project-3?node-id=1%3A2&scaling=min-zoom

### Challenges Faced


## Acknowledgments

#### Habitica, © 2021. All rights reserved.
Gave us the inspiration for the project.

#### Forest, Copyright © 2021. All rights reserved. By SeekrTech
For the alternative idea of growing a garden instead of an overwhelming battle royale game.

#### Kai Ming, Zhi Yang & Yong Jian
The awesome team that brought you this amazing app.
