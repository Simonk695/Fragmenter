Fragmenter
==========

It all started because some of our database servers at work were badly fragmented according to Windows.

"It doesn't matter."  Said the server engineer, before going back to his paper.

I wanted to prove them wrong.

This batch file and the associated files allows the user to fragment a hard disk (or partition) for test purposes.

Yes, you read right.  Fragment a hard disk.  On purpose.

To keep it useable I have limited it to 10GB.  But even so, that's a hard test for any hard disk.

YOU HAVE BEEN WARNED  -  KEEP THE DISK COOL!

It's not a perfect word, but once 'fragmented' you can then record disk transfer speed, input\output (IO) stats snd anything else you may wish to play around with.

You can then defragment the drive \ partition and repeat your tests.

Create a folder called C:\zap and within this a folder called 'Fragment_Test' (C:\zap\Fragment_Test).

Copy all the files to this, then run 'fragmenter.bat' with the drive letter you wish to fragment.

'fragmenter.bat E'

You will be asked to press 'Y' or 'N' to confirm or exit.

Once the disk is full, you will then need to press 'P' to proceed, or 'Q' to quit, to actually fragment the drive.

As for the performance bit?  Copy any appropriately large file across a few times and average the time it takes.

Please do not bother doing this test on an SSD, they don't work the same way a spinning platter does!

Oh!  If you wreck you hard drive, over-write data or set fire to your house.  Don't blame me.

Simonk695 - December 2014.
