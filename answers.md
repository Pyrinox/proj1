# Q0: Why is this error being thrown?
There is no Pokemon model that the HomeController can utilize.

# Q1: How are the random Pokemon appearing? What is the common factor between all the possible 
Pokemon that appear? *
The random Pokemon are appearing because of the seeds.rb file. The common factor for all the pokemon that appear is that they are being created by default from the seeds.rb file.

# Question 2a: What does the following line do "<%= button_to "Throw a Pokeball!", capture_path(id: @pokemon), :class => "button medium", :method => :patch %>"? Be specific about what "capture_path(id: @pokemon)" is doing. If you're having trouble, look at the Help section in the README.
The line makes a button called "Throw a Pokeball". When clicked it goes to the capture model of the Pokemon controller. The button is of medium size, and calls the capture path route in the routes.rb file.

# Question 3: What would you name your own Pokemon?
I would name my pokemon Zorro. 

# Question 4: What did you pass into the redirect_to? If it is a path, what did that path need? If it is not a path, why is it okay not to have a path here?
I passed the "trainer" path. It needs an ID of the current trainer.

# Question 5: Explain how putting this line "flash[:error] = @pokemon.errors.full_messages.to_sentence" shows error messages on your form.
It sets flash key's value to Pokemon default error setting.

# Give us feedback on the project and decal below!
I think the project theme is funner than most other projects, and the decal itself is very informative. Don't like the hour and location much though.

# Extra credit: Link your Heroku deployed app
