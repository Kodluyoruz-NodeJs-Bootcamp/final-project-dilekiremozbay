# MOVIE DIARIES

### [DEMO](https://movie-diary-dilekiremozbay.herokuapp.com/login)

<br/>

## :mount_fuji: About

In the project, users can share their favorite movies, stars and may write diaries about how they felt during or after the movies. Automatic interaction occurs during process.Users can read each other's posts and like/unlike them and make comments. In addition, users can share the posts in the private option which are only stored in the users personal profiles, and delete personal correspondences.

<br/>

## :rocket: Technologies

- [TypeORM](https://typeorm.io/#/)
- [TypeScript](https://www.typescriptlang.org/)
- [NodeJS](https://nodejs.org/en/)
- [HTML](https://www.w3schools.com/html/)
- [CSS](https://www.w3schools.com/css/)
- [Bootstrap](https://getbootstrap.com/docs/)
- [Express.js](https://expressjs.com/)
- [MySQL](https://www.mysql.com/)
- [EJS](https://ejs.co/)

<br/>

## :briefcase: Project Files

```
movie_diaries
|--- node_modules
|--- public                                         // Place of my images and css files
|--- src                                            // Place of my Typescript codes
|     |--- controllers                              // Place where my controllers are stored
|     |      |--- movieAndStarController.ts         // addMovie,deleteMovie,addComment,etc
|     |      |--- socialLoginController.ts          // Facebook and Gmail controllers
|     |      |--- UserController.ts                 // createUser, loginUser, logoutUser,etc
|     |--- entity                                   // Place where my database models are stored
|     |      |--- Comments.ts                       // Database model for comments
|     |      |--- Like.ts                           // Database model for likes (movies & stars)
|     |      |--- Movie.ts                          // Database model for movies
|     |      |--- SocialLoginCredentials.ts         // Database model for gmail/facebook login
|     |      |--- Star.ts                           // Database model for movie stars
|     |      |--- User.ts                           // Database model for users
|     |--- middlewares                              // Place of my middlewares
|     |      |--- authorizer.ts                     // JWT Authentication
|     |--- routes                                   // Place of my routes
|     |      |---index.ts                           // Routes for login and movie-star process
|     |--- views                                    // Place where my ejs documents are stores
|     |      |---partials                           // Place for recurrent parts
|     |      |      |---_detail-movie-star.ejs      // Partial for page of movie&star repetiteve part
|     |      |      |---_footer.ejs                 // Partial for repetitive part of footer
|     |      |      |---_header.ejs                 // Partial for repetitive part of header
|     |      |      |---_movies_and_star.ejs        // Partial for repetitive part of homepage
|     |      |---login.ejs                          // Login
|     |      |---movie-add.ejs                      // .ejs for sharing movie page
|     |      |---movie-star-detail.ejs              // .ejs for detailed movie&star sharings
|     |      |---movies-and-stars.ejs               // Mainpage
|     |      |---profile.ejs                        // Personal page
|     |      |---register.ejs                       // Registeration
|     |      |---star-add.ejs                       // .ejs for sharing movie-star part
|     |---index.ts                                  // Start of movie_diary
|--- .env-sample                                    // Duplicated environment variables
|--- .gitignore                                     // gitignore file
|--- nodemon.json                                   // Quick Start Confugiration
|--- ormconfig.json                                 // ORM and database connection configuration
|--- package-lock.json                              // Detail part of package.json
|--- package.json                                   // List of dependencies
|--- README.md                                      // YOU ARE HERE :)
|--- tsconfig.json                                  // TypeScript compiler options
```

<br/>

## :hammer_and_wrench: Main Features

- Gmail/Facebook login
- When logged in with Facebook, the username is updated according to the owner of the e-mail.
- If username is already registered,new username is created randomly in gmail & facebook logins.
- JWT token authentication
- Re-registration with the same email or username is not allowed.
- The user who is not logged in cannot access the website.
- Basic CRUD operations for movie & movie star posts (except update data)
- Private post sharing option (stored in personal profile)
- MySQL database record
- Posts are sorted by date
- Like / unlike feature / number of likes
- Comments can be shared.
- Random photos are sorted on posts
- Logout option

<br/>

## :crystal_ball: Screenshots

| REGISTER                                                                             |
| ------------------------------------------------------------------------------------ |
| <img src="https://github.com/dilekiremozbay/movie_diary/blob/main/public/login.png"> |

| LOGIN                                                                                   |
| --------------------------------------------------------------------------------------- |
| <img src="https://github.com/dilekiremozbay/movie_diary/blob/main/public/register.png"> |

| MAINPAGE                                                                                |
| --------------------------------------------------------------------------------------- |
| <img src="https://github.com/dilekiremozbay/movie_diary/blob/main/public/mainpage.png"> |

| DETAIL VIEW OF THE POST                                                                |
| -------------------------------------------------------------------------------------- |
| <img src="https://github.com/dilekiremozbay/movie_diary/blob/main/public/comment.png"> |

<br/><br/>

### ⚙️ Installation

Use the package manager **npm** to deploy dependencies after clonening the project.

```bash
npm install
```

### Usage

```bash
npm start
```

- _**MUST** have MySQL installed in your local_

Then go to **localhost:3000** to test it out.

### .env

.env files are duplicated as .env-sample

<br/>

## :memo: License

This project is under the terms of the MIT license.
<br/>
<br/>
Contact: [LinkedIn](https://www.linkedin.com/in/dilekiremozbay)

```

```
