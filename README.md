# blog-website-backend-nodejs-REST-API

**blog-website** is one of my personal projects where registered bloggers write blogs. Bloggers can also comment or react to blogs. This repository holds the code of it's backend which is a **RESTful API**.

<em> The frontend of this project can be found [here (Angular)](https://github.com/grasssi/blog-website-frontend-byGrassi) </em>


## Features:
- bloggers can create their profiles (token-based authentication)
- bloggers can edit their profile
- bloggers can write blogs. They can set the category of their blog (i.e. travel, medical, tech etc)
- registered bloggers can comment on their own or others blog
- registered bloggers can also react on others blog. They can react **like**, **sad** to blogs
- unregistered public users can read blogs but can't comment or react n blogs
- Blogs of a particular category can be viewed

## Tech used:

**Runtime environment**
- [x] Node.js

**API for movies & their metadata**
- [x] OMDB API

**Database**
- [x] MongoDB

**Dependencies**
- [x] bcrypt: ^5.0.1,
- [x] cors: ^2.8.5,
- [x] dotenv: ^8.2.0,
- [x] express: ^4.17.1,
- [x] http-errors: ^1.8.0,
- [x] joi: ^17.4.0,
- [x] jsonwebtoken: ^8.5.1,
- [x] mongoose: ^5.12.2

## How to install & run:
### Using Git (recommended)
1. Navigate & open CLI into the directory where you want to put this project & Clone this project (will be cloned inside myProject folder) using this command.
   
```bash
git https://github.com/grasssi/blog-website-frontend-byGrassi.git. 
```
### Using manual download ZIP
1. Download repository
2. Extract the zip file, navigate into it & copy the folder to your desired directory

### Install npm dependencies after cloning or downloading
```bash
npm install
```

### Setting up environments
1. There is a file named `.env.example` on the root directory of the project
2. Create a new file by copying & pasting the file on the root directory & rename it to just `.env`
3. The `.env` file is already ignored, so your credentials inside it won't be committed
4. Change the values of the file. Make changes of comment to the `.env.example` file while adding new constants to the `.env` file.
