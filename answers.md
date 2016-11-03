# Q0: Why is this error being thrown?
This error is being thrown because there's no appropriate controller for the pokemons model :'-(

# Q1: How are the random Pokemon appearing? What is the common factor between all the possible Pokemon that appear? *
These are all the Pokemon that are found in the seed file! They all have a name and level.

# Question 2a: What does the following line do "<%= button_to "Throw a Pokeball!", capture_path(id: @pokemon), :class => "button medium", :method => :patch %>"? Be specific about what "capture_path(id: @pokemon)" is doing. If you're having trouble, look at the Help section in the README.
This routes the button to the capture method in pokemon and changes the pokemon's trainer id to the current_trainer.

# Question 3: What would you name your own Pokemon?
Goobertino.

# Question 4: What did you pass into the redirect_to? If it is a path, what did that path need? If it is not a path, why is it okay not to have a path here?
I redirected to the trainer's path. It needs the pokemon's trainer id.

# Question 5: Explain how putting this line "flash[:error] = @pokemon.errors.full_messages.to_sentence" shows error messages on your form.
This shows error messages on my form because it doesn't allow the user to continue with the action and lets them know at the top.

# Give us feedback on the project and decal below!
FUNNNNn sorry it's late though :\

# Extra credit: Link your Heroku deployed app
