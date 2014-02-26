Text database
=============

###Text Translation
* Go to http://text.brainhq.com/txt (please use Chrome or Firefox - this web site does not work with Internet Explorer)
* Log in using your credentials - you should have already received your credentials from us by email. They will look something like login: “jp” and password “ABC123”
* On the left, you will see a set of bar graphs, with blue/red/and green regions. On the right, you will see a pair of buttons labeled “build test” (blue) and “build prod” (red).
* Locate your locale code among the various bars.
* The bar represents the total number of text items (or “keys”) in BrainHQ
    * Blue represents new keys that we have added to BrainHQ since you last translated content. You may not have any blue in your bar.
    * Red represents keys that need to be translated. If we have updated the English text since you last translated, those keys will be marked red, so that you know to check the translation.
    * Orange represents keys that you once translated, and that we have updated the English text again. 
    * Green represents keys that have been translated.
* If you have a blue region in your bar, click on it (do not click on the blue “build test” button yet)
** When the dialog box comes up, click on “clone from en-us to view”. This adds the new keys to your locale’s database.
* If you have a red region in your bar, click in it (do not click on the red “build prod” button yet)
* When the dialog box comes up, click “view and edit”
* You will now see a list of keys that need to be translated
* Click on “edit” next to the key you want to translate
    * You will see a dialog box contained background information (which can not be edited) and at the bottom, a row called “val”.
    * On the left of the “val” row is the English text. On the right, in an edit box, you should translate in English text into your language.
    * Click on “submit” to save your translation.
* After you have completed the translations, click the blue “build test” button. This incorporates your translations into BrainHQ running on a test server.
    * It takes ~15 minutes for the test server to build. You will get an email acknowledging that the test server has built. If you do not get the email (please check your spam folder), please let us know right away - either there is a problem with the build process (which is unlikely, but possible), we have the wrong email address for you (which we can fix). Once built you can view it live on our test server:
	https://bhq-play-test.herokuapp.com/default/start?chlocale={YOUR_LOCALE}
    * After you receive the confirmation email, you can view BrainHQ on your test server at [XX]
* After you have confirmed the translation, click the red “build prod” button. This incorporates your translations into BrainHQ running on your production server. You can view BrainHQ on the production server at [your locale].brainhq.com (e.g., ko.brainhq.com for Korean)

### What does not need to be translated
All bins starting with the below prefixes
* ads-XX, except for ads you have specifically opted into by contacting Posit.
* exercise-XX where exercise is the name of an exercise that you have not opted into. Typically you will not have opted into exercises that require sound translations, or are very new on the Posit side.

###General Notes on Translating Text
If you build prod, and you have blue or red sections in your bar, your version of BrainHQ will display English text 

###Specific Notes on Translating Individual Keys
gift-example-email-msg: The mixed text and html in this key are very difficult to translate correctly. Please simply delete all of the text and html in this key. Your users will not see an example of the email their gift recipient will see when they receive a gift.
