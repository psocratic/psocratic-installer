# Psocratic Installer

The Psocratic Installer is used to set up a local development environment.

## Usage

The quickest way to use the Psocratic Installer is to execute the following in a shell:

```$ bash <(curl https://raw.githubusercontent.com/psocratic/psocratic-installer/master/dlrun)```

This will download the `psocratic-installer` repository, and execute the install script. 
The installation is mostly automatic, but you'll be initially prompted to enter you Psocratic email address and authenticate,
to enter your GitHub username and authenticate, and to periodically enter your computer password.

The installer will download several dependencies, including the [Psocratic repository](https://github.com/psocratic/psocratic).

The installer downloads the Psocratic repository to `~/.psocratic`, and adds a couple commands to your
login script (typically `~/.profile`). To undo the actions of the installe

Once the installer is finished, you may go read the instructions in the [Psocratic repository](https://github.com/psocratic/psocratic).

## Uninstall

The installer downloads the Psocratic repository to `~/.psocratic`, and adds a couple commands to your
login script (typically `~/.profile`). To undo the actions of the installer, you can simply remove
the Psocratic installation and these lines from your login script.
