    TfxRegFile is a TRegistry like that store informations in binary file,
    not the windows system registry. It has the same basic functions as in
    TRegistry.
    
    This version is a major rewrite version, thus will not compatible with 
    datafile created by TfxRegFile v1.0.
    
    WHAT'S NEW:
      * indexed entry, making searching entry will be faster than before
      * ability to reuse space
      * ability to compact datafile, removing any unused space
      * up to 1,000,000 record (i hope this is enough since we were not 
        talking about full featured database engine, it is a registry file)
    
    This unit use some routines from FastCode Project 
    http://dennishomepage.gugs-cats.dk/FastCodeProject.htm
    
      * FillCharJOH_FPU
      * MoveJOH_IA32
    
    thanks to FastCode people for this great code.
