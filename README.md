# node-snapdrop
Just the original [Snapdrop](https://github.com/RobinLinus/Snapdrop), with complete Node.js server.

Modified https://github.com/Bellisario/node-snapdrop.git so that when server & clients are on the same LAN, clients discover each other.

## How to run
Download the repository in a folder, cd it, install all dependencies with `npm i` and use this command: `node index.js`.
### Run within your ip
Use this command, instead, to run not locally but in your public "sharable" ip: `node index.js public`.\
Make sure to check your ip address using your OS command.

### Run on LAN:
`node index.js LAN`
Use this comment, instead, to run when server & clients are on the same LAN so that clients are able to discover each other.
