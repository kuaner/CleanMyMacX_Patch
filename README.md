## CleanMyMac X Patched

I love this version of CleanMyMac, especially its beautiful UI.
Sadly, this X beta could only be used for a very limited time. So a patch is on the way...

This is a very simple patch for CMM X beta. 

Procedures:

1. -[_TtC10CleanMyMac23BetaApplicationDelegate applicationDidFinishLaunching]

2. sub_1000d89d0 (sub function inside the delegate method)

3. 00000001000d8a2b         'testb      $0x1, %al' (A801)

4. Modify the last instruction to 'cmpb $0x1, %al'(3C01) by using hopper's hex editor.

Try to open your obsolete beta version again :)


