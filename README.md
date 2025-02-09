# Salinaka | E-commerce react app
Simple ecommerce react js app with firebase.

### [Live demo](https://salinaka-ecommerce.firebaseapp.com)

![Salinaka screenshot](https://raw.githubusercontent.com/jgudo/ecommerce-react/master/static/screeny1.png)

### Install Dependencies
```sh
$ npm install 
```
### Create a new firebase project
Login into your google account and create a new firebase project [here](https://console.firebase.google.com/u/0/)

Create a `.env` file for production and `.env.test`for development in the root of your project folder
and add the following configuration details. It can be found on your firebase project.

```
FIREBASE_API_KEY=
FIREBASE_AUTH_DOMAIN=
FIREBASE_DB_URL=
FIREBASE_PROJECT_ID=
FIREBASE_STORAGE_BUCKET=
FIREBASE_MSG_SENDER_ID=
FIREBASE_APP_ID=

```

### Run development server
```sh 
$ npm run dev-server
```

### Build the project
```sh
$ npm run build
```


### Features

* Admin CRUD operations
* Firebase authentication
* Firebase auth provider authentication
* Account creation and edit


Appended new line.
Update README.md with appended content.
Java API for GitHub

The action tries to open PR and then checks if the PR is mergeable. 
 If mergeable then action returns PR id, if not then process exits with error code 1 to prevent later execution. Now maximum time to wait for PR state is 3 sec.


Destination Check:
– The code first verifies if the destination directory exists and is nonempty.
– If it exists, it looks for the “.git” folder. If found, it uses Git.open(localPath) to open the repository. Otherwise, it reports an error (you could choose to handle this case differently).

Cloning the Repository:
– If the destination doesn’t exist or is empty, it clones the remote repository into that directory.