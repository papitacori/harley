const Discord = require("discord.js");
const client = new Discord.Client();

client.on("ready", () => {
    console.log("BOT LISTO!");
 });
 
 client.on("message", (message) => {
   if(message.content.startsWith(".efr")) {
     message.channel.send("mamarre");
   }
 
 });
 
 client.login("https://discordapp.com/api/webhooks/1036730937817448458/HhthGabVOBuKynM4AxY2HkarTO1BBx7pIgrtBchW-SV5tO1NVDrIctDnq9iTumNlCaOV");
