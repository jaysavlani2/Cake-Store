## Run Locally

Go to the project directory

```bash
  cd CAKE_STORE
```

Install dependencies

```bash
  npm install
```

Go to server directory and install dependencies

```bash
  npm install
```

Go to client directory and install dependencies

```bash
  npm install
```

Go to server directory and start the server

```bash
  npm run dev
```

Go to client directory and start the client

```bash
  npm run client
```

Start both client and server concurrently from the root directory

```bash
  npm run dev
```

## Tech

- [React](https://reactjs.org/)
- [Node](https://nodejs.org/en/)
- [Express](http://expressjs.com/)
- [Postgres](https://www.postgresql.org/)
- [node-postgres](https://node-postgres.com/)
- [Windmill React UI](https://windmillui.com/react-ui)
- [Tailwind-CSS](https://tailwindcss.com/)
- [react-hot-toast](https://react-hot-toast.com/docs)
- [react-Spinners](https://www.npmjs.com/package/react-spinners)
- [react-helmet-async](https://www.npmjs.com/package/react-helmet-async)

## Environment Variables

To run this project, you will need to add the following environment variables to your .env files in both client and server directory

#### client/.env

`REACT_APP_GOOGLE_CLIENT_ID`

`REACT_APP_GOOGLE_CLIENT_SECRET`

`REACT_APP_API_URL`

`REACT_APP_STRIPE_PUB_KEY`

### server/.env

`PGUSER`

`PGHOST=`

`PGPASSWORD`

`PGDATABASE`

`PGDATABASE_TEST`

`PGPORT`

`PORT`

`SECRET`

`REFRESH_SECRET`

`SMTP_FROM`

`STRIPE_SECRET_KEY`
