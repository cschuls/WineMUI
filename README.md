# WineMUI
Add rudimentary support to Wine to allow access to multi-language resource objects.

Note that the code enhancements rely on testing for a range of resource module values and resource handle values.  For your system, you may need to debug the FindResourceExW function to see what ranges of module values are generated on your system and adjust the test range accordingly.  Alternatively, if the program (or programs) that you want to run with this rudimentary MUI support will function without the requirement of language neutral resources stored in the executable file, you may omit the resource range tests and just execute the GetMUI function within the LoadResource function.
