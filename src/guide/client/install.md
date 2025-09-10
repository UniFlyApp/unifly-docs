# Client

The UniFly Client runs on your computer and connects your flight simulator to our network.

## Download the installer
First, download the [installer](https://unifly.gg/#Download) from our website. After installing it, run it and follow through the prompts. After it has finished, UniFly has been installed and will automatically be updated
every time you run it.

# Setting up the Client

After running the client for the first time you will need to enter settings in order to setup some information about you.
1. You will be required to set a 'nickname' which will be your display name to other clients on the network.
2. You can optionally choose to connect to your simbrief by entering your simbrief username. This will allow you to quickly import a flightplan from Simbrief.
3. UniFly will have automatically attempted to detect the filepaths of any installed flight simulators on your computer. Manually add in any that it has missed.
4. When you're ready, enter in the details of your flight and hit connect. When both Network & Simulator are showing green `Connected`, you're good to go

## Weather Settings
UniFly needs to correct for differences in terrain elevation and atmospheric simulation between different simulators. Some simulators have a more advanced atmospheric simulation affecting altimeter readings, and frequently two simulators will not have similar terrain maps even at airports.

Therefore UniFly relies on all pilots flying on real world weather and real world time in order to correctly show aircraft at sensible altitudes and elevations, which is particularly important when they're on the ground with a parked aircraft. If you're seeing parked aircraft floating or sinking into the ground, the first thing to check should be your time and weather settings.

### Rex WeatherForce
Rex WeatherForce is known to confuse UniFly's altitude readings. It has been reported that it helps to enable `Real-Time Weather Injection` under Rex's Weather Engine Settings.
