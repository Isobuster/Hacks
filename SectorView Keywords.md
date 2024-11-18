<h1>SectorView keywords</h1>

SectorView supports keywords or commands: "**start**", "**first**", "**end**", "**last**" and "**mid**" (alternatively followed by a + or - value)

To understand you must know that SectorView keeps track of the object it was triggered from.

For instance, if you `right mouse click` the top most icon in the left pane, and choose "`SectorView`", SectorView is internally associated with the entire disc/disk.

Alternatively, if you `right mouse click` a file icon, and choose "`SectorView`", the object SectorView is internally associated with is that file.

This is true for any type object IsoBuster displays and that you can select "`SectorView`" on.

Why ? Because then it is easy to navigate inside the range of that object.
If you type "**start**" or "**first**" in the top address-navigation bar, SectorView will jump to the first address in the object's range.  In other words the first LBA of the disk in first example, or the fist LBA of the file in second example.

Similarly, if you type "**end**" or "**last**", IsoBuster will jump to the last block address of the selected object.

"**mid**" puts your roughly in the middle of the range

These keywords can also be combined with a **+** or **-** value.  For instance:

`first+2` sends you to relative block 2 inside the range of the selected object (so if the object is located at address 10, you'll end up with block 12)

`last-1` sends you to the block just before the last block of the selected object and so on ..
