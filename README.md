# Bay Sharing
Bay Sharing is a single page application providing a platform where the users can share their items with other people or families in the Bay Area.

### User Flow
Guest users can:
- browser all the posts
- register or log in to get access to more features

Logged in users can: 
- browser all the posts
- view the post details by clicking on the post card
- add/remove comments for each post
- search certain posts by typing key words in the search form
- save/cancel their favorite posts, send/cancel invite to the posts
- filter the posts by age, city, category or user by clicking on the tags on each post
- create new post by filling the new post form
- edit or delete their own posts
- view theirs own posts
- view their saved favorite posts
- view the posts which they have sent invites to
- view the users who sent invites to their posts
- view the deals which are ready to be made. Deal means both the logged in user and another user have interest in each other's post(s), so they can contact each other through email to discuss the furture process to share their items

### Deployed App Link
https://baysharing.surge.sh/

### Tech Stack 

##### frontend: 
HTML, CSS, Javascript, React.js, Redux, Bootstrap

##### backend: 
Express, Node.js

##### database: 
SQL, PostgreSQL

### Installation and Setup Instructions

Clone down this repository. You will need `node` and `npm` installed globally on your machine.

##### backend:
 cd to "sharely-backend" directory,and  install the dependencies:
    `npm install`

   Create the database and tables,  and populate the tables with sample data:
   `psql -f sharely.sql` (for windows user)

   `psql < sharely.sql` (for mac user)

   To start the server:
   `npm start`

   To run test suite:
	`npm test`


##### frontend:
cd to "sharely-frontend", and install the dependencies:
   `npm install`

  To run the app in the development mode:
   `npm start`

   To run test suite:
   `npm test`
	
##### To visit app on localhost:  

Open `http://localhost:3000` to view it in the browser.