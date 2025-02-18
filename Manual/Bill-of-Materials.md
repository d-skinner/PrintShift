# PrintShift Bill of Materials

The LIVE Bill of Materials will live here:

[BoM on Google Sheets](https://docs.google.com/spreadsheets/d/1gTF6RvdNjgoJNNBqXj-OhuOjt69_Wzujfkq8HkN1fU4/edit?usp=sharing)
Anyone can comment on the google doc - ideally, comments will be resolved and then removed.

[CSV Snapshot as of 11.05.2021](/Manual/assets/PrintShift BOM - 11.05.2021.csv)

## BoM Sections
The BoM is divided into sections based on where the parts are used; this is to try to help organize it, and to more easily edit and update.  


### Conveyor Belt Hardware
There is a separate page to cover and discuss [belt materials](/Belt Materials.md)

The rest of the parts here are hardware for mounting the belt to the Prusa Mini's bed carriage.  The conveyor belt hardware can be added at any point, and while it raises the bed 4mm it does not affect normal operation of the mini in any way... at least until you slide a belt onto it :-)

Basically none of these parts can be substituted out without redesigning something, but there are bound to be cheaper suppliers, especially in quantity.


### Ejector Hardware
These parts are everything required to mount and run the ejector motor, as well as connect it to the conveyor belt mounted on the bed.
This includes the control microswitch and wiring.

Generally, installing these I would include the 5v buck converter to run a raspberry pi - although using wire nuts to attach means it's easy to add later.

A lot of these parts (wire nuts, crimp lugs, getting power for the motor in the first place) could be substituted out as desired; I chose them as the easiest to install reliably.


### Belt Material
The Kapton and various tapes used for the belt.  I treat tapes as '1 roll per printer' so they add a little more to the BoM than I would like... but it's better to be expansive I think.


### Raspberry Pi
Mounting a Raspberry Pi and running Octoprint on the mini is optional, but adds a huge amount of functionality.  In the future, Prusa has said that they would expand the capabilities of the BuddyBoard and its ethernet port, so perhaps the pi will become redundant... but I don't think that it will.

The Raspberry Pi + camera allows you to access your printer from far away to monitor and start or queue prints.  Additionally, I use Octoprint plugins to connect my machines to the cloud and add print queueing.


### Optional Parts
This includes parts trays, GoPro mounts, my silly clock mount (I love it), and the base to put the printer on if you utilize a rackmount or other print farm system.
