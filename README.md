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
