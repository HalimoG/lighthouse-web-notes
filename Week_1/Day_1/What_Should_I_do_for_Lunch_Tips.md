### Tips

Try experimenting with the comparison operators (`<`, `>`, `===`, etc.) in the node REPL, which you can launch using the `node` command in Vagrant.

Work on your code iteratively – that means in small pieces.

To help you figure out how to use `hungry` and `availableTime` inside your function, try outputting their values to the Terminal as follows.

```function whatToDoForLunch(hungry, availableTime) {
 var what = "";
 if (hungry){
   if (availableTime < 20 ){
     what= "eat it in the lab";
   }
   else if (availableTime = 20 && availableTime <= 30){
     what = "try a place nearby";
   }
   else {
     what = "we're in a bootcamp";
   }
 }
 else{
   what =  "get back to work";
 }

 console.log("I don't know what to do!");
 console.log(what);

}
```