# Odin Project Recipe App README

## Project Overview
This is a recipe application developed as part of the Odin Project, a full-stack JavaScript curriculum. The application allows users to view, create, update, and delete recipes. It showcases the utilization of HTML, CSS, JavaScript, Node.js, and MongoDB.

## Features
1. **Recipe List:** Display a list of all recipes added by users.
2. **Recipe Details:** View detailed information about each recipe, including ingredients, preparation steps, and comments from other users.
3. **Add New Recipe:** Create a new recipe by providing the necessary information.
4. **Edit Recipe:** Update the details of an existing recipe.
5. **Delete Recipe:** Remove a recipe from the database.
6. **Search:** Search for a specific recipe using keywords.

## Installation
To get the application running locally:

1. Clone this repo
```
git clone https://github.com/yourusername/odin-project-recipe.git
```

2. Install NPM Packages
```
npm install
```

3. Run the Application
```
npm start
```
The application will start on `localhost:3000`

## Environment Variables
In order to connect with the MongoDB database, you need to provide the following environment variables:

* `DB_URI`: URI to your MongoDB database
* `DB_NAME`: Name of your MongoDB database

## Database Seeding
To seed the database with sample data, run the following command:
```
npm run seed
```

## Testing
To run tests, execute:
```
npm test
```

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

## License
This project is licensed under the MIT License.

## Credits
This project was created as part of the [Odin Project](https://www.theodinproject.com/) curriculum. 

---

For more information or help, please check the [Odin Project Community](https://community.theodinproject.com/).
