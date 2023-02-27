# About
A MERN STACK social-media-app for developers to create there profile online and to show there details on one Page. 

# Preview

[Glimpse](https://user-images.githubusercontent.com/59373438/221539511-5f396d86-a46a-4344-a138-8f6e31df2cef.mp4)

# Setup

```cmd
git clone https://github.com/iamsuyashpatel07/Developer-Valley.git
cd Developer-Valley
yarn
cd client
yarn
```

### Add your credentials

**_Navigate_** to `$Root\social-media-app\config\default.json` and add the following

```JavaScript
{
  "mongoURI": "Your_Database_URL",
  "jwtSecret": "my_secret_token",
  "githubClientId": "Your_Github_ClientID",
  "githubSecret": "Your_Github_Secret_KEY"
}

```

### Run

```
$Root\social-media-app> yarn run application
```

# Technologies/Methodologies Used 

- Builded backend API with Node.js & Express.
- Protecting routes/endpoints with JWT (JSON Web Tokens).
- Used MongoDB as Database.
- Integrated React Frontend with our backend in an elegant way for creating a great workflow.
- Used Redux for app state management.
- Created reducers and actions for our resources.
- Tested with the Redux Chrome extension. (Redux Devtool).
- Used Moment Package to Format TimeStamp.
