# Change-Default-Khmer-System-Font-on-Windows-All-Versions
This is just a simple fix for Khmer fonts.

Khmer Fonts that come with Windows are:
1. DaunPenh (small size)
2. MoolBoran (small size)
3. PhnomPenh OT (small size)(for some PC, you might install it by yourself)
4. Khmer UI (ugly font)
5. Khmer UI Bold (ugly font)

Here what I've change into:
1. DaunPenh -> Khmer OS Battambang
2. MoolBoran -> Khmer OS Moul Light
3. PhnomPenh OT -> Khmer OS Battambang
4. Khmer UI -> Hanuman UI
5. Khmer UI Bold -> Hanuman UI Bold

The Problem with default Khmer system fonts:
  Microsoft apps (and some other apps) use Khmer UI fonts for interface. It doesn't have any problem, it's just those fonts are a bit ugly to look at. You might see on apps like Microsoft Edge...
  Some other apps use fonts MoolBoran and DaunPenh/PhnomPenh OT for interface. The problem is those fonts size are too small, you might have problem seeing it clearly. And it also ugly. You might see this case on Firefox, Telegram...
  
How to Change Default Khmer System Fonts:
1. Download this project as Zip and Extract it on your PC.
2. Go to folder "ChangeDefaultKhmerFont"
3. Select all fonts then right click and choose "Install for All Users"
4. Right-click on "ChangeDefaultKhmeFont.reg" and select "Merge"
5. Restart your PC and DONE!
Note: If you have some issue with Khmer font in Microsoft Office apps or other Microsft Apps that display Khmer font as SQUAREs (Cuz of Khmer UI fonts), you might go to folder "ChangeDefaultKhmerFont-NoUI" instead and follow there form step 3.

How to revert back to Default Khmer System Fonts:
1. (You can skip it if you already download the project) Download this project as Zip and Extract it on your PC.
2. Go to folder "RestoreDefaultKhmerFont"
3. (You can skip this step) Select all fonts then right click and choose "Install for All Users"
4. Right-click on "RestoreDefaultKhmeFont.reg" and select "Merge"
5. Restart your PC and DONE!

If you want to use other fonts than Khmer OS, you may edit "ChangeDefaultKhmeFont.reg" reg file as you like. But before that, make sure you have those fonts install beforehand.

***Note: Not working for windows version 1903, 1909
