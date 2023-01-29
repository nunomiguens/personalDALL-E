# PersonalDALL-E

> Build of a AI Image Generation App MidJourney with Javascript and OpenAI API.

## Run it Locally

```
$ git clone https://github.com/nunomiguens/personalDALL-E.git
$ cd server
$ npm run start
$ cd client
$ npm run dev
```

## Env Variables

Create a .env file in the server directory and add the following

```
OPENAI_API_KEY= your OpenAI API secret key
MONGODB_URL= your mongodb uri
CLOUDINARY_CLOUD_NAME= your cloudinary client name
CLOUDINARY_API_KEY= your cloudinary API key
CLOUDINARY_API_SECRET= your cloudinary API secret

```

## Replace the fetch requests URL in the CreatePost.jsx and Home.jsx files.
> "https://<i></i>dall-e-b8xi.onrender.com/" 
with 
> "http://<i></i>localhost:8080/"

