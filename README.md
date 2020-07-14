# Android-Artificial-Eyes-for-Visually-Impaired
 A computer vision Android app which detects objects in the user's surroundings through Android's rear camera and conveys the information about the objects through text-to-speech to the visually impaired user.

## What does it do?

* The app detects objects through the input stream from the Android phone's rear camera.
* It then determines the position of the detected objects, i.e. left, right, or middle.
* It also counts the number of each object detected.
* It also determines the relationship between certain objects, for example, if an object is near another object.
* After getting all the information about the objects, it constructs an English string, and passes it to the Text-to-Speech API.
* The TTS API then conveys the string to the visually impaired user. For example, if the app detects a bus on the left and a car on the right, the sentence spoken by the TTS will be "There is a **bus** on the **left** and a **car** on the **right** of the user."

## Future Scope

* The ruleset for relationship between objects can be vastly improved. One such case is suppose a cup is on the table, and if the app detects both the cup and the table, it should be able to calculate their relationship as "There is a **cup** on the **table** in **front** of the user."
* The model used for detection can be improved to increase accuracy.
