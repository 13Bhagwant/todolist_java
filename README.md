Edit README.MD and write the changes made in the project

# MainActivity.java

1. Add an AppBar menu that uses an 'add' button to open an item entry dialog to add new list entries.
2. Add logic to handle presenting item entry dialog.
3. Add touch gestures logic to clear the To-Do List with a long press.
4. Remove all unnecessary code (i.e. former add button + edit text and clear button components that are no longer necessary).

# Add Item fragment

1. You'll need to add a new .java file to your project to host the dialog fragment.This dialog should provide the ability for the user to enter text to add an item to the To-Do List.

# Drawables

1. Add an appropriate drawable for the AppBar menu (typically a '+' symbol for 'add' actions).

# activity_main.xml

1. The only thing our activity_main.xml file will need is a TextView. Remove all unnecessary buttons, and the ScrollView (note that we would probably prefer to keep the ScrollView in place, but it interferes with the TouchGesture control, since a long press on a ScrollView is used to initiate a scroll action. If we wanted to include both types of behaviour - scrolling through the list and a long press to clear - then we would be better off using a RecyclerView - but we're not quite there yet).And, in general, please be careful to choose appropriate naming conventions for all identifiers (i.e. variables, methods, etc.). Make sure your code is well-formatted before submission (no unnecessary whitespace, good indenting and spacing). And, of course, make sure it runs without errors!
