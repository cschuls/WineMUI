# WineMUI
Added rudimentary support to Wine to allow access to multi-language resource objects.

Having performed additional testing and receiving valuable feedback from the Wine community, I was able to utilize standard API's to acquire the locale code and to remove the need for resource handle range testing.  This has made the code changes more compact but at the same time providing comprehensive retrieval of resources both from the multi-language support file for language specific resources and from the executable file for language neutral resources.

FYI, this enhancement was not accepted as a patch by the Wine reviewers, so I will just continue to periodically update the loader.c file as new versions of Wine are released.

The enhancements have again been applied.  Starting out, the initial development version and stable version will be the same.  Also, if the previous stable version of the code is needed, they have been placed into a zip file for access.
