<details>
<summary>Deploy to Heroku</summary>

```js
// docgen
// app.use(express.static('./public/))

// package =>
// "engines": {
// 		"node": "16.x"
// 	}

// Profile => web: node app.js

//  rmdir .git

// git init...add commit
// heroku login
// heroku create "app-name"
// git remote -v // check if rely on heroku
// set .env variable in heroku dashboard
// or via CLI =>  $ heroku config:set SECRET=some_random_string => see .env file

// git push heroku master

// heroku restart -a fm-pfeedback-api
```

cors

```js
// app.use(
//   cors({
//     origin: origin,
//     preflightContinue: true,
//     methods: "GET,HEAD,PUT,PATCH,POST,DELETE",
//     credentials: true,
//   })
// );
```

</details>

<details>
<summary>Deploy on render</summary>

```js
-
```

</details>
