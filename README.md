# HOTAS Warthog profile for DCS F/A-18C Hornet
T.A.R.G.E.T. profile for the Thrustmaster HOTAS Warthog and DCS World FA-18C Hornet

This profile was inspired by the great [F-18 Profile][noid_f18_profile_url] created by [NOiD][noid_profile_url]. You should check out this profile if you like having more functions bound to your HOTAS by using modifier buttons.

## Goals

- __Reduce cognitive load__: Remembering stuff is hard, especially if you don't have time to play a lot and/or 
  regularly and it's not a good thing when you have to remember your key mapping in combat. This problem is 
  aggravated when there are a lot of multi-assignments with modifiers.
  
  This profile aims to reduce the use of modifiers especially on the stick and throttle. There will be some but they will be mostly 
  on the throttle instrument panel which should only contain non-critical stuff.

- __Minimal configuration__: The profile is designed to work with DX buttons so they can be configured within DCS and .lua.diff files can be loaded which makes the configuration really simple.

  Hopefully at some point the profile is completely installed hands-off using a install wizard.
  
- __Relation to real life__: The US Air Force and the US Navy have put a lot of time and thought in designing their 
  HOTAS and "Button Mapping" so I will definiatley try and take adavantage of that.

  The emphasis is on "try" though since the differences in buttons are big enough, e.g. what would be the CMS switch in the F-16 (same layout as the warthog) would be the weapon selection in the F-18. But on the warthog it also has a button press ... so it is perfeclty suited for the sensor switch which now has a depress ... and I thought this would be the easiest point on the list.
  
- __F-16__: I started out years ago in Falcon 4 and spent a lot of time in the (virtual) F-16 cockpit so the control scheme is somhow
  still pretty much ingrained into my flying. And since the F-16 teaser Eagle Dynamics put in their awsome 
  [2018 video][dcs_2018_youtube_url] I think it is a good Idea to keep the 2 schemes somewhat related.
  
- __Flexibility__: The plan is to make the profile interchangeable with other modules, either as is or by including different macro
  definitions so the scheme can stay the same between different planes.
  
## Curent State
__Work in Progess__

TODOs (order reflects the priority but is not set in stone):
- [Fix Bugs][issues_bugs]
- Map Remaining Buttons:
  - DMS (Stick)
  - Pinky (Throttle)
  - Boat (Throttle)
- Add mapping description (text)
- Add install instructions with screenshots
- Add mapping description (image)
- [Issues: Enhancements][issues_enhancements]

## Usage

Download the package from the releases, extract to a folder (I put mine in `..\Saved Games\DCS\Layouts\[plane]\`) and run it with T.A.R.G.E.T

As soon as the profile runs you can run DCS. Load the stick.lua.diff and throttle.lua.diff (located in the same folder as the script - make sure you have the correct column selected before loading!) and everything should be good from there.

[noid_f18_profile_url]: https://www.digitalcombatsimulator.com/en/files/3300626/
[noid_profile_url]: https://www.digitalcombatsimulator.com/en/files/?CREATED_BY=NOiD&set_filter=Y
[dcs_2018_youtube_url]: https://www.youtube.com/watch?v=RlmUWO2JL6I
[issues_enhancements]: https://github.com/bastianschwarz/warthog.dcs.f18/labels/enhancement
[issues_bugs]: https://github.com/bastianschwarz/warthog.dcs.f18/labels/bug
