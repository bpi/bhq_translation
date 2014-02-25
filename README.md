bhq_translation
===============

## Introduction
Many exercises can be localized completely by editing the text for your locale; others need tranlated sound stimuli. We can disable selected exercises for your locale until they have been fully localized.

### Text translation
To translate text, go to our [text database](https://tra:vame4uFA@tra.cloudant.com/rfm_loc/_design/rfm_loc/index.html#) and select your locale.

Text is arranged in bins by content area. Once you've edited and saved some text you can view it live on our test server:

	https://bhq-play-test.herokuapp.com/default/start?locale={YOUR_LOCALE}&override_locale={YOUR_LOCALE}
	
Note that your locale appears twice in the url, once to specify the (pre-built) localized version and again to load the fresh text you've edited.

### Sounds translation
We would like you work through the exercises that require sound recordings in a series of steps starting off with a relatively easy stimulus set. More information is below. 

## Exercises - text translation only

* divided_attention (Divided Attention)
* mot (Target Tracker)
* ufov (Double Decision)
* tapat (TAPAT)
* visual_search (Hawk Eye)
* vis_sweeps (Visual Sweeps)
* aud_sweeps (Sound Sweeps)
* eye_movement (Eye for Detail)
* visual_scan (Scene Crasher)
* face_match (Recognition)
* emotion_match (Face to Face)
* nback_card (Card Shark)
* digit_span (Juggle Factor)
* face_story (Face Facts) -- in addition we require translation of [these files](face_story).
* rotation (Right Turn)
* spatial_orientation (Mental Map)
* optic_flow (Optic Flow)


## Exercises - text and sound stimuli
We would like you to work through these exercises in a series of steps. Only when one step is fully completed should you move to the next step. A step is completed when the exercise it is ready to go live on our production server. 

###Step 1 
The sounds for the first two exercises (Mixed Signals and Auditory Ace) should be translated first. These are a relatively easy set of stimuli and help us establish that the recording methods meet our requirements. 
* dual_modes (Mixed Signals). 
* nback_card_auditory (Auditory Ace).  

The recording instructions and the stimuli to record are [here](easy_translations.md).  

###Step 2 
When the above two exercises are completed we recommend working on True North. This is another relatively easy stimulus set.  
* conveyance (True North). Please translate and record this [stimulus set](conveyance.md).

###Step 3
Next we recommend working on Memory Grid and Syllable Stacks. Both of these exercises use the same stimulus set. Stimulus planning and generation is required in collaboration with Posit Science. Click [here](misrp.md) for more information.
* aud_spatial_match (Memory Grid)
* syl_ordering (Syllable Stacks)

###Step 4 
Next is Fine Tuning. Stimulus planning and generation is required in collaboration with Posit Science. 
* aud_sound_discrimination (Fine Tuning). Click [here](tua.md) for more information.

###Step 5
Next is In the Know. Stimulus planning and generation is required in collaboration with Posit Science.
*  aud_chatter (In the Know). Click [here](chatter.md) for more information.

###Step 6
The final exercise is To-Do List Training. Stimulus planning and generation is required in collaboration with Posit Science.
* aud_instr_seq (To-Do List Training). Click [here](lad.m) for more information.

## Beta exercises  - do not translate yet
*  categorization (Categorization)
*  beep_seeker (Beep Seeker)
*  gabor_memory (name-gabor_memory)
*  visual_ordering (Fribble Factor)
*  visual_spatial_match (Fribbler)
*  lucky_seven (name-lucky_seven)
*  rule_change (Rule Change)
*  task_switch (name-task_switch)
*  digit_span_auditory (Auditory Juggle Factor)
*  dualnback_card (Dual N-Back)














