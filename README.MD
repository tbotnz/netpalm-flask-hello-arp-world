# netpalm-flask-hello-arp-world
simple hello world app to pull arp table off multiple devices and render into a nice searchable datatable

![netpalm arp table](/netpalm_arp.gif)

### getting started
- ensure you have a [netpalm](https://github.com/tbotnz/netpalm) container running
- git clone the project ``` git clone https://github.com/tbotnz/netpalm-flask-hello-arp-world.git && cd netpalm-flask-hello-arp-world ```
- update the app.py with your ```NETPALM_SERVER_IP``` ```NETPALM_SERVER_PORT``` ```NETPALM_API_KEY```
- install the requirements ```pip3 install -r requirements.txt```
- run the app ```python3 app.py```
