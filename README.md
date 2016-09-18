# reHarvest
//Food matching algoritm

var safeway = ["peanuts", "apple"];
var foodBank = ["apple", "orange"];
var match = false

for (var i = 0; i < safeway.length; i++) {
  if (foodBank.indexOf(safeway[i]) > -1) {   
    console.log("We have a match for you!");
    match = true
  }
    else {
      console.log("Sorry, there are currently no matches."); 
    }
}
