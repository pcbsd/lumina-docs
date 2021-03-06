.. index:: Utilities
.. _Utilities:

Utilities
*********

|lumina| provides many built-in utilities, which are described in this
chapter.

.. index:: archiver
.. _Lumina Archiver:

Archiver
========

The |lumina| Archiver, seen here in :numref:`Figure %s <luminaarc1>`,
provides compression/decompression services for a wide variety of file
types. It is listed with other utilities in the GUI, or can be opened
with :command:`lumina-archiver` in a CLI.

.. _luminaarc1:

.. figure:: images/luminaarc1.png
   :scale: 100%

   |lumina| Archiver

The :guilabel:`File` and :guilabel:`Edit` categories contain all
operations for the utility, which are also reproduced in the icon
toolbar. :numref:`Table %s <arcmanops>` lists all operations for the
Archive Manager:

.. tabularcolumns:: |>{\RaggedRight}p{\dimexpr 0.20\linewidth-2\tabcolsep}
                    |>{\RaggedRight}p{\dimexpr 0.10\linewidth-2\tabcolsep}
                    |>{\RaggedRight}p{\dimexpr 0.20\linewidth-2\tabcolsep}
                    |>{\RaggedRight}p{\dimexpr 0.10\linewidth-2\tabcolsep}
                    |>{\RaggedRight}p{\dimexpr 0.40\linewidth-2\tabcolsep}|

.. _arcmanops:

.. table:: Archiver operations

   +-----------+------+-------------+----------+-----------------------+
   | Command   | Menu | Icon        | Shortcut | Result                |
   +===========+======+=============+==========+=======================+
   | New       | File | Page with   | Ctrl + N | Opens a window to     |
   | Archive   |      | White Plus  |          | create a new archive  |
   |           |      |             |          | file                  |
   +-----------+------+-------------+----------+-----------------------+
   | Open      | File | Folder with | Ctrl + O | Open an existing      |
   | Archive   |      | File        |          | archive               |
   +-----------+------+-------------+----------+-----------------------+
   | Quit      | File | None        | Ctrl + Q | Exit the utility      |
   +-----------+------+-------------+----------+-----------------------+
   | Add       | Edit | Page with   | None     | Add a file to an open |
   | Files     |      | Green Plus  |          | archive               |
   +-----------+------+-------------+----------+-----------------------+
   | Add       | Edit | Folder      | None     | Add a directory to an |
   | Directory |      | with Plus   |          | open archive          |
   +-----------+------+-------------+----------+-----------------------+
   | Remove    | Edit | Page with   | None     | Removes the selected  |
   | Files     |      | Red X       |          | file from the archive |
   +-----------+------+-------------+----------+-----------------------+
   | Extract   | Edit | Page with   | Ctrl + E | Opens a window to     |
   | All       |      | White Arrow |          | extract the entire e  |
   |           |      |             |          | contents of the       |
   |           |      |             |          | archive               |
   +-----------+------+-------------+----------+-----------------------+
   | Extract   | Edit | Page with   | None     | Opens a window to     |
   | Selection |      | White Arrow |          | extract the           |
   |           |      |             |          | highlighted archive   |
   |           |      |             |          | contents              |
   +-----------+------+-------------+----------+-----------------------+

The primary window under the icon toolbar displays several elements:

* **Archive:** The full pathway to the opened archived.
* **File:** Lists the names of the files in the archive.
* **Mimetype:** Lists the mimetypes of archived files.
* **Size:** Displays the total size of the archived files.

The small section under the primary window will display any tooltips
when hovering over an icon, as well as messages indicating an
operation's success or failure.

.. index:: calculator
.. _Lumina Calculator:

Calculator
==========

The |lumina| calculator utility is designed to provide a simple and
intuitive interface paired with advanced functions and features. Open
the calculator through the *Utilities* category of the application list,
or by typing :command:`lumina-calculator` in a CLI. The interface is
seen in :numref:`Figure %s <lcalc1>`:

.. _lcalc1:

.. figure:: images/lcalc1a.png
   :scale: 100%

   |lumina| Calculator

The calculator is configured to use a numpad, if one is available.
Enter the values and an operation, and the calculator displays the
answer in the upper window. Select an equation displayed in the upper
window to paste it in the entry field. On the right side of the output
display are two icons. Press the :guilabel:`Paper with red circle` to
clear the entire output history. Press the :guilabel:`disk and pencil`
icon to save the calulator history as a basic text document.

|lumina| Calculator also supports a variety of advanced operations, seen
in :numref:`Figure %s <lcalc2>`.

.. _lcalc2:

.. figure:: images/lcalc2.png
   :scale: 100%

   |lumina| Calculator Advanced Operations

These advanced operations can be selected from the drop down menu, or
typed manually. The full list of available operations is seen in
:numref:`Table %s <lcalcops>`.

.. tabularcolumns:: |>{\RaggedRight}p{\dimexpr 0.80\linewidth-2\tabcolsep}
                    |>{\RaggedRight}p{\dimexpr 0.20\linewidth-2\tabcolsep}|

.. _lcalcops:

.. table:: |lumina| Calculator Advanced Operations
   :class: longtable

   +---------------------+--------+
   | Operation           | Symbol |
   +=====================+========+
   | Percentage          | %      |
   +---------------------+--------+
   | Power               | ^      |
   +---------------------+--------+
   | Base-10 Exponential | E      |
   +---------------------+--------+
   | Exponential         | e      |
   +---------------------+--------+
   | Constant Pi         | π      |
   +---------------------+--------+
   | Square Root         | sqrt(  |
   +---------------------+--------+
   | Logarithm           | log(   |
   +---------------------+--------+
   | Natural Log         | ln(    |
   +---------------------+--------+
   | Sine                | sin(   |
   +---------------------+--------+
   | Cosine              | cos(   |
   +---------------------+--------+
   | Tangent             | tan(   |
   +---------------------+--------+
   | Arc Sine            | asin(  |
   +---------------------+--------+
   | Arc Cosine          | acos(  |
   +---------------------+--------+
   | Arc Tangent         | atan(  |
   +---------------------+--------+
   | Hyperbolic Sine     | sinh(  |
   +---------------------+--------+
   | Hyperbolic Cosine   | cosh(  |
   +---------------------+--------+
   | Hyperbolic Tangent  | tanh(  |
   +---------------------+--------+

.. index:: file manager
.. _Insight File Manager:

Insight File Manager
====================

The Insight file manager, shown in :numref:`Figure %s <lumina10>`,
allows the user to easily browse and modify files on the local system.
To open Insight, click the start menu and select
:guilabel:`Browse Files`, right-click the desktop and select
:guilabel:`Browse Files`, or type :command:`lumina-fm` from an xterm.

.. note:: If Insight is already open, :command:`lumina-fm` activates the
   currently open instance of Insight and adds a new tab. Open a new
   window of Insight by pressing :kbd:`Ctrl + N` when the current
   Insight window is active.

.. _lumina10:

.. figure:: images/lumina10c.png
   :scale: 100%

   Insight File Manager

The top menu bar offers a wide variety of options for controlling
Insight:

* **File:** Contains basic options for manipulating Insight, seen here
  in :numref:`Table %s <insightfile>`.

  .. tabularcolumns:: |>{\RaggedRight}p{\dimexpr 0.25\linewidth-2\tabcolsep}
                      |>{\RaggedRight}p{\dimexpr 0.15\linewidth-2\tabcolsep}
                      |>{\RaggedRight}p{\dimexpr 0.60\linewidth-2\tabcolsep}|

  .. _insightfile:

  .. table:: Insight Manager *File* Options
     :class: longtable

     +------------------+----------+-----------------------------------+
     | Name             | Shortcut | Description                       |
     +==================+==========+===================================+
     | New Window       | Ctrl + N | Creates a new instance of Insight |
     +------------------+----------+-----------------------------------+
     | New Tab          | Ctrl + T | Opens a new tab in Insight        |
     +------------------+----------+-----------------------------------+
     | Search Directory | Ctrl + F | Opens :ref:`Lumina Search`        |
     +------------------+----------+-----------------------------------+
     | Close Tab        | Ctrl + W | Removes an open tab               |
     +------------------+----------+-----------------------------------+
     | Exit             | Ctrl + Q | Closes Insight                    |
     +------------------+----------+-----------------------------------+

* **View:** Presents options to alter what Insight displays to the user.
  :numref:`Table %s <insightview>` shows the current options in the
  :guilabel:`View` tab:

  .. tabularcolumns:: |>{\RaggedRight}p{\dimexpr 0.25\linewidth-2\tabcolsep}
                      |>{\RaggedRight}p{\dimexpr 0.15\linewidth-2\tabcolsep}
                      |>{\RaggedRight}p{\dimexpr 0.60\linewidth-2\tabcolsep}|

  .. _insightview:

  .. table:: Insight Manager "View" Options
     :class: longtable

     +-------------+----------+----------------------------------------+
     | Name        | Shortcut | Description                            |
     +=============+==========+========================================+
     | Refresh     | F5       | Reloads the current location           |
     +-------------+----------+----------------------------------------+
     | Show Hidden | Ctrl + H | Insight displays all files marked      |
     | Files       |          | *hidden*                               |
     +-------------+----------+----------------------------------------+
     | Show Image  | None     | Displays a small thumbnail of the      |
     | Previews    |          | image file in the Insight window       |
     +-------------+----------+----------------------------------------+
     | View Mode   | None     | Basic: Displays the names of files and |
     |             |          | directories.                           |
     |             |          | Advanced: Displays Name, Size, Type,   |
     |             |          | Date Modified, and Date Created for    |
     |             |          | each file or directory.                |
     +-------------+----------+----------------------------------------+

* **Bookmarks:** The :guilabel:`Bookmarks` not only gives options to
  add and manipulate internal links for quick navigation with Insight,
  but also displays any created bookmarks in the drop-down menu.
  :numref:`Table %s <insightbkmrks>` describes all these elements:

  .. tabularcolumns:: |>{\RaggedRight}p{\dimexpr 0.25\linewidth-2\tabcolsep}
                      |>{\RaggedRight}p{\dimexpr 0.15\linewidth-2\tabcolsep}
                      |>{\RaggedRight}p{\dimexpr 0.60\linewidth-2\tabcolsep}|

  .. _insightbkmrks:

  .. table:: Insight Manager *Bookmark* Options
     :class: longtable

     +------------------+----------+--------------------------+
     | Name             | Shortcut | Description              |
     +==================+==========+==========================+
     | Manage Bookmarks | Ctrl + B | Allows modification      |
     |                  |          | or removal of bookmarks  |
     +------------------+----------+--------------------------+
     | Add Bookmark     | Ctrl + D | Creates new bookmark of  |
     |                  |          | current location         |
     +------------------+----------+--------------------------+
     | Bookmark Display | None     | Populates with bookmarks |
     |                  |          | as they are created      |
     +------------------+----------+--------------------------+

* **External Devices:** Any attached devices with storage appears in
  this menu. Click :guilabel:`Scan for Devices` if an attached device
  does not appear.

* **Git:** Basic GitHub functionality is natively built into Insight.
  Currently, :guilabel:`Repo Status` displays the active branch, update
  status with the origin repository, and any uncommitted changes.
  :guilabel:`Clone Repository` opens a wizard to download a git
  repository from the internet, seen in :numref:`Figure %s <lumina34>`.

  .. _lumina34:

  .. figure:: images/lumina34.png

     Git Clone Repository Wizard

  .. tip:: :guilabel:`Clone Repository` deactivates when Insight
     navigates inside a directory already labeled as a git repository.

Underneath the top menu bar is a navigation bar with even more options.
From left to right, :numref:`Table %s <insightnav>` describes each icon:

.. tabularcolumns:: |>{\RaggedRight}p{\dimexpr 0.30\linewidth-2\tabcolsep}
                    |>{\RaggedRight}p{\dimexpr 0.70\linewidth-2\tabcolsep}|

.. _insightnav:

.. table:: Insight Manager Navigation bar

   +------------+--------------------------------------------------+
   | Item       | Description                                      |
   +============+==================================================+
   | Left Arrow | Go back to previous directory                    |
   +------------+--------------------------------------------------+
   | Up Arrow   | Go to parent directory                           |
   +------------+--------------------------------------------------+
   | House Icon | Go to home directory                             |
   +------------+--------------------------------------------------+
   | Text Field | Path to current location/Manual navigation field |
   +------------+--------------------------------------------------+
   | Boxes with | Single column view                               |
   | "x"        |                                                  |
   +------------+--------------------------------------------------+
   | Boxes with | Dual column view                                 |
   | plus       |                                                  |
   +------------+--------------------------------------------------+
   | Vertical   | Additional file and directory operations (also   |
   | dots icon  | available by right-clicking in the display area) |
   +------------+--------------------------------------------------+

Pressing the :guilabel:`Plus Columns` button next to the navigation
field activates columned browsing, displaying two independent instances
of the file manager in a side-by-side view, seen in
:numref:`Figure %s <lumina33>`.

.. _lumina33:

.. figure:: images/lumina33a.png

   Insight Columns Display

In columns mode, the active column has a white background. All the menu
options and ZFS functions apply to **only** the active column.

The :guilabel:`Vertical Dots Icon` shows file and directory operations,
commonly seen in the right-click menu when an item is selected. The
directory operations are always available and as the name implies,
provide options affecting the entire directory.
:numref:`Table %s <insdirops>` shows each of these options, split into
the :guilabel:`Create...` and :guilabel:`Open...` categories:

.. tabularcolumns:: |>{\RaggedRight}p{\dimexpr 0.20\linewidth-2\tabcolsep}
                    |>{\RaggedRight}p{\dimexpr 0.10\linewidth-2\tabcolsep}
                    |>{\RaggedRight}p{\dimexpr 0.20\linewidth-2\tabcolsep}
                    |>{\RaggedRight}p{\dimexpr 0.50\linewidth-2\tabcolsep}|

.. _insdirops:

.. table:: Insight Manager Directory Operations
   :class: longtable

   +-------------+----------+-----------+-----------------------+
   | Item        | Category | Shortcut  | Description           |
   +=============+==========+===========+=======================+
   | File        | Create   | Ctrl +    | Create new file       |
   |             |          | Shift + F |                       |
   +-------------+----------+-----------+-----------------------+
   | Directory   | Create   | Ctrl +    | Create new directory  |
   |             |          | Shift + N |                       |
   +-------------+----------+-----------+-----------------------+
   | Application | Create   | Ctrl + G  | Launches wizard to    |
   | Launcher    |          |           | create link to        |
   |             |          |           | desired application   |
   +-------------+----------+-----------+-----------------------+
   | Terminal    | Launch   | F1        | Launches the default  |
   |             |          |           | terminal set to the   |
   |             |          |           | current directory     |
   +-------------+----------+-----------+-----------------------+
   | Slideshow   | Launch   | F6        | Creates and populates |
   |             |          |           | a slideshow within a  |
   |             |          |           | new Insight tab       |
   +-------------+----------+-----------+-----------------------+
   | Multimedia  | Launch   | F7        | Opens the directory   |
   | Player      |          |           | with the default      |
   |             |          |           | multimedia player     |
   +-------------+----------+-----------+-----------------------+

Once an item is highlighted in Insight, a number of file operations
become available, seen in :numref:`Table %s <insightfileops>`:

.. tabularcolumns:: |>{\RaggedRight}p{\dimexpr 0.20\linewidth-2\tabcolsep}
                    |>{\RaggedRight}p{\dimexpr 0.10\linewidth-2\tabcolsep}
                    |>{\RaggedRight}p{\dimexpr 0.20\linewidth-2\tabcolsep}
                    |>{\RaggedRight}p{\dimexpr 0.50\linewidth-2\tabcolsep}|

.. _insightfileops:

.. table:: Insight Manager Operations
   :class: longtable

   +------------+------------+--------------+-------------------------+
   | Item       | Category   | Shortcut     | Description             |
   +============+============+==============+=========================+
   | Open       | None       | Double-Click | Open the file or        |
   |            |            |              | directory with the      |
   |            |            |              | default applications    |
   +------------+------------+--------------+-------------------------+
   | Open With  | None       | None         | Opens the file or       |
   |            |            |              | directory with a        |
   |            |            |              | chosen application      |
   +------------+------------+--------------+-------------------------+
   | Cut        | File       | Ctrl + X     | Used with *Paste* to    |
   | Selection  | Operations |              | move a file             |
   +------------+------------+--------------+-------------------------+
   | Copy       | File       | Ctrl + C     | Used with *Paste* to    |
   | Selection  | Operations |              | create an exact         |
   |            |            |              | duplicate of the        |
   |            |            |              | selected file           |
   +------------+------------+--------------+-------------------------+
   | Rename     | File       | F2           | Allows changing the     |
   |            | Operations |              | title of the selection  |
   +------------+------------+--------------+-------------------------+
   | Delete     | File       | Del          | Removes the selection   |
   | Selection  | Operations |              | from the system         |
   +------------+------------+--------------+-------------------------+
   | Auto       | File       | Ctrl + E     | Uses *lumina-archiver*  |
   | Extract    | Operations |              | to extract the file     |
   +------------+------------+--------------+-------------------------+
   | Checksums  | View       | None         | Displays the file's     |
   |            | Files      |              | checksum                |
   +------------+------------+--------------+-------------------------+
   | Properties | View       | None         | Displays the file       |
   |            | Files      |              | information of the      |
   |            |            |              | selection               |
   +------------+------------+--------------+-------------------------+
   | Paste      | None       | Ctrl + V     | Used with *Cut* or      |
   |            |            |              | *Copy* to move or clone |
   |            |            |              | files and directories   |
   +------------+------------+--------------+-------------------------+

The final element to the upper Insight menus, if configured, is the ZFS
snapshot bar, seen as the long blue line in :ref:`Insight <lumina10>`.
If the system is formatted with ZFS and snapshots of the current
directory are available, this bar allows the user to view the current
directory from previous snapshots. In other words, the user can see past
instances of the directory, as long as ZFS is configured to take
periodic snapshots.

Snapshots are organized with oldest to newest snapshots displayed on the
line from left to right. The text box on the left side of the blue line
shows the active snapshot. Click the text box to view the other
snapshots and choose which snapshots to activate. A slider also exists
which can be used to move the directory back and forward in time,
according to the saved snapshots. The left and right arrows can also be
used for this function.

Insight displays the directory tree in a small window on the left side.
This display can also be used to navigate to the desired directory.

Underneath the viewing area of Insight are :guilabel:`Magnifying Glass`
icons, used to increase or decrease the size of the objects to display.
Also, the bottom left corner will display tooltips about the highlighted
object or other relevant information.

.. index:: File Information
.. _File Information:

File Information
================

The :command:`lumina-fileinfo` utility is used to open a graphical
window summarizing the size, permissions and ownership, creation time,
and last modification time of the specified file or directory. In the
example shown in in :numref:`Figure %s <file1>`, the user has typed
:command:`lumina-fileinfo Downloads` from a terminal window to view
the file information of their :file:`~/Downloads` directory.

.. _file1:

.. figure:: images/file1a.png
   :scale: 100%

   Sample File Information

.. index:: Information
.. _Information:

Information
===========

This utility provides information about the installed version of
|lumina|, as well as the license, acknowledgements, and project links.
To launch this utility, right-click the desktop and select
:menuselection:`Preferences --> About Lumina`, click
:menuselection:`Start Menu --> Question Mark icon` in
:guilabel:`Preferences`, or type :command:`lumina-info` in a terminal
window. An example is shown in :numref:`Figure %s <about1>`.

.. _about1:

.. figure:: images/about1c.png
   :scale: 100%

   About |lumina|

The :guilabel:`General` tab contains a variety of information:

* **Desktop Version:** Indicates the version of |lumina|.

* **OS Build:** Indicates the operating system used to build this
  version of |lumina|.

* **Qt Version:** Click :guilabel:`View Information` to display the QT
  version and its license.

* **Lumina Website:** Click :guilabel:`Lumina Website` to open
  `<http://lumina-desktop.org/>`_ in the default web browser.

* **Ask the Community:** Click :guilabel:`Ask the Community` to open
  `<https://webchat.freenode.net/?channels=%23lumina-desktop>`_, a
  chat channel dedicated to |lumina| with many friendly and helpful
  users.

* **Source Repository:** Click :guilabel:`Source Repository` to open
  `<https://github.com/trueos/lumina>`_ in the default web browser.

* **Report a Bug:** Click :guilabel:`Bug Reports` to open
  `<https://bugs.pcbsd.org/projects/pcbsd>`_ in the default web browser.
  Refer to :ref:`Report a Bug` for instructions on how to submit a bug
  report.

The :guilabel:`License` tab contains the license text for |lumina|.
|lumina| is licensed under a
`3-clause BSD license <https://github.com/trueos/lumina/blob/master/LICENSE>`_.

The :guilabel:`Acknowledgements` tab contains a few elements:

* **Project Lead:** The name of the Project's lead developer. Click the
  name to open his or her profile on GitHub in the default web browser.

* **Contributors:** Click :guilabel:`Open in web browser` link to open
  `<https://github.com/trueos/lumina/graphs/contributors>`_.

* **Sponsors:** lists the official sponsors of the |lumina| Project.

.. index:: application launcher
.. _Open:

Open
====

To open a file, directory, or URL from the command line, type
:command:`lumina-open` followed by the full path to the file or the URL.
This utility will look for an appropriate application to use to open the
specified file or URL. If there is no default application registered for
the input type, a small dialog will prompt the user to select which
application to use, and optionally set it as the default application for
this file type. As seen in the example shown in
:numref:`Figure %s <lumina11>`, this dialog organizes the available
applications into three types:

.. _lumina11:

.. figure:: images/lumina11b.png
   :scale: 100%

   |lumina| Open

* **Preferred:** These applications register their Mime type with the
  system and can open that type of file. Also included are any
  applications used to open this type of file before, as it keeps track
  of the last three applications used for that file type.

* **Available:** Displays all the applications installed on the system,
  organized by category and name.

* **Custom:** The user can manually type in the binary name or path of
  the application to use. A search button is also available for the
  user to graphically search the system for the binary. Whenever text
  is entered, a check is performed to determine if it is a valid
  binary, changing the icon to a :guilabel:`green checkmark` or
  :guilabel:`red X` as appropriate.

.. index:: screenshot
.. _Screenshot:

Screenshot
==========

This utility can be used to take screenshots of the desktop or selected
window and save them as PNG image files. To launch this utility, click
the start menu and select
:menuselection:`Browse Applications --> Utility --> Lumina Screenshot`,
right-click the desktop and select
:menuselection:`Applications --> Utility --> Lumina Screenshot`, type
:command:`lumina-screenshot` from a terminal window, or press
:kbd:`Print Screen`.

The utility opens with the *View* tab open by default, as seen in
:numref:`Figure %s <lumina25>`.

.. _lumina25:

.. figure:: images/lumina25c.png
   :scale: 100%

   Lumina Screenshot with *View* tab open.

The top menu bar contains several common options, while the tabs contain
configuration options for screenshots. :numref:`Table %s <lssmo>` lists
the options in this top menu bar:

.. tabularcolumns:: |>{\RaggedRight}p{\dimexpr 0.20\linewidth-2\tabcolsep}
                    |>{\RaggedRight}p{\dimexpr 0.20\linewidth-2\tabcolsep}
                    |>{\RaggedRight}p{\dimexpr 0.60\linewidth-2\tabcolsep}|

.. _lssmo:
.. table:: Lumina Screenshot menu options
   :class: longtable

   +---------+----------+----------------------------------------------+
   | Option  | Shortcut | Description                                  |
   +=========+==========+==============================================+
   | Capture | Ctrl + N | Take a screenshot.                           |
   +---------+----------+----------------------------------------------+
   | Save As | Ctrl + S | Open the *Save Screenshot* window to name    |
   |         |          | and save the new screenshot.                 |
   +---------+----------+----------------------------------------------+
   | Quick   | None     | Saves the screenshot to :file:`/Pictures` in |
   | Save    |          | the format                                   |
   |         |          | *Screenshot-yr-mth-dy-hr-min-sec.png*. An    |
   |         |          | *Open With* window appears for the user to   |
   |         |          | view the screenshot.                         |
   +---------+----------+----------------------------------------------+
   | Close   | Esc      | Closes **lumina-screenshot**.                |
   +---------+----------+----------------------------------------------+

Underneath the top menu bar are tabs for viewing and configuring
screenshots.

The *View* tab displays the most recent screenshot. Adjust the slider
on the left to zoom in or out on the screenshot. Click and drag anywhere
on the screenshot to designate an area to crop. Click again to remove
the highlighted area. When satisfied, click :guilabel:`Crop` to remove
everything from the screenshot outside the highlighted area. Click
:guilabel:`Open With...` to quicksave the screenshot and designate an
application to view or further manipulate the screenshot.

Use the settings tab to configure how a screenshot is taken.

:numref:`Figure %s <lumina39>` shows the *Settings* tab, while
:numref:`Table %s <lscrnshtmn>` lists all options for configuring
screenshots:

.. _lumina39:

.. figure:: images/lumina39.png
   :scale: 100%

   Lumina Screenshot with *Settings* tab open.

.. tabularcolumns:: |>{\RaggedRight}p{\dimexpr 0.30\linewidth-2\tabcolsep}
                    |>{\RaggedRight}p{\dimexpr 0.70\linewidth-2\tabcolsep}|

.. _lscrnshtmn:

.. table:: Lumina Screenshot UI Options
   :class: longtable

   +-----------------+-------------------------------------------------+
   | Option          | Description                                     |
   +=================+=================================================+
   | Entire Session  | Captures the entire screen.                     |
   +-----------------+-------------------------------------------------+
   | Single Screen   | For multi-monitor setups. The screen number     |
   |                 | can be selected for the screenshot.             |
   +-----------------+-------------------------------------------------+
   | Single Window   | Captures a selected window. With this selected, |
   |                 | click :guilabel:`Capture`, and click the        |
   |                 | desired window. The :guilabel:`Include Borders` |
   |                 | checkbox is used to determine if the utility    |
   |                 | takes a screenshot of the window with its       |
   |                 | border frame.                                   |
   +-----------------+-------------------------------------------------+
   | Delay           | Choose the number of seconds to delay the       |
   |                 | screen capture after pressing                   |
   |                 | :guilabel:`Capture`.                            |
   +-----------------+-------------------------------------------------+
   | Show warnings   | Check this box to have the utility provide a    |
   |                 | popup prompt when closing without saving the    |
   |                 | screenshot.                                     |
   +-----------------+-------------------------------------------------+

.. index:: search
.. _Lumina Search:

|lumina| Search
===============

|lumina| Search provides options to find and launch applications or to
quickly search for files and directories. The ***** wildcard can be used
in the search terms and the search will include hidden files if the
search term starts with a dot (**.**).

To start this utility, type :command:`lumina-search`, press
:kbd:`Alt + F2`, or go to the start menu and press
:menuselection:`Browse Applications --> Utility --> Lumina Search`.
:numref:`Figure %s <lumina13>` shows a screenshot of this utility.

.. _lumina13:

.. figure:: images/lumina13b.png
   :scale: 100%

   Search for Applications

To open an application, begin to type its name into the search field
(selected by default). The box below the selected
:guilabel:`Applications` button displays any matching application names.
To open an application, select the desired application and click
:guilabel:`Launch Item`.

Click :guilabel:`Files or Directories` to change the screen slightly,
as seen in :numref:`Figure %s <lumina26>`.

.. _lumina26:

.. figure:: images/lumina26.png
   :scale: 100%

   Search for Files

By default, a :guilabel:`Files or Directories` search is limited to the
user's home directory, as indicated by the :guilabel:`Search: ~` at the
bottom of the screen. :guilabel:`Smart: Off` indicates every
subdirectory is included in the search, with no exlusions. Once
subdirectories have been added to the exclusion list, :guilabel:`Smart:`
switches to :guilabel:`On`, and the excluded subdirectories are shown on
the :guilabel:`Search:` section of the menu. To add more search
directories or to exclude subdirectories, click the :guilabel:`wrench`
to see the screen shown in :numref:`Figure %s <lumina14>`.

.. _lumina14:

.. figure:: images/lumina14a.png
   :scale: 100%

   Search Configuration

Click the :guilabel:`blue folder` icon to change the starting search
directory. For example, select :guilabel:`Computer`, then
:guilabel:`/` from the :guilabel:`Select Search Directory` screen to
search the entire contents of the computer. Click :guilabel:`+` to add
directories to an exclusion list for searching. Delete an exclusion by
highlighting its entry and clicking :guilabel:`-`. The
:guilabel:`Save as Defaults` option is selected by default. Uncheck
this option to return the all customized search settings back to their
defaults after closing the menu.

.. index:: textedit
.. _Lumina Text Editor:

Text Editor
===========

The :command:`lumina-textedit` utility is a plaintext editor with a
number of basic options. :numref:`Figure %s: <lumina23>`
shows the editor with no file opened.

.. note:: Typing :command:`lte` in the command line will also open the
   |lumina| Text Editor.

.. _lumina23:

.. figure:: images/lumina23.png
   :scale: 100%

   |lumina| Text Edit

Clicking :guilabel:`File` presents options to create *New File*,
*Open File*, *Close File*, *Save file*, *Save File As*, and *Close*.
Click :guilabel:`Edit` to open options to *Find* and *Replace*, also
usable with :kbd:`Ctrl-F` and :kbd:`Ctrl-R`, respectively. The
:guilabel:`View` tab can be used to alter *Syntax Highlighting*,
*Line Numbers*, *Wrap Lines*, and *Customize Colors*. By default,
brackets are highlighted, lines are numbered, and words wrap dynamically
with the edge of the window. Additionally, selecting
:guilabel:`Customize Colors` gives the option to alter all the default
text and highlight colors, as seen in :numref:`Figure %s <lumina32>`.

.. _lumina32:

.. figure:: images/lumina32.png
   :scale: 100%

   Customize Colors

.. index:: lumina-mediaplayer
.. _Lumina Media Player:

Lumina Media Player
===================

:command:`lumina-mediaplayer` is a very basic music player with included
integrations for the Pandora internet radio streaming service. Lumina
Media Player can be found in the
:menuselection:`Applications --> Utilities` section, or by typing
:command:`lumina-mediaplayer` in a command line.

Lumina Media Player is essentially a basic graphic interface for the Qt
`QMediaPlayer Class <http://doc.qt.io/qt-5/qmediaplayer.html>`_. This
class supports many audio formats, including *.ogg*, *.mp3*, *.mp4*,
*.flac*, and *.wmv*. You can increase the number of playable formats by
installing *gstreamer-plugins* from |appcafe|.

:numref:`Figure %s <lmediapl1>` shows the initial screen for Lumina
Media Player.

.. _lmediapl1:

.. figure:: images/lmediapl1.png
   :scale: 100%

   Lumina Media Player: Play Local Files

Use :guilabel:`View` to toggle notifications or closing the player to
the tray when active. The :guilabel:`Play` button plays all songs in the
:guilabel:`Playlist`. When music is playing, the :guilabel:`Now Playing`
tab becomes active, displaying more icons to *Pause*, *Stop*,
*Play Previous*, and *Skip to Next*. Press *Stop* to disable the
:guilabel:`Now Playing` tab and return to the :guilabel:`Playlist` tab.

While browsing the :guilabel:`Playlist`, you can use the
:guilabel:`Plus` and :guilabel:`Minus` buttons to add and remove songs
from the list. Use the :kbd:`Arrow` keys to reorder songs in the list.
There are also :guilabel:`Cross Arrows` and :guilabel:`Circular Arrows`
icons to *Randomize* and *Auto-Repeat* the playlist, respectively.

To enable Pandora streaming functionality, install the *pianobar*
utility from |appcafe|. Once installed, restart Lumina Media Player to
enable the :guilabel:`P` icon. Click it to switch to Pandora streaming,
seen in :numref:`Figure %s <lmediapl2>`.

.. _lmediapl2:

.. figure:: images/lmediapl2.png
   :scale: 100%

   Lumina Media Player: Pandora Settings

The :guilabel:`Settings` tab has a number of options for configuring
your Pandora stream.
You can log in to your account or click :guilabel:`Need an account?` to
create a new Pandora account. There are also options to adjust
*Audio Quality*, *Audio Driver*, and add *Proxy URLs*. Be sure to click
:guilabel:`Apply Settings`. If the account information is valid, the
:guilabel:`Now Playing` tab activates, seen in
:numref:`Figure %s <lmediapl3>`.

.. _lmediapl3:

.. figure:: images/lmediapl3.png
   :scale: 100%

   Lumina Media Player: Pandora Now Playing

The :guilabel:`Now Playing` tab offers a very basic Pandora interface,
displaying the current song and station, and offering options to *like*
songs, prevent a song from playing for a month, *ban* songs, and view
more *details* about a song. You can also use the :guilabel:`Plus` and
:guilabel:`Minus` icons to add or remove new radio stations.

.. index:: Notify
.. _luminanotify:

lumina-notify
=============

:command:`lumina-notify` is a CLI-only utility designed to create simple
QT dialog windows to improve user interactivity. When used in a shell
script, :command:`lumina-notify` launches QDialogs. Here is the syntax:
:command:`lumina-notify [msgtxt] [accptbtntxt] [rjctbtntxt] [wndwttl]`.

Save this example and run it to see the full output:

.. code-block:: none

 #!/bin/csh
 set a=`./lumina-notify "Did Jar Jar do anything wrong?" Yes No "Question"`
 if ($a == 1) then
 set b=`./lumina-notify "Are you sure?" Yes No "Are you Sure?"`
 if ($b == 1) then
 ./lumina-notify "Please stop being a hater." Ok Ok "Haters gunna hate"
 else
 set c=`./lumina-notify "Thank you for changing your mind" OK OK "You're Awesome"`
 endif
 else
 ./lumina-notify "High Five for Darth Jar Jar" Sure OK "Respect"
 endif`

.. index:: Xconfig
.. _Xconfig:

Xconfig
=======

The :command:`lumina-xconfig` utility is a graphical front-end to the
:command:`xrandr` command line utility. It provides the ability to probe
and manage any number of attached monitors. To start this utility,
right-click the desktop and select
:menuselection:`Preferences --> Display` or type
:command:`lumina-xconfig` from a terminal window. This opens a screen
similar to the one shown in :numref:`Figure %s <lumina15>`.

.. _lumina15:

.. figure:: images/lumina15b.png
   :scale: 100%

   Configuring Monitors

In this example, two display inputs are attached to the system and the
resolution for the selected input is displayed. If the display
input supports multiple resolutions, these all appear in the
:guilabel:`Resolution` drop-down menu to select a different resolution.

Underneath the :guilabel:`Resolution` drop-down menu the user is able
choose the orientation of their screen. This may prove useful if the
user orients their monitor vertically or upside down. Also, the user can
make the selected input the primary screen by checking the Primary
Screen box.

If another display is attached, the :guilabel:`Add Screen` tab is
activated. On this tab the user can configure the new input resolution
as well as make it the new system default.

Within the area the displays are listed, the user is able to drag each
display. The arragement of the displays affect which borders switch
between monitors.

Located in the top right of the window are two buttons. The top
button refreshs the connected displays. The button below it
disables the selected input.

The user is able to create several profiles. To create profiles, apply
the appropriate settings and select "New Profile" from the
:guilabel:`Save` drop-down menu. It then prompts the user to enter a
name for the profile.

.. index:: xdg-entry
.. _xdgentry:

XDG-Entry
=========

This Qt5 utility generates :file:`.desktop` files and places them in the
user's home directory (:file:`/usr/home/[username]`). Be sure to copy
these files to the default location the operating system searches for
:file:`.desktop` files. As :numref:`Figure %s <xdgentry1>` shows, there
are numerous configurable elements:

.. _xdgentry1:

.. figure:: images/xdgentry1.png
   :scale: 100%

   .Desktop Creator (XDG-Entry)

**Name:** The specific name of the new :file:`.desktop` file.

**Generic Name:** This text in this field displays as a tooltip (when
enabled).

**Comment:** Adds more descriptive text to the
:guilabel:`File Information`.

**Keywords:** Simple word associations for the file.

**Executable:** Click :guilabel:`Select` to open the file browser and
choose an application to associate with this file.

**Icon:** Click :guilabel:`Select` to open the file browser and choose
an icon file to associate with this file.

**Categories:** Choose the category for this file.

**Run in Terminal:** Select this to open the file with the default
terminal application.
