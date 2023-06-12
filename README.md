Things to do
 Generate random private key and wallet address
 Create a column to add private key
 Store the address into a JSON
 Sign the message
 Send the recovery key and recovery bit to backend
 Compare derived wallet address and do the transactions
ECDSA Node
This project is an example of using a client and server to facilitate transfers between different addresses. Since there is just a single server on the back-end handling transfers, this is clearly very centralized. We won't worry about distributed consensus for this project.

However, something that we would like to incoporate is Public Key Cryptography. By using Elliptic Curve Digital Signatures we can make it so the server only allows transfers that have been signed for by the person who owns the associated address.

Video instructions
For an overview of this project as well as getting started instructions, check out the following video:

https://www.loom.com/share/0d3c74890b8e44a5918c4cacb3f646c4

Client
The client folder contains a react app using vite. To get started, follow these steps:

Open up a terminal in the /client folder
Run npm install to install all the depedencies
Run npm run dev to start the application
Now you should be able to visit the app at http://127.0.0.1:5173/
Server
The server folder contains a node.js server using express. To run the server, follow these steps:

Open a terminal within the /server folder
Run npm install to install all the depedencies
Run node index to start the server
The application should connect to the default server port (3042) automatically!

Hint - Use nodemon instead of node to automatically restart the server on any changes.

About
Alchemy University - W1

ecdsa-node-app.vercel.app/
Resources
 Readme
 Activity
Stars
 0 stars
Watchers
 0 watching
Forks
 1 fork
Report repository
Releases
No releases published
Packages
No packages published
Contributors 3
@rrsingh11
rrsingh11 Ritu Raj Singh
@Dan-Nolan
Dan-Nolan Dan Nolan
@elanh
elanh Elan
Environments 4
 Production – ecdsa-node-api Active
 Production – ecdsa-node-app Active
 Production – ecdsa-node Active
 Production Active
Languages
JavaScript
80.7%
 
SCSS
15.4%
 
HTML
3.9%
Footer
© 2023 GitHub, Inc.
Footer navigation
Terms
Privacy
Security
Status
Docs
