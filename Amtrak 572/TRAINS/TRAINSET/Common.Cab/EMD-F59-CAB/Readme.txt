
---MSTS EMD F59 CAB----

Hi, thank you for downloading my EMD F59 CAB.

I hope you will enjoy it.

This is a photorealistic cab for the EMD Engine F59PHI and MPI MP36PH. 
Have a wide vision angle for a better realistic experience like the real life. 


Controls originally by MLT (Freeware KHP route Demo) (www.mapleleaftracks.com).
Left view photo by Paul Duda.
Front Photo by HowStuffWorks.
Original Read me instructions by Dwight Mitchell.
                                                      
by Charlie Sibaja

-----------------------------------------------------------------------------------------------------

TO INSTALL:

1.	 First and most important BACKUP and I do mean BACKUP the entire folder of the engine that you want to use this cab in. If you don’t do this first SHAME ON YOU!!


2.     Unzip this file to the drive where MSTS is located (normally drive C:). This will create the directory

        x:\Program Files\Microsoft Games\Train Simulator\TRAINS\TRAINSET\Common.Cab\EMD-F59-CAB

        where “x:\”   is the drive where MSTS is located.

3.	 In the sub-folder “ALIAS” of this file are one cvf files:

            EMD-F59.cvf---------------Normal F59PHI and cab.

4.	Choose one of the files in step 3 and copy it into the cabview folder of the engine you want to use this cabview in. You have the option of deleting all other files in this folder if you wish.  If your engine does not have a Cabview folder then create one and then copy the file(s) into this folder.

5.	Open up the *.eng file with an ASCII text editor such as Notepad or Context. Look for the following line (*)

      NumWheels ( 1 )
	MaxTemperature ( 120 )
	MaxOilPressure ( 90 )
     (*)CabView ( gp38.cvf )
	MaxDieselLevel ( 3600gal )
	DieselUsedPerHourAtMaxPower ( 60gal )
	DieselUsedPerHourAtIdle ( 10gal )

       Replace the wording gp38.cvf with the name of the file you used in step 3 ( EMD-F59.cvf ). 
      
	
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


