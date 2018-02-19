# Re-Dream Public Map Repository

This is a repository for people to work on the Re-Dream Map

This work is licensed under a MIT License.

To discuss or propose changes to this map, please use the discord #redream-dev channel: https://discord.gg/9Gc8DeA or make a issue or pull request with detailed ideas or additions.

# GUIDLINES READ THIS BEFORE PULL REQUESTS OR PUSHES
**TEST ALL CHANGES YOU MAKE BEFORE PUSHING OR CREATING PULL REQURESTS**

Make sure that your map or edits do not cause leaks or lighting error, if making a push request, compile the map showing the changes (if visible)

Make sure that you have standardised brushwork, worldbrushes going to the void shouldnt be greater than 64 unit to save global map grid space.

Do not have brushes that are not of units to the power of 2. (Do not do 1 unit brushes in width or diameter)
Try to optimize any big changes, func_detail world geometry that is:

* Not in contact with void (knowledge and discression applies for performance reasons)

* Misc detail (should be a model if high detailed)

Keep names for files conventional and coherant (Do not name your map meme_x321_v4_kabus or other silly things)

# Note
* The map is assembled and compiled from a master vmf with instances for ease of editing multiple maps without causing hammer to crash from opening large scale VMF files.

* The current master VMF is redream_waterlands.vmf, this may be  subject to change

* A compile tool is slowly being made via Python 3, functionality can be seen for it at https://github.com/KabusIblis/map-toolkit

* Temporarily, or if you prefer, you can compile the map using Python1320s map-compiling-toolkit https://github.com/Metastruct/map-compiling-toolkit
  * This requires a lot of manual setup, support is not given for this toolkit.

Projects are used for TODO tracking
