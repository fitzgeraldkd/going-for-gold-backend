# Going For Gold (Backend)

This is the backend repository for the [Going For Gold](https://goingforgold.netlify.app/) app. The frontend repository is available [here](https://github.com/fitzgeraldkd/going-for-gold-frontend).

## Setup

Fork and clone this repo. Then install the dependencies by running:

```sh
npm install
```

## Running the Server Locally

To run your server in development mode, run:

```sh
npm run dev
```

While your server is running, you can make requests to
[http://localhost:4000](http://localhost:4000). Check it out in the browser to
make sure your server works!

## Seeding Data

If you need to reset the database to its initial state, run `npm run seed` to reseed the database. This will overwrite all the data in the `db.json` file, replacing it with the contents of `seeds.json`.
