MSTS Superliner II Coach Interior
Version 1.0: January 4, 2012
---------------------------------

This is a custom, highly detailed interior model designed for Superliner II coach and coach-baggage cars. It will fit the default Genesis Superliner wagon that comes with MSTS, as well as any repaints of that model.

The original source files (model in obj format, tga textures) are included in case anyone wishes to modify the model.

Sorry, no fancy auto-installer. Scroll down to the Installation section for installation instructions.

Changelog
---------

1.0:

 * Initial release

Compatibility
-------------

I suggest installing the latest version of MSTS-Bin so you can switch between different cars in passenger view (#5). But this addon does not require it.

As far as I know, the model will fit perfectly with the following cars:

 * Default MSTS Genesis Superliner
 
 * Superliner II coach #34122 by Buzz Benz
   File name "s2coaa41.zip" on the Trainsim.com file library
 
 * Superliner I coach-baggage #31039 by Buzz Benz
   File name "s1cbga41.zip" on the Trainsim.com file library

Installation
------------

1. Copy all the files in this folder to the folder of the Superliner wagon you wish to use this model in.
   For example, for the default Superliner, I would copy all the files to MSTS/TRAINS/TRAINSET/Genesis.
   
2. Open that wagon's *.wag file.
   For the default Superliner, I would open MSTS/TRAINS/TRAINSET/Genesis/superliner.wag.
   
3. Scroll down to the bottom and add the following code **BEFORE** the last bracket ")":
  	
	Inside (
		PassengerCabinFile ( "supcoachint.s" )
		PassengerCabinHeadPos ( 0.982 3.806 -7.859 )
		StartDirection ( 0 0 0 )
		RotationLimit ( 180 180 0 )
		Sound ( "GenPassWagModern.sms" )
	)

   For the default Superliner, I would modify superliner.wag so that the last 10 lines look like this (**NOTE THE ENDING BRACKET!**):

  	Sound (	"GenPassWagModern.sms" )

	Inside (
		PassengerCabinFile ( "supcoachint.s" )
		PassengerCabinHeadPos ( 0.982 3.806 -7.859 )
		StartDirection ( 0 0 0 )
		RotationLimit ( 180 180 0 )
		Sound ( "GenPassWagModern.sms" )
	)
)

Known issues
------------
 
 * The rear end of the car in front might punch into the forward vestibule in some cases.

License/Legal
-------------

This work is licensed under a Creative Commons Attribution-NonCommercial 3.0 Unported License.
http://creativecommons.org/licenses/by-nc/3.0/

In other words, you are allowed to redistribute/modify/do whatever you want with this model as long as you attribute me in your documents and do NOT use the model for commercial purposes (i.e. including it in payware).

Contact
-------

Interior model created by Ryan Young.
Email (IMPORTANT- READ THE LINE BELOW THIS!): <ryan.ry.old@yahoo.com>
Replace "old" with "young" and "yahoo" with "gmail".
(Sorry for the anti-spam measures, I'm paranoid about junk mail :)
