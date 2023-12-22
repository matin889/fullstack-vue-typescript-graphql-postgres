Developed by Md Aabdul Matin

## Deployed site

https://fullstack-typescript-vue-postgres.netlify.app/

## Docker Pull

docker pull matin889/fullstack-project-typescript:tag

## Project Setup

### Step 1:

Run:

```sh
npm install
```

This will install all the project dependencies.
Keep this terminal aside.

### Step 2

Open **another** terminal
Run the command:

```sh
cd src/
```

Then run

```sh
npx prisma db push
```

you should see the message: 🚀 Your database is now in sync with your Prisma schema.

Then run

```sh
npx prisma db seed
```

you should see the message: 🌱 The seed command has been executed.

Then go back by

```sh
cd ..
```

Then run:

```sh
npm start
```

you should see the message: 🚀 Server ready at: http://localhost:4007

### Step 3

Now go back to the first terminal where we ran the npm install
and Run the command:

```sh
npm run dev
```

This Compile and Hot-Reload the website

The project is now finally setup

##View Project

### Open a browser and go to: http://localhost:5173/

Here, the website will be up.

### Open another tab and go to: http://localhost:4007

Here, the Yoga GraphQL playground will be running
