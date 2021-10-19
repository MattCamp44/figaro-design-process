# Milestone 4: Usability Testing - Figaro

## Overview and Script

To understand the teat runs please follow the script. All tests have been run with only one person doing both facilitator and note-taker.


- [Link to script's pdf file](./Documents/Usability_Testing_Script.pdf)
- [Link to informed consent pdf file](./Documents/InformedConsentForm.pdf) 
- [Link to test run template pdf file](./Documents/Figarotestruntemplate.pdf) 

---
## Results 

### Test run 1 
- [link to pdf file](./Documents/Test_run_1.pdf) 



SUS score: 80
---

### Test run 2

- [link to pdf file](./Documents/Test_run_2.pdf) 



SUS score: 55
---


### Test run 3

- [link to pdf file](./Documents/Test_run_3.pdf) 



SUS score: 80
---
### Test run 4

- [link to pdf file](./Documents/Test_run_4.pdf) 




SUS score: 80
---

Tasks:
 * T1: Select an exercise to perform
 * T2: Perform an exercise
 * T3: Exit an exercise during execution
 * T4: Find the just executed exercise record
 * T5: Find your (hypothetically) weakest passages
 * T6: Find the day you (hypothetically) practised more in the last week
 * T7: Add an exercise to your favorites (go to favorite section, remove from favorite section)
 * T8: Add your picture to your profile, change your vocal range

| Task  | Main Issues    |  SEQ Score Average | Measurements | 
|---|---|---|---|
|  T1   |  Amateurs and those not familiar with musical concepts have difficulty anticipate what the exercises are about by just looking at the names  |  5  |  |
|  T2  | Some more time between the singing and the listening phases, too fast.	 Explaination expected before the exercise.      Would like indication of played note in listening phase. 	Not clear what will happen before the exercise starts.   Too fast, user could not keep up with it.    American notation not clear (C,D,E instead Do,Re,Mi)   | 5 | M1: 1,2,1,2 (Number of repetition)  |
|  T3  | It should say “tap here”, or it should be a button.  Users tend to press the circle (the circle works too).   User started to tap everywhere to find clickable area.     | 5.5 | M2: 3 sec, 1 sec, 1 sec, 4 sec |
|  T4  | User was searching for a type of “history” button rather than “statistics”.   Unclear treshold for good and bad score. 90% is a bad score?    | 5.5   | M3: 6 sec, 15 sec, 10 sec, 14 sec |
|  T5  | Name suggestions: transitions, jumps,      search icon in the box made me think that I could click on that portion of the screen, while then I’ve understood that it is only for displaying the weakest passage.    ERROR: User  thinks the exercise scores are the passages: wrong understanding   Actors seem to have a different understanding of the word "passage" than musicians.   It should be much more expressive and specific, at the cost of being wordy, something like "notes passages" or "tonality passages"   | 4  |   |
|  T6  | Second tab on statistics page: not clear what is in there, they don't seem to recognize the name of the tab.   It is not clear that chart represents the quantity of performed exercises.   Bars don't seem to be the best way to represent this data.       | 4 |  |
|  T7  | ERRORS: went to favorites tab first. Then, on the exercise list, a user clicked a black heart thinking it would add the exercise to favorites(it deletes it from favorites, some exercises were already added to favorites, maybe it would not have been an error if no heart was ticked already)   ERRORS: Went to favorite tab, went to stats tab, went to profile tab, tried to click on passages   Users seem not to remember the "hearts" from the first task. Maybe if this task is executed right after T1 they would remember? |  4.5  |  |
|  T8  | Visual information does not suggests what is clickable from what is not.   | 6  |   |


We learned that our prototype is quite usable and users has appreciated the simplicty in the UI. Most of the features are easily reachable and self descriptive and instinctive to use, thanks to the usage of common and known conventions on elements. We are proud of the exercise effectiveness, in general the users were able to understand the steps needed to perform it without additional knowledge. Specifically, inexperienced users appreciate the audio feedback during the singing phase, which makes them confident to use the application without having to learn the specific note convention (C#, D..).
In general the exercises resemble quite accurately real singing exercises as they have experienced them in real singing classes.


## List of Changes

* Slow down the exercise rythm, since at the moment the difficulty of the exercise is given by the length and different variation of passages. The rythm will be included in the definition of the difficulty of the exercise
* Adding a tutorial about the flow of the exercise, before it is started, probably on first application access or until explicitely hided by the user by means of a "don't show anymore" button
* We found out that the "passage" concept is too specific to the music, so we might want to find a more appropriate name for it
* Find different ways of showing the most practiced days, since we found out that the bar chart seems to be too "boring". We believe that a strengh of the application is to follow the user in improving his/her skills day by day, inserting more motivating and interactive sentences while showing the progress. 
* On the first tab of statistics, that has been generally appreciated, we had inserted a very high threshold on well-done exercises (*we have lowered this threshold after the usability testings*)
* We should add some other fields in the profile page, maybe aggregating the "static" and the editable configuration options, also differantiating them visually


