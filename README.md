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

Recording instructions are [here](recording_instr.md).

## Exercises using text only

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

## Exercises requiring sound stimuli 
In addition to the text tranlations, the following exercises require sound stimuli. We would like you to work through these exercises in a series of steps. Only when one step is fully completed should you move to the next step. A step is completed when the exercise it is ready to go live on our production server. 

###Exercises with easy stimulus sets
####Step 1 
The sounds for the first two exercises (Mixed Signals and Auditory Ace) should be translated first. These are a relatively easy set of stimuli and help us establish that the recording methods meet our requirements. 
* dual_modes (Mixed Signals). 
* nback_card_auditory (Auditory Ace).  

Please tranlate and record [this](easy_translations.md) stimulus set.  

####Step 2 
When the previous step is completed you can start workig on True North. This is another relatively easy stimulus set.  
* conveyance (True North). Please translate and record [this] (conveyance.md) stimulus set.

###Exercises with complex stimulus sets
Stimulus planning and generation is required for exercises with complex sound stimulis. Please contact us when you are ready to proceed with the next Step so that we can start working together to produce a stimulus list. 

Note: Due to the complexity of the stimuli in aud_instr_seq (To-Do List Training) we do not plan to offer this exercise for translation. However, the conveyance (True North) exercise is a similar task. 

####Step 3
Both of these exercises use the same stimulus set.
* aud_spatial_match (Memory Grid)
* syl_ordering (Syllable Stacks)
Once the previous step has been completed you can contact us when you are ready to start stimulus planning and generation. 


####Step 4 
* aud_sound_discrimination (Fine Tuning). 
Once the previous step has been completed you can contact us when you are ready to start stimulus planning and generation. 

####Step 5
*  aud_chatter (In the Know). 
Once the previous step has been completed you can contact us when you are ready to start stimulus planning and generation. 

## Beta exercises  - do not translate
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














