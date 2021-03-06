# Webserver with PHP for iSH
Shell script to setup apache2 webserver with PHP support on iOS devices.

## Install iSH
Detailed instructions can be found [here](https://ish.app/).

## Install git
At first you'll need git to clone this repository. Start iSH and run
`apk update`
and
`apk add git`.

## Setup apache2 and git

After that clone this repository with
`git clone <repository url>`.

Now switch to the created folder and make the .sh files executable with `chmod +x setup.sh` and `chmod +x start.sh`. Now run the setup script with
`sh ./setup.sh`.

During the script you will be asked for location access. This is needed to keep the iSH running when it is in background.
You should now be able to access your webserver on "http://127.0.0.1:8000" on your iOS Device.

From now just run `sh start.sh` from the folder to start apache2!
