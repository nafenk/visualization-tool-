# Traffic Visualisation tool for Gothenburg 

This project utilize publish and subsribe, and pipe and filter as architectural models. The purpose of the project is to visualise simulated trip requests that one may make when using transportation in Gothenburg city. 


The system consists of a map that acts like a visualisation tool to the user, the potential user in this case, transportation services provider, Västtrafik. There is legend presented on the map that gives an explanation of each line color and it's meaning. A green line represents an available route that connects bus stops, from the origin to the destination. A white line represent the walking route for the traveler from their standing location towards the bus stop in which they would travel from. A red line represents a bottleneck between two locations. The user is able to pause and unpause the map. This feature allows the user to observe the routes without the distraction of new lines coming in.
Another feature of the map, is zooming in and out the map. This allows the user to zoom in on the map to have a better and clearer view of the route/streets. This fulfills the interactive mode that is required.

In order ot run this project: 

Firstly, you have to run "commuincator.py" in the "caller" folder, which is subscribed to the "publisher.py" in the "generator" folder. 

the output of the run command is the following: 
Connected with result code 0

Secondly, you have to run "publisher.py" in the "caller" folder. The output of that command is messages. 

Finally, you can view the visualisation tool by running map.js in src file in visualiser folder. 
