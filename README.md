## FlowBite 

 This project aims to develop a platform similar to Google Drive, allowing multiple clients to upload their own documents, files, and images to a server and optionally share these documents with other users. Essentially, it's a project resembling Google Drive. The purpose of this project is to enhance my skills in the MERN stack technology and delve deeper into this field.

## Used Technologies
<p align="left"><a href="https://www.w3schools.com/css/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/css3/css3-original-wordmark.svg" alt="css3" width="40" height="40"/> </a> <a href="https://expressjs.com" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/express/express-original-wordmark.svg" alt="express" width="40" height="40"/> </a> <a href="https://www.w3.org/html/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/html5/html5-original-wordmark.svg" alt="html5" width="40" height="40"/> </a>  <a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/javascript/javascript-original.svg" alt="javascript" width="40" height="40"/> </a> <a href="https://www.mongodb.com/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mongodb/mongodb-original-wordmark.svg" alt="mongodb" width="40" height="40"/> </a> <a href="https://nodejs.org" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/nodejs/nodejs-original-wordmark.svg" alt="nodejs" width="40" height="40"/> </a> <a href="https://www.tailwindcss.com" target="_blank" rel="noreferrer"> <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/tailwindcss/tailwindcss-original-wordmark.svg" height="70" alt="tailwindcss logo"  /></a></p>





###


 ## Current Status  ( Third Commit )
 - During the rendering process of the 'protect' feature in the project, I found a security vulnerability and a bug. After a user accessed a protected page, upon hitting F5, the page wasn't rendered again unless the user logged in again, preventing access to the page.
 - Later on, I successfully managed the authorization process. However, I encountered another issue: when a user with ID 555 logged in and manually entered a different ID in the URL, they could still gain access. This issue has been fixed.
 - The rough design of the Profile Page has been implemented into the project (it's not responsive yet, developed only for desktop compatibility).
 - In the next phase, I'll start working on enabling users to upload files to the server and view these files in their profiles.
 ## Second Commit

- Added a protected render feature using React Router.
- Implemented token refresh on every user login.
- Controlled authorization processes using Context.
- Implemented encryption for the token using certain algorithms.
- Token information is refreshed and encrypted uniquely for each user upon every login.
- Authorization processes are being monitored (verification against data in the database is not yet being performed).








  
## First Commit

- API has been created and executed.
- Database has been established and connected.
- Google OAuth API has been successfully integrated.
- Users can log in using their Google accounts. If the user has previously logged in with their Google account, necessary redirects are provided without any action. If the user is logging in for the first time, their information is added to the database.
 

  
