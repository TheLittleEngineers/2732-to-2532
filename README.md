# 2732 <--> 2532 adapter
The following text is from the repository originally uploaded by Ricardo Quesada at this url: https://github.com/ricardoquesada/2732-to-2532

_Original taken from here: [2532 to 2732 adaptor](http://www.neoncluster.com/aamber_pegasus/Blog/Entries/2010/5/5_2532_to_2732_and_visa_versa_adaptor..html)_

This product is intended to allow a 2732 EPROM to be placed into  a 2532 EPROM socket or a 2532 EPROM to  be  placed  into a 2732 EPROM socket. Fitting I.C. pins for IC1 and a socket for IC2 allows a 2732 to be plugged into a 2532 socket, whilst fitting I.C. pins for IC2 and a socket for IC1 allows a 2532 to be plugged  into a 2732 socket.

The 2732 has an output enable signal in addition to the chip enable signal. In most cases, the output enable signal can simply be connected to ground. However, it may sometimes be desirable to connect the ouput enable signal to the chip enable signal.
Jumpers JP1 and JP2 allow these settings.
* If JP1 is fitted, then the ouput enable will be connected to the chip enable.
* If JP2 is  fitted,  then  the  ouput enable will be connected to  GND.
JP1  and  JP2  should __NEVER__  be fitted at the same time - one  or the other, but not both. In  most cases, fitting JP2 will  suffice.

All of  GIMEchip.com's designs are created for the benefit of the vintage computing community as a whole. Although we copyright all of our works and retain all rights to them,  we also  don't mind  sharing. If you wish to produce and distribute this product, please contact us at: * sales@gimechip.com

In most cases, permissions will be granted Royalty Free. I said we like to share, didn't I?

If you would like to include this product as part of your  website, feel free to do so,  as  long  as all documentation remains intact.
We do ask that you inform us that you have included  this  file  on your site so our ego's may get  a bit larger :-)

Enjoy - John Eric & John Robert (J.R.), Son & Father - This is the end of text from the original repository.

The following text is added for this new version:

I have updated the GCC-0001.0 (v1.0) product described above to GCC-0001.1 (v1.1) and placed a repository for the 1.1 version here: https://github.com/TheLittleEngineers/2732-tofrom-2532

The original version was created by my nephew and his father (my brother) with minor input from me. The 1.1 version made minor changes, specifically a cleaner silkscreen, mitered tracks and a CC BY-SA 4.0 License. I did not fork Ricardo Quesadas repository for that minor update, but rather simply made a new repository.

I have now updated GCC-0001.1 (v1.1) to GCC-0001.2 (v1.2), once again making only minor changes. These changes are to the EAGLE library to improve appearance. I decided, at this time, to fork Ricardo Quesadas repository for this version so that more people might find it and have access to the CC BY-SA 4.0 Licensed version.

Enjoy - Robert "The R.A.T." Allen Turner, 02 June 2019.

This repository resides at: https://github.com/TheLittleEngineers/2732-to-2532

There is an OSHPark Project Page at this url: https://oshpark.com/shared_projects/AEIenkvH

The logos, names and other material relating to The Little Engineers, TheLittleEngineers.org and GIMEchip.com are the sole property of Robert Allen Turner with All Rights Reserved. The rights to the GIMEchip.com domain and products were acquired by the author on 25 December 2018. Merry Happy Christmas! Please note that the author is unable to answer any inquiries, including those of support or otherwise, in relation to GIMEchip.com prior to his acquisition of same on 25 December 2018. http://www.TheLittleEngineers.org

Please note: This is derived from an original design by "Little" John Eric and/or his father "Big" John Robert (J.R.) by "Uncle" Robert Allen. It should be thoroughly scrutinized and verified prior to actual use of any kind. DISCLAIMER: The following article is provided for informational purposes only. Any attempt to modify your computer without the proper skills to do so may void your computer. Any attempt to modify your computer without unplugging it first may void you. This Information is provided "as-is" with no guarantee of fitness for any purpose, either explicit or implied. We disclaim any and all responsibility for losses incurred through the use of this information. By using this information, you are deemed to have accepted these conditions of use, and you agree NOT to sue us. CLARIFICATION: The above disclaimer states as plainly as possible that if you decide to make use of any of the information contained within this document that you do so at your own risk. Designing hardware for the CoCo (ColorComputer) and other vintage hardware is a hobby of ours and is not motivated by any desire of profits. As this is a not for profit venture, obviously we can't afford not to disclaim the use of this information.

PLEASE NOTE: THIS VERSION HAS NOT YET BEEN TESTED.
