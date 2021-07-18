## Contributing

Contributions are welcome! Feel free to open an issue or submit a pull request if you have a way to improve this project.

If you are making a significant change, please open an issue before creating a pull request. This will allow us to discuss the design and implementation.

Make sure your request is meaningful and you have tested the app locally before submitting a pull request.


### Installing Requirements

#### Requirements

* NodeJS
* Yarn
* TypeScript

### Clone the repository

```
git clone https://github.com/DenverCoder1/custom-icon-badges.git
cd custom-icon-badges
```

### Installing dependencies

```bash
npm install && npm run install-client
```

### Config vars

To work with a database, in a `.env`, include the following:

```env
DB_URL=mongodb+srv://<username>:<password>@<cluster>.mongodb.net/<dbname>?retryWrites=true&w=majority&tls=true
```

The URL should be the URL provided by MongoDB and the database should have a collection named `icons`.

More info on setting up a free Atlas database on [MongoDB's documentation](https://docs.atlas.mongodb.com/getting-started/).

### Build and run the app locally

```bash
yarn dev
```

### Run the app locally (without building)

```bash
npm start
```

Use <http://localhost:5000/> as the base URL to access the server-side routes

### Linting

```bash
yarn lint
```