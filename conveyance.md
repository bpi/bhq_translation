# True North (conveyance)
We need translated dictionary entries and matching recordings.

## Dictionary translation
We need a translated entry for each value in the dictionary. You can also update the key names but that is optional. Note that sounds recording file names should match the key names (see Sound Recordings section below). 

Format:
```"key":"value"```

The key is the text before the colon. The value is the text after the colon.


#### Instructions
```   
   "first":"first",
   "trans":". then, ",
   "trans2":". after that",
   "take_the":"Take the",
   "train":"train",
   "to":"to",
  ```  
  
#### Directions
  ```   
   "w":"westbound",
   "s":"southbound",
   "n":"northbound",
   "e":"eastbound",
  ```  
 
#### Confusable stops. 
These keys refer to stops that sounds similar and are easy to confuse. Example: P Street, D Street, G Street in English. You should create values in the dictiornary above sound similar in the tranlsated language. 
```
   "b_st":"B St.",
   "c_st":"C St.",
   "e_st":"E St.",
   "d_st":"D St.",
   "g_st":"G St.",
   "p_st":"P St.",
   "t_st":"T St.",
   "v_st":"V St.",
   "z_st":"Z St.",
   
```

#### Landmarks
  ```   
   "fisher_lib":"Fisher Library",
   "sixth_ave":"6th Ave.",
   "watermoor_hill":"Watermoor Hill",
   "easthollow_rd":"Easthollow Rd.",
   "corwin_garden":"Corwin Garden",
   "marina_ter":"Marina Terrace",
   "lochmill_st":"Lochmill St.",
   "atkinson_ave":"Atkinson Ave.",
   "millbury_st":"Millbury St.",
   "icebutter_c":"Icebutter Circle",
   "trans3":". next",
   "southsea_plz":"Southsea Plaza",
   "grand_central":"Grand Central Terminal",
   "n_logan_hosp":"N. Logan Hospital",
   "arapaho_st":"Arapaho St.",
   "clear_crk":"Clear Creek",
   "wellwood_pk":"Wellwood Park",
   "church_st":"Church St.",
   "southview_rd":"Southview Rd.",
   "fairmont_plz":"Fairmont Plaza",
   "bridgelake_blvd":"Bridgelake Blvd.",
   "clevedon_rd":"Clevedon Rd.",
   "capitol_sq":"Capitol Square",
   "melvindale":"Melvindale",
   "kite_hill":"Kite Hill",
   "bethlehem_hosp":"Bethlehem Hosp.",
   "central_lib":"Central Library",
   "hollinwood_bay":"Hollinwood Bay",
   "sanctuary_pk":"Sanctuary Park",
   "heatherton_rd":"Heatherton Rd."
```
## Sound recordings
  A recording should be made for each transated value. The sound file name should match the key.
  E.g., "fisher_lib" must have a wav file called fisher_lib.wav.
  Further information on recording is [here](recording_instr.md).
