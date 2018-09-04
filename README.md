# multiagent-lab-3

# Install and running
Following this tutorial: https://github.com/battlecode/battlecode-scaffold-2017

This assumes that JAVA sdk 8.0 or higher is installed and the JAVA_HOME path variable has been set.

* Install choco or some other windows based package manager
* Install gradle
* Run ``` gradle build ``` in the main scaffolding directory
* You can now list available gradle tasks via ``` gradle -q tasks ```
* Now you can run a game with ``` gradle run ```. This runs a game in headless mode
* To see what is happening, open up the elctron client app under ```/client```
* You can add players to the ```src/``` folder to test new players
* To select players for a headless match run ``` gradle run -PteamA=<player_1> -PteamB=<player_2> -Pmaps="MagicWood"```
* For better debugging use ```gradlew runDebug```

# Gameplay specifics
Good strat: https://youtu.be/jkgt-c3Ag58?t=2443# battlecode 2017
