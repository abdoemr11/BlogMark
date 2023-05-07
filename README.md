# BlogMark
A collaborative space to bookmark your favorite blog post and share it with others. 

![Blogmark login page]("pictures\login1.PNG")
![Blogmark blogs list]("pictures\blogs.PNG")
![Blogmark users list]("pictures\Capture.PNG")
# Technology Stack
- node js v16.19.0 & Express
- React v18.1.0
- MongoDB

# Getting Started
## Production instructions
- Clone This repo to your local machine
- From the root directory hit ``` npm run start:prod```

## Development instructions
- run ``` npm i ```
- create ```env``` file with following credentials
  - MONGDODB_URI : you can get from the mongodb provider.
  - PORT: The main port for the application
  - TEST_MONGDODB_URI: For ease, The testing happen in its own database.
  - SECRET: For JsonWebToken encrypting.
- run ```cd frontend &&  npm i ```
- Now you can start working on this project.

# TODO
- [ ] For Now The front end doesn't enable registering new user, so this is the next logical step
- [ ] fix broken tests and refactor the backend code to enhance request validation.
- [ ] Imporve the frontend UX