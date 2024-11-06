# UCVD Legacy

> **Note: This project is no longer actively maintained, and the host URL endpoint is no longer active. It has been archived for historical purposes. Feel free to explore the code, but please note that it is no longer in use or supported.**

Ultimate Cats vs Dogs is an HTML5 game created in 2014 for fun. The game was originally created in Gamemaker Studio but since has been converted into a regular HTML5 game. No special frameworks were used to build the game. The premise of the game is that cats and dogs battle each other in tanks. You, the player select one side to play as and then engage in a tank battle. 

This game can be played both on the desktop and on mobile devices. It is also possible to port the source code to Android and iOS using tools such as [CapacitorJs](https://capacitorjs.com/). 

The source code for this project is for demonstration and reference. This project was included with the intention of being archived and for personal enjoyment and isn't intended for any commercial use.

## Controls

### Desktop Controls
- `WSAD` - use these keys to navigate the tank. `W` and `S` will move the tank forward and backward. `A` and `D` will rotate the tank.
- `Arrow Keys` - the arrow keys will move the crosshairs to aim.
- `Enter` - the Enter key will shoot projectiles. 

### Mobile Controls
- `Left bottom corner of screen` - use this area of the screen as a directional pad to move and rotate the tank. 
- `Right bottom corner of screen` - use this area of the screen to move the crosshairs to aim. 
- `Center bottom of screen` - use this area of the screen to shoot projectiles. 

## Play Locally

### Play Directly in Your Browser
The game runs on static HTML5. If desired, you can simply open the `index.html` file in your preferred browser, and the game will run.

### Play Using Docker
If you prefer to launch the game from a VM/Server, you can utilize the Docker Compose service to generate a container running NGINX on Port 80.

This option requires Docker and Docker Compose to already be installed on your machine. You can start the container and retrieve the hostname it will run on by executing the following command:
```
docker compose up -d && hostname -I
```
Copy the hostname or IP address and paste it into your browser. The game will run as if it were on your local machine. To stop the service, simply run:
```
docker compose down 
```

