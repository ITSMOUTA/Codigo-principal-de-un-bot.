buenas usuario de GITHUB, antes de empezar tengo que decir que este codigo el solo una parte de todo tu bot.
Puede copiar y pegar.



const http = require('http');
const express = require('express');
const app = express();

//
app.use(express.static('public'));

app.get("/", function (request, response) {
  response.sendFile(__dirname + '/views/index.html');
});

app.get("/", (request, response) => {
  response.sendStatus(200);
});

app.listen(process.env.PORT);

setInterval(() => {
  http.get(`http://${process.env.PROJECT_DOMAIN}.glitch.me/`); 
}, 280000);



const Discord = require("discord.js");
const client = new Discord.Client();

client.on("ready", () => {
    console.log("bot ready!");
 });
