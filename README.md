# UVic2.9_04
Andreas Schmittner (aschmitt@coas.oregonstate.edu) 
This is my current working version (updates/04) of the UVic model. In order to use it you'll need to copy it in your base code updates directory (e.g. /usr/local/models/UVic_ESCM/2.9/updates/04) 
It is a merge of Juan Muglia's iron model additions to MOBI and Karen Kvale's calcium carbonate code. I have restructured the code to remove hard-wired indices for the tracer numbers and to make MOBI flexible such that individual options can be switched on and off independently. E.g. a basic, only phosphate limited, version of the NPZD model can be used. Iron can be added to that and/or the nitrogen cycle. The carbon cycle can be added to either version and carbon and nitrogen isotopes can be switched on and off.
Note that this is a working versin and has some known (and presumably other unknown) issues. E.g. c13 distributions are wrong.
I'll also upload as a separate repository a local directory that works with this code. 
 
