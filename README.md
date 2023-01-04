CONTENTS OF THIS FILE
---------------------
  * Description
  * Installation Instructions
  * Screenshots
  * Walkthrough
  
DESCRIPTION
-----------
Internet retail, also known as **e-commerce**, is the largest sector of the electronics industry, generating an estimated $29 trillion in 2019. E-commerce platforms like Shopify and WooCommerce provide a suite of services to businesses of all sizes. Due to their prevalence, understanding the fundamental architecture of these platforms will benefit you as a full-stack web developer.

This application is a back end for an e-commerce site. It uses Express.js API to use Sequelize to interact with a MySQL database.

INSTALLATION INSTRUCTIONS
-------------------------
## Setup (if git and node are already installed, you may skip): 

For Windows, please download and install [git](https://git-scm.com/downloads) and [Node.js](https://nodejs.org/en/download/).

macOS users will need to install [Homebrew](https://brew.sh/). Then, run `brew install git` to install git, and `brew install node` to install Node.js.

Linux/BSD users should use their appropriate package managers to install git and Node.js, or build from source if you swing that way.

After that, [clone the Application](https://help.github.com/en/github/creating-cloning-and-archiving-repositories/cloning-a-repository).

When the cloning is done, open the Integrated Terminal in the respective directory. 

Run the following command in the terminal to install the packages: 

```bash
npm install
```

You will also need to install MySQL to your machine and run the schema.sql and seeds.sql files to create the database/tables.
You can seed the database by running the following command in your CLI: 

```bash
npm run seed
```

After connecting to the database, create a .env file in the main directory and input your database name, user, and password.
For example, it will look like this: 

DB_NAME='ecommerce_db'
DB_USER='root'
DB_PASSWORD='root'

To send the API calls, it would be very useful to download an API client (ie. Insomnia)

## Using the Application

Run the following command in the terminal to run the application: 

```bash
npm run start
```
Now, you may go into your API client to send your API calls as shown in the gifs/walkthrough video further below this README.

SCREENSHOTS
-----------
The following image shows the web application's capability:

![Screenshot 1](./assets/images/demo1.gif)
![Screenshot 2](./assets/images/demo2.gif)
![Screenshot 3](./assets/images/demo3.gif)

WALKTHROUGH
-----------
The following link will show a walkthrough of the web application: 

[Ecommerce Back End Walkthrough](https://drive.google.com/file/d/1kSCU-mEhusPm8KuUWsrmfvFvBuxechVE/view)

QUESTIONS
---------
If you have any questions or concerns, please contact me through my email below: 

kimdillon19@gmail.com

[https://github.com/dillonkim19](https://github.com/dillonkim19)
