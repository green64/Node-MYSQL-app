# Node-MYSQL-app
[Node-MYSQL-App](https://green64.github.io/Node-MYSQL-app/)

**Object**

Our goal with the Bamazon app was to combine node.js and 

***Technology used***
This app uses JavaScript, Node.js and MYSQL plus 2 NPM packages: MYSQL and Inquirer

***Code excerpts***

This our first project with a database we created. Here's how we connected:

```var connection = mysql.createConnection({
host: "localhost",
port: 3306,

// Your username
user: "root",

// Your password
password: "",
database: "bamazon_db"
});
```

Queries used MYSQL syntax: ```connection.query("SELECT * FROM products", function (err, res) {```
            
***Video walkthrough***

Because this is a command-line app, there's not an HTML page where you can watch it in action. In the video below, I walk through a quick demo to show the app is querying and updating the MYSQL database. 

:video_camera: [Liri app walkthrough](hhttps://youtu.be/YXXJ1gQlZxY)

