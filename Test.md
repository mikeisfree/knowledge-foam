# Foam Note Templates

Foam includes note templates! 
This allows you to easily create notes that have similar structure without having to use copy/paste :)

Templates support the [VS Code's Snippet Syntax](https://code.visualstudio.com/docs/editor/userdefinedsnippets#_snippet-syntax), which means you can:
- add variables to the newly created note
- add tabstop to automatically navigate to the key parts of the note, just like a form
Below you can see an example showing a todo list and a timestamp.

## Todo List

1. First tabstop
2. A second tabstop
3. A third tabstop

Note Created: 2025-05-10

---

## Core Features

- End-to-end Encrypted Password Manager (with built-in 2FA authenticator)
- Alias Generator
- Built-In Email Server
- Open Source & Fully Self-Hostable
- Browser Extensions Available On All Major Browsers

The full list of features can be found on the AliasVault website: [https://www.aliasvault.net/features](https://www.aliasvault.net/features?ref=noted.lol).

## Browser Extensions

## Installing AliasVault

AliasVault offers a free cloud-hosted variant that you can try out on [https://www.aliasvault.net](https://www.aliasvault.net/?ref=noted.lol). However you can also install AliasVault on your own servers. The following steps will show you show.

AliasVault consists of several Docker containers that are managed via Docker Compose. In order to make the installation as easy as possible, AliasVault comes with a bundled `install.sh` script that guides you through the installation process and takes care of setting up your.env file and more. The whole installation only takes a matter of minutes.

**Requirements**:

- Linux VM with root access (Ubuntu/AlmaLinux recommended) or Raspberry Pi
- 1 vCPU
- 1GB RAM
- 16GB disk space
- Docker installed

**Execute the following commands via a shell:**

```
bash

# Download install script from latest stable release

curl -o install.sh https://raw.githubusercontent.com/lanedirt/AliasVault/main/install.sh

# Make install script executable and run it. This will create the .env file, pull the Docker images, and start the AliasVault containers.

chmod +x install.sh

./install.sh install
```
bash
