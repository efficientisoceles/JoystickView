# JoystickView
A simple Android joystick that can be easily added to activities.

##Installation instructions:
1. Copy-Paste the JoystickView class into your Android project
2. Update the package information for the JoystickView so that it matches your package directory
3. Add it to your Activity's XML by using <*YOUR PACKAGE HERE*.JoystickView /> and set its attributes. It takes on the same attributes as a SurfaceView
4. Implement the JoystickView.JoystickListener interface in the activity you are using and implement the onJoystickMoved() method.
The onJoystickMoved method contains 2 floats between 0 and 1, indicating how far along the x and y (respectively) the joystick has been moved relative to its maximum.
It also contains an int at the end, which is the id of the joystick that is being moved. This id is equal to R.id.*YOUR_JOYSTICK_NAME*, assigned via android:id in the XML

##To be added in the future:
- More comments, and an actual JavaDoc. For now, the Instructable I made this for will have to suffice as explanation
- XML attributes that allow the joystick's color to be changed directly from the xml rather than from code
- Better joystick shading

##For more info...
Visit the instructable I made for this!: http://www.instructables.com/id/A-Simple-Android-UI-Joystick/
