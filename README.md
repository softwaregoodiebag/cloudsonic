# Cloudsonic
Cloudsonic is a lightweight mobile first web based music player.

<img src="https://raw.githubusercontent.com/softwaregoodiebag/cloudsonic/master/mobile.jpeg" width="200" height="400">

## Release version 1.0.0 task list
As it stands the player is fully functional for scanning and streaming tracks. Progress towards version 1.0.0 will depend on interest in the project (Project stars + watches). 

- [x] Admin login
- [x] Scanning of files and indexing
- [x] Queue tracks
- [x] Progressive web app
- [x] Responsive mobile first UI
- [ ] Reindexing and detecting when new tracks are added
- [ ] Basic user management
- [ ] View queue + queue management
- [ ] Per user playlists
- [ ] Tracks stats such as play count
- [ ] Service wait for database



## Setup
The project has been tested using docker swarm. To run Cloudsonic on your swarm use the following commands:

    docker stack deploy --compose-file docker-compose.yml
    
Tail the service logs and you should see the default admin password

    
    2020/04/14 18:55:37 Successfully connected to database
    2020/04/14 18:55:37 cf784f9f52d8705b88d97ef85abd859e
    2020/04/14 18:55:37 Service listening on :8081
    
Navigate to IP_ADDRESS:PORT and enter:

- Username=andmin

- Password=cf784f9f52d8705b88d97ef85abd859e

You will then be asked to change the admin account password.

## Supporting development
If you enjoyed this project — or just feeling generous, please consider donating to support ongoing development costs. Thank you

[![Donate with PayPal](https://raw.githubusercontent.com/softwaregoodiebag/cloudsonic/master/paypal-donate-button.png)](https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=K897UR95WQKTN&source=url)

## Licensing
This project is free to use. No tracking
