# CODSOFT-L1-T2-PAGE-LANDING

Here we can see a company's progress on their projects and the features they are offering to their customers. There is an working contact form mailing system, which allows the user to send any messages along with his name and email id and the owner can view the mail that has been sent from the contact form by the user and the owner can review the mails and he can respond to the mails.

You need to install node js for this after installing you need install some modules

npm init -y
npm install express nodemailer cors 

npm i -D nodemon

after installing these 
alter the "script" in package.json file like this

  "scripts": {
    "dev": "nodemon server.js",
    "start": "node server.js"
  },
  then to start the server bash
  npm run dev
