#Real Way To Speed Up Android Studio

If you are using Android Studio on a system having moderate(3 GB), or high RAM, then it is fairly simple to speed up Android Studio.

You just need to increase the heap-size(which I assume is the RAM allocated to the running projects, yada yada) in the Android Studio.

First enable visualization of the RAM allocated and the RAM used:-
Android Studio --> File --> Settings --> Appearance & Behavior --> Appearance --> Show Memory Indicator .
You will be able to see the indicator in the lowermost right corner of the screen, beside the smiley icons.

Next go to Help --> Edit Custom VM Options -->  Then Inside The VM Options Editor Write This --> -XmxYour_Required_RAM_Size_In_GB_Or_MB .
E.g., -Xmx2g , here g stands for GB, or -Xmx2000m, here m stands for MB, both are nearly the same thing.

Restart Android Studio. Done. :)

 
