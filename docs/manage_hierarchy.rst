9. Manage hierarchy

rebus:list is based around the concept of a hierarchy which determines
the navigation and browse structure of the system.

|image|\ There are four separate areas in the Manage Hierarchy Module

9.1 Creating and Modifying

The hierarchy is constructed from Organizational Units and Lists.

The structure below has Organizational Units of

-  University

-  Faculty

-  |image|\ Subject

Below which are the reading lists.

-  You can create as many Units or Lists as you need to suit your
   organization.

-  A List will always appear at the bottom of its branch in a hierarchy.

-  It is not possible to add a Unit on a level below a List on a given
   branch.

-  It is not possible to add a List on a level below a List on a given
   branch.

-  It is possible to create a Sublist but they are not handled as a part
   of Manage hierarchy.

Note. It is quite possible to use a single layer layout for the system.
For a future release ‘flat-mode’ is in development which will improve
browsing functionality for those users who have chosen not to implement
a hierarchical structure.

9.2 Creating a Unit

+--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+-----------+
| To create a hierarchy an Admin user needs to initially create a Unit at the top level. To do this click the Add New Unit button. This will open the Unit metadata page, see below.   | |image|   |
+======================================================================================================================================================================================+===========+
+--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+-----------+

|image|

Name is the only required field, the other fields allow you to provide
extra information if necessary. Click finish and your Unit will be
created.

9.3 Building a Hierachy

|image|\ You can create as many Units at the top level as you like and
then using the editing tools continue to build your hierarchy.

Above you can see two top level Units, one for Rebus Public Libraries
and another for the University of Rebus.

In the above example the editing tools have been expanded for the
University of Rebus.

+-----------+-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| |image|   | Clicking the green pen icon opens and closes the available editing tools for a Unit or List                                                                                                                                       |
+===========+===================================================================================================================================================================================================================================+
| |image|   | Clicking the bin icon will delete the current Unit or List. As a safety feature it is not possible to delete a whole branch of the hierarchy by clicking one high level button. All child Units or Lists must be deleted first.   |
+-----------+-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| |image|   | Clicking the pen icon in the edit tools will open the Unit or List metadata page for editing (see above).                                                                                                                         |
+-----------+-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| |image|   | Clicking this icon will suppress the Unit or List. This removes it from public view and it will no longer be browseable or searchable. Suppression is inherited so all lists below a supressed Unit will also be supressed.       |
+-----------+-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| |image|   | This is the add button in expanded form. If you click the plus icon you are then presented with the option of creating a Unit or List at the next level down the hierarchy.                                                       |
+-----------+-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+

Using these tools you can quickly and easily produce a hierarchy that
will suit your organisation.

9.4 Inheritance

You will notice when you create a Unit or List that many of the fields
have a placeholder of **(inherited from””)**. This placeholder indicates
that the field will inherit its contents from the level above if it is
left blank.

Inheritance is a very useful labour saving tool. Below you can see the
expanded tree for the University of Rebus.

|image|\ In a University setting all the lists may cover one academic
year. In that case ‘Year’ can be set at the top ‘University’ level and
will then be inherited down the hierarchy without the need to repeatedly
enter the data no matter how many lists there are.

Inheritance can also be overwritten further down the hierarchy.

Above ‘Year’ has been set as 2016 in the metadata in the University of
Rebus top level Unit. The boxes on the diagram show how 2016 is
inherited down the hierarchy.

The Faculty of the Arts lists are still being used from 2015.

Adding 2015 in the Year field of the Faculty of the Art Unit results in
2015 being inherited as year in all the Units and Lists down that
branch.

Note, the dates and boxes are examples only and do not display on the
system.

|image|\ 9.5 Moving Lists and Units

When you click the icon to open the move list functions you are
presented with a screen that displays the hierarchy twice. You can move
either a single list or a whole branch of your hierarchy.

|image|

+-----------+----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| |image|   | To move a List or Unit click on the four arrow icon next to the List or Unit name on the left hand side of the screen. and drag it into position on the righthand side of the screen   |
+===========+========================================================================================================================================================================================+
+-----------+----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+

When you have dragged your List or Unit into its new position the
hierarchy will automatically be saved. If you move a Unit it will move
the entire branch to the new position.

|image|\ 9.6 Cloning Lists or Units

Sometimes it might be necessary to clone a List or Branch to another
position in the hierarchy. The procedure for doing this is very similar
to moving lists.

|image|

+-----------+-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| |image|   | To clone a List or Unit click on the clone icon next to the List or Unit name on the left hand side of the screen. and drag it into position on the righthand side of the screen.   |
+===========+=====================================================================================================================================================================================+
+-----------+-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+

Above is an example of a situation when cloning lists might be used.

Rebus Public Library have created a mobile library service and have
created a Unit called Rebus Book Bus. This unit will only be made
available to users of the service.

The library wishes to provide some of the same lists as are listed under
the main Rebus Public Library. To avoid having to recreate the lists on
another branch they can clone them.

After cloning a List or Unit the hierarchy will be locked for editing
whilst the system recalculates inheritance. Recalculation can take some
time dependant on the size of the hierarchy that is being cloned.

Note: A Cloned List is a separate entity to the original list. Changes
made to one will not automatically effect the other.

|image|\ 9.7 Rollover Lists

Rollover lists is a management function - it provides the ability to
roll a list into the next year - updating its dates and optionally
creating an archived version. This is a feature which is especially
useful for academic institutions who wish to retain historic lists as
well as those changed for the new academic year.

When you click the rollover icon you are presented with the choice to
archive your current list or not.

\|l\|l\| |image| &

-  Archive - save your current list and create another with the rolled
   forward dates.

-  No Archive - just roll dates forward.

| 

|image|\ You will notice the rollover icon is available next to each
level allowing you to rollover individual lists or Faculty Units or Top
level Units.

In the above example

-  Rollover has been selected for University of Rebus. All lists within
   the hierarchy beneath University of Rebus will be rolled over.

-  If the situation arose that only the Faculties of Science and
   Humanities wanted to rollover then that could also be done by
   selecting rollover at those respective levels.

-  When a list is rolled over and an archived version is created, the
   archived version will appear alongside the rolled over list in the
   hierarchy.

-  When rollover is taking place the hierarchy will display as locked
   whilst inheritence is recalculated.


