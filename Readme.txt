
Copyright 2011 by Alexander Balasch http://coolrobotprojects.blogspot.co.at/

This program is free software: you can redistribute it and/or modify
it under the terms of the GNU General Public License as published by
the Free Software Foundation, either version 3 of the License, or
(at your option) any later version.

This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU General Public License for more details.

You should have received a copy of the GNU General Public License
along with this program.  If not, see <http://www.gnu.org/licenses/>

this project has been inspired by:

http://pleasantsoftware.com/developer/3d/spherebot/

///////////////////////////////////////////////////////////////////////////////////

HOW TO:

1.) Upload the Arduino sketch.

	(I have added an additional multiplicator to the y-Step calculation to 
	match my spherebot to the unicorn-script coordinates. You will maybe have to
	do the same adjustment for your Spherebot)

	(You will also have to redefine your pins accordingly to your electronics design)

2.) Start the Spherebot-UI.exe and connect to your Arduino

Warning for custom Firmwares: 	The send file function will only work if the arduino answers each sent command with a message 
				that contains "ok:" so that the next command is sent.