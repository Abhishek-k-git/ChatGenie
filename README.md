- project setup

```bash
cd client
npm i
```

```bash
cd..
cd server
npm i
```

- start command (for both frontend and backend)

```bash
npm run dev
```

- frontend .env.local

```bash
GOOGLE_CLIENT_ID= (google authentication client id/api)
```

- backen .env

```bash
PORT=5000
MONGO_URL= (mongodb connection string/url)
SITE_URL=http://localhost:5173 (frontend url)
JWT_PRIVATE_KEY=kdjioe3834dkdKDJ378Sdsdjjk38798
GEMINI_API_KEY= (gemini api key)
GEMINI_MODEL=gemini-1.5-pro-latest
MAIL_EMAIL= (mail address for smtp mail delivery)
MAIL_SECRET= (above mail secret)
```
