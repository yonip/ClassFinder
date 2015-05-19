# ClassFinder
This application will provide a selection of courses to indecisive magnet students in order to help them choose courses, along with a description of courses and which courses they should take based on the student

#Priorities
1. Simple - easy to navigae UI
    a. low clutter, mostly text
    b. use text fields and drop-down menus
    c. few screens to pick from, with buttons to navigate
2. Organized - every element in its place
    a. divide into subjects
    b. each view is self contained
    c. table, menus
3. Permits mistakes
    a. doesn't advance to next screen immediately after selection
    b. undo/redo buttons
    c. final button to advance to next part of selector after selections have been made
4. Relevant - nothing unnecessary, streamline operations
    a. emphasize magnet/ap/honors classes
    b. discourage courses that need prerequesets, but still allow it
    c. show information as to why to pick a course
5. Time budgeting - streamline operation
    a. can pick courses and fill in semester schedule
    b. requirements filled in
7. Versatility
    a. open source, can help with making/fixing app

#Storyboard

A1: This scrollable activity will be launched when the application opens. The user enters their grade, their main interest (they have an option to add up to 5 interests). At the bottom there is a floating "begin" button which leads to B1.

B1: Previously selected courses, previous courses already filled in and greyed out, then any electives are activated buttons, that when pressed, bring up a pop up (B1p). Once filled in, this view will also allow to star classes, and a "continue" button at the bottom leading to C1.

C1: Lets the user pick desired courses in the future, not neccesarily for the next year, using a similar principal to B1's method of picking courses via popup. At the bottom, a "continue" button leads to E1

D1: Blank sheet.

E1: Final screen that similar to B1, where requirements are already filled in, and electives can be selected via popup, similar to B1p, except this popup is sorted by "suggested courses" and gives an explanation as to why the user might want to pick the course.