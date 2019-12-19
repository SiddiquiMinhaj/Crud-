1.	User Registration using Firebase Authentication (using Email/Password | Google Authentication )
2.	CRUD Operations like
•	User can add product to his cart.
•	Admin can add product to the product list
•	Admin can edit/delete the product.
3.	Drag and Drop Angular 7 Drag & Drop
•	Implemented Angular Drag and Drop CDK
1.	Security
•	Implmented Authentication and Authorization
Tools and Technologies
•	Technology: HTML, MDBootstrap, CSS, Angular-7, Firebase, i18n, Drag & Drop, Progressive Web Application, jsPDF (to download Receipt as PDF).
•	Database : Angular Firebase.
This Projects covers all fundamentals of Angular
•	Multiple Modules
•	Components, Template and DataBinding
•	Form Validation
•	HttpClient
•	Animations
•	Dependency Injection
•	Routing & Navigation
•	Service Workers
•	Pipes
•	Gaurds etc..
Installation
1.	Angular CLI
o	Download Angular CLI
2.	NodeJs
o	Download Nodejs
3.	Package Manager - NPM / Yarn
4.	Clone the repository and run npm install if you use npm as package manager or yarn install if you use yarn as package manager.
5.	Angular + Firebase Tutorial - Angular + Firebase + Typescript — Step by step tutorial
6.	Activate Firebase Authentication Providers
Authentication -> Sign-in-method -> Enable Email/Password & Google provider
7.	Update the Firebase Database Rules
Database -> Rules
{
"rules": {
    ".read":true,
    ".write": true
}
}
8.	Configure your firebase configuration src/environments/firebaseConfig.ts
9.	export const FireBaseConfig = {
10.	    apiKey: "YOUR_API_KEY",
11.	    authDomain: "YOUR_AUTH_DOMAIN",
12.	    databaseURL: "YOUR_DATABASE_URL",
13.	    projectId: "YOUR_PROJECT_ID",
14.	    storageBucket: "YOUR_STORAGE_BUCKET",
15.	    messagingSenderId: "YOUR_SENDER_ID"
16.	};
17.	For Admin Role Register or SignIn with Google Auth
your registered data will be saved inside the firebase clients table.
    -clients
        -LRSkWxGAKQAFZmyfsx6
            -createdOn: "1542046725"
            -email: "<<YOUR_REGISTERED_EMAIL_ID>>"
            -isAdmin: false      <--- Change this to true
            ...
Now you can able to access the Admin Privileges like Creating Product, Removing Product, etc..
18.	Run the Server.
Screenshots:

