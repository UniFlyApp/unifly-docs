  
# Need assistance?

> Our voluntary team is happy to assist you in using the software, taking feature requests and bug reports. We operate on the Discord platform, you can create an account and join in the conversation with [this link](https://unifly.gg/discord).


# Download the installer
First, download the [installer](https://unifly.gg/#download) from our website. After downloading it, run it and follow the on-screen prompts. After it has finished, UniFly will have been installed and will automatically be updated every time you run it.

# Setting up the Client

After running the client for the first time you will need to enter settings in order to setup some information about you.
1. You will be required to set a 'nickname' which will be your display name to other clients on the network.
2. You can optionally choose to connect to your simbrief by entering your simbrief username. This will allow you to quickly import a flightplan from Simbrief.
3. UniFly will have automatically attempted to detect the filepaths of any installed flight simulators on your computer. Manually add in any that it has missed.
4. When you're ready, enter in the details of your flight and hit connect. When both Network & Simulator are showing green `Connected`, you're good to go

# Installing Modelmatching

In order for UniFly to accurately show other aircraft in your simulator, you'll need to have installed a modelset of various aircraft and livery combinations. UniFly doesn't provide these, but does integrate with third party providers:
- For MSFS 2020/2024, we recommend installing [FSLTL](https://fslivetrafficliveries.com/) models.
- For XPlane simulators, we recommend installing [Bluebell](https://forums.x-plane.org/files/file/37041-bluebell-obj8-csl-packages/) models.
- For FSX/P3D, we recommend FLAi models.

If you wish to use a modelset that hasn't been mentioned here, you'll need to provide your own ruleset file following vPilot's specified `.vmr` file format inside the `%localappdata%/UniFly/rulesets` directory

## (MSFS Only!) FSLTL Models
These can be easily installed through the FlyByWire launcher.

> Note that you only need to install the `Base Models` package, and not their additional `Injector` software which uses the modelset for AI traffic.

## (X-Plane Only!) Bluebell Models

See below to first install the UniFly-XPLM plugin!

The models need to be installed inside of `X-Plane 11/Resources/plugins/UniFly-XPLM/Resources/CSL`.

> Note that this installation is identical to that of the `xPilot` software, if you're familiar with that.

### Installing the UniFly-XPLM plugin 

The XPlane plugin allows the UniFly client to communicate with the XPlane simulator. 

It should be installed from [our website](https://unifly.gg/#download) into the `X-Plane 11/Resources/plugins/` folder.

> This part of the software **does not automatically update**. If you're having trouble using UniFly with XPlane, it's a good idea to check that your plugin is up-to-date.


# Time & Weather Settings
UniFly needs to correct for differences in terrain elevation and atmospheric simulation between different simulators. Some simulators have a more advanced atmospheric simulation affecting altimeter readings, and frequently two simulators will not have similar terrain maps for airports.

Therefore UniFly relies on all pilots flying on real world weather and real world time in order to correctly show aircraft at sensible altitudes and elevations, which is particularly important when connected on the ground. If you're seeing parked aircraft floating or sinking into the ground, the first thing to check should be your time and weather settings.

### Rex WeatherForce
Rex WeatherForce is known to confuse UniFly's altitude readings. It has been reported that it helps to enable `Real-Time Weather Injection` under Rex's Weather Engine Settings.
