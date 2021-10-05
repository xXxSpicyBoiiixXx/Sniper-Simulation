# Sniper-Simulation


Sniper is a simulation that simulate x86-64 with up to 1000 cores. 

To run the sniper simulation you will first need to go into the docker file and run make run or make run-root to get into the root version of the ubuntu file. 

After that you can run ./run-sniper -- /bin/ls as a test run to see if sni[er is working and then run the configuations.

Now we can run sniper with our desired configuration, such as ./run-sniper -n 12 <file path>

You can also make a configuration file in the config section of sniper and from there use the following to run sniper while in the docker containter. 

./run-sniper -n 2 -c <configuration file> <file path> 
