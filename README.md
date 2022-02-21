<h1 align="center">Thumbs Up</h1>

## Description

[Live Demo](https://lit-castle-22669.herokuapp.com/)
<p align="center">
<img src="">
</p>

---
## Installation
**Make sure your system meets the requirements below before following installation**
1. Clone this repo to your local machine:
    - `git clone https://github.com/Mitch311G/Thumbs-Up.git`
2. Navigate the repo's root directory:
    - `cd Thumbs-Up`
3. Install project dependencies:
    - `npm install`
4. For local development, set up a local [PostgreSQL](https://www.postgresql.org/docs/) database.
    - After your local database is available, create a `.env` file in the root directory containing your local database info. See `.env.example` for reference. **NOTE:** The PostgreSQL server will defualt to `port 5432`.
    - Uncomment lines inside section titled **"for development purposes only"** in the `backend/database/schema.sql` file.
    - Run `psql -d blueocean -f ./backend/database/schema.sql` in the root directory of the project to create the project's database and load test data.
5. Run `npm run build-dev` to build `dist/bundle.js`.
6. Run `npm run start-dev` to start development server at `localhost:3000`.
7. Start developing!

### Requirements
1. Install the following to your system (if not done already):
    - [Node.js and npm](https://nodejs.org/en/download/)
    - [PostgreSQL](https://www.postgresql.org/download/)
2. Obtain a [Google Maps API key](https://developers.google.com/maps)
---

## Usage

<p align="center">
<img src="">
</p>

---

## Provided scripts
- `npm run build-dev`
    - Using webpack and babel, this will bundle and transpile the contents of `client/src` directory into bundled `.js` file for browser consumption, which is linked to `index.html`, then **watch for changes and re-bundle on file changes**.
- `npm run build`
    - Builds the bundle for production and **does not watch for file changes**.
- `npm run start-dev`
    - Starts the development server (default is localhost:3000), then **watches for changes and restarts the server with updated content on file change**.
- `npm run start`
    - Starts the app's server, but **does not watch for file changes**.
---

## Author and acknowledgment
***Thumbs Up*** was written by [Mitchell Gardner](https://github.com/Mitch311G), [Prith Jaganathan](https://github.com/prith98), [Matt Dziedzic](https://github.com/MrFripple), [Neil Mosser](https://github.com/NeilMosser), [Ezra Pullido](https://github.com/ezra-pullido), and [Sterling Muller](https://github.com/sterlingmuller).
