# Getting started

You'll need to get you raspberry pi setup and an connected to the internet either by an ethernet cable or wifi usb adapter.

First make sure your software is up to date, run the following in the terminal:

```
sudo apt-get update
sudo apt-get upgrade
```

Great. We're ready to install nodejs and npm! Try:

```
sudo apt-get install nodejs npm
```

If that doesn't work, a quick google for "install nodejs on Raspberry pi" should get you pointed in the right direction.

Once node and npm are installed, we can clone the repo, enter the new directory, and install the software dependencies.

```
git clone [this repo]
cd [this repo]
sudo npm install
```

If this doesn't through an errors you should be ready to go.

Be sure to edit the `grow.json` file, to make sure it reflects your setup. Point the `host` to the IP address where you are hosting you Grow-IoT instance.




