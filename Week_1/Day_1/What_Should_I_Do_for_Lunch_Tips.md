### Tips

Try experimenting with the comparison operators (`<`, `>`, `===`, etc.) in the node REPL, which you can launch using the `node` command in Vagrant.

Work on your code iteratively - that means in small pieces.

To help you figure out how to use `hungry` and `availableTime` inside your function, try outputting their values to the Terminal as follows.

```javascript
const whatToDoForLunch = function(hungry, availableTime) {
  if (hungry && availableTime < 20) {
    console.log("Pick up a snack and eat it in the lab!");
  } else if (hungry && availableTime >= 20 && availableTime <= 30) {
    console.log("You deserve a break! Take time to cook a tasty meal.");
  } else if (hungry && availableTime > 30) {
    console.log("This is a bootcamp... maybe reconsider your time.");
  } else {
    console.log("You're not hungry! Get back to work!");
  }
};
```