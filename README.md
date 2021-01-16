# WineMUI
Added rudimentary support to Wine to allow access to multi-language resource objects.

Having performed additional testing and receiving valuable feedback from the Wine community, I was able to utilize standard API's to acquire the locale code and to remove the need for resource handle range testing.  This has made the code changes more compact but at the same time providing comprehensive retrieval of resources both from the multi-language support file for language specific resources and from the executable file for language neutral resources.

FYI, this enhancement has been submitted as a patch to "Wine HQ".  I will see if the patch is accepted.
