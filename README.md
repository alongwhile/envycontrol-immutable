<div align="center">
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://github.com/bayasdev/envycontrol/raw/main/logos/dark.png">
  <img alt="EnvyControl Logo" src="https://github.com/bayasdev/envycontrol/raw/main/logos/light.png" height="100px">
</picture>
<br>
Optimus made easy
</div>
<br>

# 👁‍🗨 EnvyControl

EnvyControl is a CLI tool that provides an easy way to switch between GPU modes on Nvidia Optimus systems (i.e laptops with hybrid Intel + Nvidia or AMD + Nvidia graphics configurations) under Linux.

### Immutable Fork

<i>This fork is intended to resolve the problem of envycontrol not working properly on immutable distros.   It is a work in progress and is mostly untested, however it has some confirmed limited functionality on Silverblue 38 running Gnome Wayland.  Hopefully it can be helpful for others.</i>

<b>How to run:</b>

1. Clone the repo: `git clone https://github.com/alongwhile/envycontrol-immutable.git`
4. Run the script from the python root: `python ./envycontrol.py -s <MODE>`  Replace <MODE> with integrated, hybrid, or nvidia as needed
5. You may see some errors.  Reboot anyway and hope for the best

See <a href="https://github.com/bayasdev/envycontrol">EnvyControl</a> github page for full CLI options, FAQ's, etc.
