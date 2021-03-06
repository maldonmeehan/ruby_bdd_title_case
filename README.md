## Ruby Behavior-Driven Development - Title Case

#### An project to learn Ruby BDD, June 27, 2016

#### By Maldon Meehan & Noah Yasskin

## Description

Lesson: Behavior-Driven Development (BDD), Red-Green-Refactor, RSpec, Ruby Code Styling, Naming Conventions and commits.

Project: Create Ruby method on the String class that takes a string of word(s) from the user and returns it in title case.

## Specifications
| Behavior        | Input       | Output  |
| ------------- |:-------------:| -----:|
|   It capitalizes the first letter of a single word    | beowulf | Beowulf |
|   It capitalizes the first letter of a multiple word sting    | beowulf begins | Beowulf Begins |
|   It does not capitalizes designated words (prepositions, conjunctions, etc)    | beowulf from brighton beach | Beowulf from Brighton Beach |
|   It does capitalizes designated words if they are the first word   | from beowulf to the hulk | From Beowulf to the Hulk |
|   It handles non-letter characters | 57 beowulf alternative endings!! | 57 Beowulf Alternative Endings!! |
|   It manages all uppercase entries | BEOWULF ON THE ROCKS | Beowulf on the Rocks
|   It manages mixed case entries | BeoWoluf aNd mE | Beowulf and Me


## Setup/Installation Requirements

* Clone this repository onto your computer
* Run rspec to see tests pass
* Run bundle install in your project directory to ensure all gems are installed.
* Run ruby app.rb in your project directory to start Sinatra
* Open a browser of your choice to localhost:4567

## Setup/Installation Requirements

* Clone this repository onto your computer
* Run rspec to see specs pass
* Run ruby app.rb in your project directory to start Sinatra
* Open a browser of your choice to localhost:4567

## Known Bugs
No known bugs

## Support and contact details

If you have any questions please feel free to contact Maldon or Noah on github

## Technologies Used

* Ruby
* Postgres
* Sinatra

### License

MIT License

Copyright (c) 2016, **Maldon Meehan & Noah Yasskin, Epicodus**
