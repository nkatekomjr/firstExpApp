### Clone the Repository
Clone the repository only if you don't have a copy already on your local machine
`$ git clone https://github.com/nkatekomjr/firstExpApp`


### Get recent changes
Provided you have the project already localy. Mode to the folder of the project
`$ cd /path/to/the/project`

then pull the latest changes
`$ git pull`

### `node_modules`
|You usually don't want to track your `node_modules` folder. On a small project like this it's OK, but as the project grows and you add more dependencies that folder will grow even bigger.
I added it to the '.gitignore' file to tell `git` to not track it.

|Everytime you pull the project you need to run the following
`$ npm install`

to make sure you have the latest node packages (if any was added or updated)
