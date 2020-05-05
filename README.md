# Caregiver Dashboard View

UI in development here: https://www.figma.com/file/f23nTHED4ITyKO0dDzTs2T/expressivecare?node-id=0%3A1

Distance care tools

Users:

Caregiver
Student

Environment:

Caregiver has a tablet in home 1
Student has a tablet in home 2


(Student and caregiver are also connected via video chat either on separate devices or using picture-in-picture with zoom but we will not build the video part itself)

Functionality:

Caregiver controls everything that happens on the student’s screen in realtime. 

The main behavioral loop is 
1. Caregiver prompts
2. Student responds 
3. Caregiver rewards or waits and tries again 

In the app, Caregiver can remotely
Trigger animations
Display “flashcards”
Begin, pause, and end media playback


Features:

Display Animations

Caregiver’s interfaceI shows a “drawer” of icons that represent animations
The app will provide a default set of animations
Future versions may use Giphy or other API’s
As soon as the Caregiver taps the icon, the animation is played once on the Student’s screen. 
All animations should take place on the highest level so they can play on top of Flashcards and other media. 



Display Flashcards

Caregiver UI shows a “drawer of icons that represent Flashcards
The app provides a default set of Flashcards (images)
Caregiver can also upload and store custom images
As soon as the Caregiver taps the icon, the Flashcard is displayed on the Student’s screen. 
When a Flashcard is displayed on a Student’s screen, the corresponding icon on Caregiver’s screen indicates an active state. 
When the Caregiver taps the icon a second time the Flashcard is removed from the Student’s screen and the icon stops indicating active state.
Animations can also be played over the top of Flashcards at any point. 
Next version will allow the act of triggering animations to remove all visible flashcards.

Control Media

Caregiver can display and control the playback of videos
Functionality is identical to displaying flashcards except the Caregiver can start and stop the media playback 

Mirror view

	Caregiver has a view of what is being shown on the student’s screen at all times.



 
