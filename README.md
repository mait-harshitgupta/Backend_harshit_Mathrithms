# Backend_harshit_Mathrithms
I have used node.js and express.js for making he Restful API. To post data to the API i have created a post route and using postman software we can add data to the API.

The API Runs on the localhost 5000.

The two endpoints namely '/users' that returns information of all the users. '/users/' which returns the information of a specific user.

Used different node modules : const express = require("express"); const bodyParser = require("body-parser"); const mongoose = require("mongoose"); const ejs = require("ejs");

I have used mongodb locally to store the database : mongoose.connect("mongodb://localhost:27017/information", {useNewUrlParser: true});
