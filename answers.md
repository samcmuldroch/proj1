# Q0: Why is this error being thrown?
The error is being thrown because it needs to be migrated

# Q1: How are the random Pokemon appearing? What is the common factor between all the possible Pokemon that appear? 
All the random Pokemon are appearing one at a time with every refresh based on the seed. A common factor between all the Pokemon that appear is that they are all wild.  The pokemon are only Squirtle, Charmander, Bulbasaur and Pikachu because thsoe are the only Pokemon provided in the seed.

# Question 2a: What does the following line in the help text do? Be specific about what "capture_path(id: @pokemon)" is doing. If you're having trouble, look at the Help section in the README.
The following line creates a capture path when we click the button which in our routes file we root to our capture function.  The paramater passed in is the id of the current pokemon.  We can then access that parameter in our funciton.

# Question 3: What would you name your own Pokemon?
Sydney

# Question 4: What did you pass into the redirect_to? If it is a path, what did that path need? If it is not a path, why is it okay not to have a path here?
I wrote the line: redirect_to trainer_path(params[:trainer])
This is a path which goes back to the original page (which is the page for the trainer at that id).  It is nessisary to have a path here because there is no show page for the damage function. 

# Question 5: Explain how putting this line "flash[:error] = @pokemon.errors.full_messages.to_sentence" shows error messages on your form.
It pops up with a red little bar above the thing where you create a new pokemon.

# Give us feedback on the project and decal below!
Keep up the good work.

# Extra credit: Link your Heroku deployed app
