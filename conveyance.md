# conveyance (True North)
We need translated dictionary entries and matching recordings.

## Dictionary translation
Format:
```"key":"value"```

The key is the text before the colon. The value is the text after the colon.

Each value must be translated. You can also update the key names but you must also update the entries in the confusable stop and landmark sections below.

```
  "dict":{
   "first":"first",
   "fisher_lib":"Fisher Library",
   "sixth_ave":"6th Ave.",
   "s":"southbound",
   "n":"northbound",
   "watermoor_hill":"Watermoor Hill",
   "easthollow_rd":"Easthollow Rd.",
   "corwin_garden":"Corwin Garden",
   "marina_ter":"Marina Terrace",
   "lochmill_st":"Lochmill St.",
   "trans":". then, ",
   "atkinson_ave":"Atkinson Ave.",
   "z_st":"Z St.",
   "millbury_st":"Millbury St.",
   "icebutter_c":"Icebutter Circle",
   "trans3":". next",
   "southsea_plz":"Southsea Plaza",
   "v_st":"V St.",
   "train":"train",
   "grand_central":"Grand Central Terminal",
   "t_st":"T St.",
   "n_logan_hosp":"N. Logan Hospital",
   "arapaho_st":"Arapaho St.",
   "clear_crk":"Clear Creek",
   "c_st":"C St.",
   "p_st":"P St.",
   "d_st":"D St.",
   "e":"eastbound",
   "wellwood_pk":"Wellwood Park",
   "church_st":"Church St.",
   "southview_rd":"Southview Rd.",
   "fairmont_plz":"Fairmont Plaza",
   "take_the":"Take the",
   "bridgelake_blvd":"Bridgelake Blvd.",
   "clevedon_rd":"Clevedon Rd.",
   "capitol_sq":"Capitol Square",
   "b_st":"B St.",
   "trans2":". after that",
   "melvindale":"Melvindale",
   "kite_hill":"Kite Hill",
   "e_st":"E St.",
   "bethlehem_hosp":"Bethlehem Hosp.",
   "central_lib":"Central Library",
   "to":"to",
   "w":"westbound",
   "g_st":"G St.",
   "hollinwood_bay":"Hollinwood Bay",
   "sanctuary_pk":"Sanctuary Park",
   "heatherton_rd":"Heatherton Rd."
  },
```

### Confusable stop keys
The following keys are confusable stops. The values for these keys should all sound similar. The keys should match the corresponding key names in the dictionary.
```
"confusable_stops":[
 "b_st",
 "c_st",
 "d_st",
 "e_st",
 "g_st",
 "p_st",
 "t_st",
 "v_st",
 "z_st"
],
```
### Landmark keys
The keys should match the corresponding key names in the dictionary.

```
  "landmarks":[
   "wellwood_pk",
   "southsea_plz",
   "lochmill_st",
   "icebutter_c",
   "watermoor_hill",
   "marina_ter",
   "bridgelake_blvd",
   "easthollow_rd",
   "arapaho_st",
   "n_logan_hosp",
   "hollinwood_bay",
   "clear_crk",
   "southview_rd",
   "melvindale",
   "millbury_st",
   "corwin_garden",
   "kite_hill",
   "fairmont_plz",
   "central_lib",
   "sixth_ave",
   "sanctuary_pk",
   "church_st",
   "atkinson_ave",
   "clevedon_rd",
   "bethlehem_hosp",
   "heatherton_rd",
   "capitol_sq",
   "fisher_lib"
  ]
```
## Sound recordings
  A recording should be made for each transated value. The sound file name should match the key.
  E.g., "fisher_lib" must have a wav file called fisher_lib.wav.
  Further information on recording is [here] (recording_instr.md).
