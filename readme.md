create script.js file
install express
## npm i express
express js boilerplate code
## const express =require('express');
 const app=express();

//app.set("view engine","ejs");
app.get('/',function(req,res){
    res.send("hello dost");
});

app.listen(3000); ##

express js ejs setup
  //install ejs 
   ## npm i ejs
    //set view engine
    create views folder
    //create ejs file
    //render ejs file inside route

express static files setup 
## app.use(express.static("./public"));
architecture of public folder

express generator
## express generator ek folder bana ke deta hai ,jiska matlab aapko khudse folder nahi banana hai.to express generator saree file ko is folder me daal ke dega.

steps to use express generator.
    // sabse pahle jeevan me ek baar laptop par install karo globally
  ## npm i express-generator -g
    // to create new app anywhere
    // open cmd move to desktop
    // create new app :
  ## express appname --view=ejs
now use two commands
    //cd appname
    //npm i
    // open it on vs code.


database
mangoodb=>non relational