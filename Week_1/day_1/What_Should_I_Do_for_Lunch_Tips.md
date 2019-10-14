```javascript const whatToDoForLunch = function(hungry, availableTime) {
  if (hungry === false) {
    console.log("You are not hungry, get back to work!");
  } else if (hungry && availableTime < 20) {
    console.log("Pick something up and eat in the kitchen with your classmates");
  } else if (hungry && availableTime >= 20 && availableTime < 30) {
    console.log("Go try a new place in gastown");
  } else {
    console.log("you have to much time on your hands, this is a bootcamp!");
  }
};
```