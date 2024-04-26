# DevOps Monitoring

## Installation

You need to have `node` and `npm` installed on your system. Node version should be 20 or more.

### 1. Environment variable setup

In the backend folder, there is an `.env.example`. Rename this to just `.env` and update `DATABASE_URL`.

> Note: `DATABASE_URL` should be in this format `DATABASE_URL="postgresql://USERNAME:PASSWORD@HOSTNAME:PORT"`.

### 2. Running database migration

When running for the first time, you need to run database migrations first so to do so navigate to backend folder and run the following

```bash
npx prisma migrate deploy
```

### 3. Running backend

Navigate to backend folder and run the following

```bash
npm install
```

Once the dependencies are installed then run the following

```bash
npm run start
```

This will start the backend server at port 5000.


### 4. Running frontend

Navigate to frontend folder and run the following

```bash
npm install
```

Once the dependencies are installed then run the following

```bash
npm run dev
```

This will start the frontend server at port 4000.



