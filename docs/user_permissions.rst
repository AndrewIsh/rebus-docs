User Permissions
================

|image|

User permissions allow precise control of what different users are able
to do.

In rebus:list the abilities of the user are defined by their
permissions. These are grouped in two ways:

-  User Roles - These define users ability to manipulate lists and the
   materials on those lists and are discussed in the previous chapter.

-  User Types - These are groups of permissions for individual users and
   define how the system may be used and are dealt with in this chapter.

12.1 Default User types

rebus:list is highly configurable and allows for the editing or creation
of many different User Types. The system is delivered with four default
User Types:

-  librarian - Librarian level access

-  admin - Full access

-  staff - Standard staff access

-  public - View only access

The defaults are configured with different permissions to represent the
different tasks they may perform. From this screen you can access
permission management for any of the default User Types and also create
new User Types.

Click the dropdown to open permissions management for a specific user
type

|image|

12.2 Edit User types

To edit the privileges applied to each user type open the drop down.

You will be presented with the five areas as headed in green below.

Here you can:

-  Edit the user type name and short description

-  Assign or remove Responsibilities in the left column

-  Assign or remove individual Privileges in the right column

|image|\ Responsibilities and Privileges are also split into two rows
Assigned and Unassigned. This can be seen below for the librarian User
Type.

There are a large number of privileges available on rebus:list (see
appendix) so to make management simpler we have grouped these privileges
into areas of responsibility. Rolling over a responsibility will
highlight the related privileges in red.

|image|

In the example above we can see that the Requests responsibility has
been assigned to the Librarian User Type.

The permissions within the Requests responsibility group are highlighted
in red.

+-----------+-------------------------------------------------------------------------------------------+
| |image|   | Clicking the plus on a responsibility button will enable all the associated privileges.   |
+===========+===========================================================================================+
| |image|   | Clicking the Bin icon will disable all the associated privileges                          |
+-----------+-------------------------------------------------------------------------------------------+

Individual privileges can be assigned in addition to responsibilities

+-----------+----------------------------------------------------------------------------------------------------+
| |image|   | Clicking the plus on a privilege button will assign it for the User Type you are working with      |
+===========+====================================================================================================+
| |image|   | Clicking the plus on a privilege button will un-assign it for the User Type you are working with   |
+-----------+----------------------------------------------------------------------------------------------------+

|image|\ It’s possible to build a custom group of privileges quickly by
making use of a combination of responsibility groups and assigning /
un-assigning individual privileges

In the above example the Reports responsibility group has been added to
the librarian User Type. This has assigned all the Reporting privileges.

|image|

It may be the case that although a librarian should be able to work with
reports they shouldn’t be able to create them.

|image|\ The report-create privilege can be un-assigned by clicking on
the bin icon.

As only a subset of the privileges that make up the Reports
responsibility group are now assigned Reports no longer displays as an
assigned group

Using this method, you can quickly build a custom set of privileges for
your own user types.

There are several special privileges that fall outside the
responsibility groups. These are mainly concerned with global
administrative tasks.

-  sublist-suppress

-  taxon-assign

-  taxon-clone

-  taxon-delete

-  taxon-move

-  taxon-read

-  taxon-rollover

-  taxon-suppress

-  taxon-update

-  unit-assign

rebus:list uses the term ‘taxon’ to define any point or level within a
hierarchy e.g. a unit is a taxon, a list is a taxon, a sublist is also a
taxon.

12.3 Creating a User Type

If no default user type exists that fits staff workflows in your
organisation it’s quite straight forward to create a new user type.

Click the ADD NEW USER TYPE button

|image|\ You will be presented with a drop down where you must add a
name and short description for the new user type.

On ticking the box the assign privilege screen will display allowing you
to select the necessary permissions for your new User Type.

Your selections will auto save and your new User Type will be available
when you create or edit a user in User Management (see 11.2 Add a New
User).

|image|

12.4 Deleting a User Type

|image|\ To delete a user type, in Manage Permissions select the user
type and press the bin button. You will be given the option of confirm
or cancel. Select confirm and the User Type will be deleted. Any users
of that type will be reassigned a type of ‘public’


