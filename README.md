Rbay - Auction Platform
Introduction
Rbay is an auction platform designed for higher bids, providing a seamless and engaging auction experience. Inspired by the course Redis: The Complete Developer's Guide by Stephen Grider, Rbay leverages the power of Redis to manage and optimize its backend functionalities.

Technologies Used
TypeScript: Main language for the backend
Node.js: Main backend environment
Express.js: For handling API and HTTP requests
Redis: Utilized as the main database server, leveraging its powerful data structures, including RediSearch for the smart search bar
Features
Sign-In and Sign-Up: Secure user authentication
Home Page: Showcasing the most expensive items, bids ending soonest, and the most viewed items
Auction Dashboard: Real-time bidding with a 2D graph for bid history
User Dashboard: Allows users to manage and view their posted items
Smart Search Bar: Implemented using the Redis module RediSearch, enabling efficient and intelligent search functionality
Getting Started
To run this project locally, follow these steps:

Prerequisites
Install Node.js
Installation
Clone the Repository


git clone https://github.com/ahmedalaa2544/RBay-application-on-Redis-
Open the Project in Your Code Editor

cd RBay-application-on-Redis-
Install the Dependencies


npm install
Create a .env File in the root directory of the project and add the following variables. (Replace the placeholders with your Redis server details.)


_REDIS_HOST=<your_redis_host>
_REDIS_PORT=<your_redis_port>
_REDIS_PW=<your_redis_password>

REDIS_HOST=<your_redis_host>
REDIS_PORT=<your_redis_port>
REDIS_PW=<your_redis_password>
Run the Project


npm run dev
Usage
Once the project is running, you can access it locally through your browser. You will be able to:

Register and log in as a user
Browse the most expensive items, bids ending soonest, and most viewed items on the home page
Participate in auctions and view bid history with a 2D graph
Manage your posted items through the user dashboard
Use the smart search bar to find items efficiently

Contact
If you have any questions or want to connect, feel free to reach out:

LinkedIn:https://www.linkedin.com/in/ahmed-alaa-956971274/
Email: ahmedalaa2544@gmail.com 
