This utility hides or un-hides partitions on removable media by re-writing the boot signature from the standard 55-AA to 55-AB.

The purpose is to prevent Wii U from seeing the attached drive and asking you to format it on start up.  While the partition is hidden, only supported applications are able to see the drive - the drive will be hidden to the PC as well.

Currently the utility is supported on the vWii (or indeed Wii if you need it) by open-wiiflow-mod (thanks to Fix94!).  More applications to be added, watch this space.

I realise I should have tackled this with C++ instead of C# and .Net and I apologise to Mac and Linux users.  I'll put it on my to do list to port it to C++ multi-platform.... unless someone else in the community has the time :)

The source is in Visual Studio 2010 with .Net 3.5.

You will need Windows XP and higher with .Net 3.5 to use this app.  It also needs to run with elevated permissions (run as administrator) and should invoke elevated access request automatically when you run it.

I have tested this utility with standard 512b sector drives.  I have **not** tested it or written it for newer drives with 4kb sectors.  It may work on drives that emulate 512b sectors but since I don't have one, I have been unable to test it as yet.  I'll update the application as soon as I get a drive to test it on.  When in doubt, always assume the worst - data loss - and make sure you have a backup.

**NOTE**
Use this utility at YOUR OWN RISK.  It comes with no warranty whatsoever.
Low level writes to your drives are dangerous if you don't know what you are doing!
Don't use this utility if you are not prepared to lose data.
Backup your drive before using this utility on it.
Lastly, if you don't understand what this utility is for then you don't likely need it.

Check the Wiki for more info.