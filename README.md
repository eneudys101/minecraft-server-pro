# Dual Minecraft Home Server Setup

This project will get you setup with a easy to use dual minecraft server to jump between survival and creative with a simple command.

## Installation
This setup assumes that the host machine is visible on the network. This means firewall rules and Docker should be configured, which is outside the scope of this setup. The port that needs to be open is `25577`

Clone the repo and cd into it:

`git clone https://github.com/eneudys101/minecraft-server-pro.git`

`cd minecraft-server-pro`

### Building the server

Once in the directory run the command bellow

`docker-compose up`

### Usage

Once the server is up and running, switch over to computer running the latest minecraft version and add the server to your server list on minecraft.

Once connected to the server, simply run the command:

`/server creative` To connect to the creative instance,
`/server lobby` To connect back to the survival server.
