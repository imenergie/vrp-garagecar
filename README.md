1. Copy the vrp folder where the vrp folder on the server is located.
2. From the vrp folder on the server find __resource.lua. Search line: "modules/basic_garage.lua", and add this line next to it "modules/basic_garagecar.lua",
Example: 
"modules/basic_garage.lua",
"modules/basic_garagecar.lua",

now search line: "client/basic_garage.lua", and add this line next to it "client/basic_garagecar.lua",
Example:
"client/basic_garage.lua",
"client/basic_garagecar.lua",

3. from vrp/cfg/garagescar.lua you have to add your cars and locations and of course from vrp/cfg/garages.lua you need to remove your cars and the locations you have added in garagescar.lua

Start the server. Well done!


Modified by Energie
