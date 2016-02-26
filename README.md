# Getting started

You'll need to get you raspberry pi setup and an connected to the internet either by an ethernet cable or wifi usb adapter.

These instructions assume you are using the latest version of Rasbian, *Jessie*, and not the previous version. See the [raspberry pi documentation]() for how to create an sd card with this operating system.

### Update software

First make sure your software is up to date, run the following in the terminal:

```
sudo apt-get update
sudo apt-get upgrade
```

Great. Check and see if you have node.js installed by typing `node` in the terminal. You should see a `>`, press `control + c` or `control + shift + c` to exit. If not you'll need to install node.js (hint: use your favorite search engine to find results for "how to install nodejs on Raspberry pi"). 

We're ready to install npm!

```
sudo apt-get install npm
```

Once node and npm are installed, we can clone the repo, enter the new directory, and install the software dependencies.

```
git clone [this repo]
cd [this repo]
sudo npm install
```

If this doesn't through an errors you should be ready to go.

Be sure to edit the `grow.json` file, to make sure it reflects your setup. Point the `host` to the IP address where you are hosting you Grow-IoT instance.




