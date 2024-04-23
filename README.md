# E-0923 NodeJS Intro Exercise

Goal: Create your first NodeJS server

1. Create a `dev` branch after accepting the assignment
2. Clone your repository and switch to the `dev` branch
3. Run `npm init -y` to generate your `package.json` file
4. Create your server file. You can call it `server.js` or `index.js`
5. Create a simple server with four routes and the corresponding response:

   - Home `/ text/html 200`: Should return `<h1>Home</h1>`
   - About `/about text/html 200`: Should return `<h1>About</h1>`
   - My Account `/my-account text/plain 403`: Should return `You have no access to this page`
   - Any other url `text/plain 404`: Should return `Page not found`

6. To run your server, you can run `node server.js` or if you have nodemon installed, `nodemon server.js`
7. Once you are done, push your changes and create a PR from `dev` to `master` and merge
