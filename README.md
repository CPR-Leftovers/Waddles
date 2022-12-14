# Waddles - 🐧

Waddles makes it easy to configure dash, houdini and a host a AS3 CPPS.

## Basic setup

**Step 1** Install git, docker & docker-compose

```bash
$ sudo apt update
$ sudo apt install docker.io git curl
$ sudo curl -L "https://github.com/docker/compose/releases/download/1.25.5/docker-compose-$(uname -s)-$(uname -m)" -o /usr/local/bin/docker-compose
$ sudo chmod +x /usr/local/bin/docker-compose
```

**Step 2** Clone the repository & submodules
```bash
$ git clone --recurse-submodules https://github.com/CPR-Leftovers/Waddles && cd Waddles
```

**Step 3** Edit the config file
```bash
$ nano .env
```

**Step 4** Add your servers IP Address
```bash
$ nano servers.xml
```

**Step 5** Start the services
```bash
$ sudo docker-compose up
```

**Step 6** You're done!
