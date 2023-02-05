
---MSTS GE SAFE2 CABS V1.2----

Hi, thank you for downloading my GE SAFE2 cabs Version 1.2.

I hope you will enjoy it.

Update for GE-SAFE2-CAB; Version 1.2 includes better graphics and night views.
This is a photorealistic cab for the GE Engines that uses a Safety cab with LCD monitors like the DASH-9, AC4400CW, AC6600CW, ES44DC and ES44AC.
Have a wide vision angle for a better realistic experience like the real life. 
The DASH-8, DASH-9, AC4400CW, AC6600CW, ES44DC and ES44AC have a wide nose and a large "North American Safety Cab”, allowing more crew members to ride comfortably inside of the locomotive than the older standard cab designs.

Original Read me instructions by Dwight Mitchell.
Controls originally by MLT (Freeware KHP route Demo) (www.mapleleaftracks.com).
LCD display monitors by Phil Gosney.
Right view original from Microsoft/Kuju.
Left view photo by Mike Bates.
Front photo originally by Dave Toussaint.                                                       

by Charlie Sibaja

-----------------------------------------------------------------------------------------------------

TO INSTALL:

1.	 First and most important BACKUP and I do mean BACKUP the entire folder of the engine that you want to use this cab in. If you don’t do this first SHAME ON YOU!!


2.     Unzip this file to the drive where MSTS is located (normally drive C:). This will create the directory

        x:\Program Files\Microsoft Games\Train Simulator\TRAINS\TRAINSET\Common.Cab\GE-SAFE2-CAB

        where “x:\”   is the drive where MSTS is located.


***(If you have the first GE-SAFE2-CAB installed, Answer "YES TO ALL" to overwrite any files when asked. You don't need replace the old .cvf files on your Cabview folders; the V1.2 uses the same .cvf files)***


3.	 In the sub-folder “ALIAS” of this file are four cvf files:

             GEsafe2-OLCD.cvf---------------Cab for GE locos with Old LCD monitors (Dash-9, AC4400).
             GEsafe2-OLCD-RW.cvf------------Cab for GE locos with Old LCD monitors and round side windows (Dash-9, AC4400).
             GEsafe2-NLCD.cvf---------------Cab for GE locos with New LCD monitors (AC6600, ES44DC, ES44AC).
             GEsafe2-NLCD-RW.cvf------------Cab for GE locos with New LCD monitors and round side windows (AC6600, ES44DC, ES44AC).


4.	Choose one of the files in step 3 and copy it into the cabview folder of the engine you want to use this cabview in. You have the option of deleting all other files in this folder if you wish.  If your engine does not have a Cabview folder then create one and then copy the file(s) into this folder.

5.	Open up the *.eng file with an ASCII text editor such as Notepad or Context. Look for the following line (*)

      NumWheels ( 1 )
	MaxTemperature ( 120 )
	MaxOilPressure ( 90 )
     (*)CabView ( gp38.cvf )
	MaxDieselLevel ( 3600gal )
	DieselUsedPerHourAtMaxPower ( 60gal )
	DieselUsedPerHourAtIdle ( 10gal )

       Replace the wording gp38.cvf with the name of the file you used in step 3 ( GEsafef2-OLCD.cvf ) or ( GEsafef2-NLCD-RW.cvf ). 
      
	
      NOTE: Your CabView line might be some other engine other than gp38.cvf.

6.	Since this cab uses the combined control stand Look and add for the following lines(*).
 
       Brake_Dynamic ( 0 1 0.025 0 
                NumNotches ( 1
                    Notch ( 0       1 Dummy )
                )
            )
         (*)Combined_Control ( 0 1 0.5 0.5 throttle dynamic )
	    DirControl ( -1 0 1 1 )
            BellToggle( 0 1 0 )
            AWS ( 0 1 0 )

	
SAVE THIS FILE!



----Enjoy your ride-----

-----------------------------------------------------------------------------------------------------

If you have ANY problems what-so-ever please email me at charliesibajamsts@yahoo.com, email me saying nice job. I just want to know how you all like it.

Thanks,

CHARLIE SIBAJA.


