# tutorial10-adpro
Name: Muhamad Pascal Alfin Pahlevi <br>
NPM: 2206046752

## Experiment 1.2
<img width="299" alt="image" src="https://github.com/PascalPahlevi/tutorial10-adpro/assets/143638456/b27f60be-2088-4491-8485-f62fb4b19a7e"> <br>
From the screenshot above, after implementing `println!("Pascal's Computer: hey hey")` into the code after `spawner.spwan(future:async {...`, we can see that the line "hey hey" was printed out first followed by "howdy!" and "done!". The reason this is happening could be because `println!("Pascal's Computer: hey hey")` was implemented outside of the `spawner.spawn` method hence the print statement would not need to follow the timer. 
