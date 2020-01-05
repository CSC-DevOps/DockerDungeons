# Docker Dungeon > NodeJS

Enter the dungeon.

```
$ bakerx pull CSC-Devops/Images#Spring2020 ubuntu-node-dungeon
$ bakerx run dung0 ubuntu-node-dungeon --memory 2048
```

## Overview

### Levels

#### Level 0

Run a simple node.js webserver, to enter level 1

```
root@dungeon:/# LVL0
You enter level 0.
You see a server.js file in your directory.

You try to run it with 'node server.js'
Nothing happens.

```

Challenges:

* Examine the contents of `server.js` file.
* Install nodejs and npm.
* Find out your ip address.
* Visit site in your web browser.
* 🔮 Send command to check if server is running from your host computer.

#### Level 1

Run an express node.js webserver.

```
root@dungeon:/srv/level0# LVL1
localhost [127.0.0.1] 8080 (http-alt) open
You enter level 1.
You see a more fancy file in your directory.

You notice a package. But don't know what to do with it

```

Challenges:

* Install packages.
* Start server (hint: you may need to make a small change in the server code)
* Inspect code (`cat`) and send payload to server (hint: `curl`).

#### Finish

If you send the payload to the server, then type the command `ASCEND`. You should complete the dungeon! Taking any shortcuts might lead to failure!

```bash
Golden key found...

The golden key unlocks the invisible stairs. You climb and see daylight.
The dungeon begins to crumble...but you escape.
Connection to 127.0.0.1 closed by remote host.
Connection to 127.0.0.1 closed.
```




