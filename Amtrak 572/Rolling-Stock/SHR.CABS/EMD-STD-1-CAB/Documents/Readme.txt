
---MSTS SHR EMD-STD-1 CAB----

Hi, thank you for downloading my EMD-STD-1 High Resolution Version cab (1024X768pixels).

I hope you will enjoy it.

----------------------------------------------------------------------------------------------------

Introduction:

This is a photorealistic cab for the EMD Engines like the GP9, GP10, GP11, GP15, GP18, GP20, GP30, GP35, GP38, GP40, SD9, SD24, SD35, SD40, SD45 and many others, not the dash-2. 
Includes High Resolution graphics, night views and diverse versions for:

PACK.1
ARR, ATSF, BN, BNSF and BO. 

PACK-2
Chessie, CN, CP, CNW, CR, CRR, CSX, DRGW, FNM, FXE, GN, GTW, IC, ICG, LN, KCS, MILW, MKT, MP and MRL.

PACK-3
NS, NW, RI, SBD, SOO, SOU, SP, SPSF, UP and USAX.

It has a wide vision angle for a better realistic experience like the real life, 195 diferents modes of cabviews.

----------------------------------------------------------------------------------------------------

Credits:

All ace are my own creations except for the Right and left view original from TrainArtisan (reworked for me) and some controls and display indicators.
Front Photo by James Gardiner.
Original Read me instructions by Dwight Mitchell.
Combined control original concept by Dwight Mitchell and Ken Powers.
Cabview by Charlie Sibaja.

-----------------------------------------------------------------------------------------------------

TO INSTALL:

1.      Always backup all files before you edit them!

2.     Unzip this file to the drive where MSTS is located (normally drive C:). This will create the directory
       x:\Program Files\Microsoft Games\Train Simulator\TRAINS\TRAINSET\SHR.CABS\EMD-STD-1-CAB

       Where x:\ is the drive where MSTS is located

----------------------------------------------------------------------------------    

3.	In the sub-folder “ALIAS” of this file are 183 cvf files

   EMD  -  GP10    ND   -   BNSF  -  H1   -  AS   .cvf
    /       /      /         /       /       /     /
   /       /      /         /       /       /     /
Builder   /      /         /       /       /     /
         /      /         /       /       /    File extencion
 Loco Model    /         /       /       / 
              /         /       /       /
  Loco Caracteristic   /       /       / 
                      /       /       / 
                Road Name    /       /
                            /       / 
               Road Name Variant   /
                                  /
                             Speedometer

----------------------------------------------------------------------------------    

4.	Choose one of the files in step 3 and copy it into the cabview folder of the engine you want to use this cabview in. If your engine does not have a Cabview folder then create one and then copy the file into this folder.


5.	Now the tricky part. Open your eng file with a Unicode text editor (Wordpad for example) and search for CabView (*):

      NumWheels ( 1 )
	MaxTemperature ( 120 )
	MaxOilPressure ( 90 )
     (*)CabView ( GP38.cvf )          <------Change this line
	MaxDieselLevel ( 3600gal )
	DieselUsedPerHourAtMaxPower ( 60gal )
	DieselUsedPerHourAtIdle ( 10gal )

       Replace the wording GP38.cvf with the name of the file you used in step 3. 
	
6.    Look for the following lines (*): (Skip this step if you are using a Non-Dynamic brake engine )
	
            Brake_Dynamic ( 0 1 0.025 0 
                NumNotches ( 1
                    Notch ( 0       1 Dummy )
                )
            )
         (*)Combined_Control ( 0 1 0.5 0.5 throttle dynamic )      <------Delete this line
	    DirControl ( -1 0 1 1 )
            BellToggle( 0 1 0 )
            AWS ( 0 1 0 )

     Add the line that starts with: Combined_Control ( 0 1 0.5 0.5 throttle dynamic )

SAVE THIS FILE!



----Enjoy your ride-----

-----------------------------------------------------------------------------------------------------

This cab is done as a freeware, not for sale.

If you have ANY problems what-so-ever please email me at charliesibajamsts@yahoo.com, email me saying nice job. I just want to know how you all like it.

Thanks,

CHARLIE SIBAJA.


