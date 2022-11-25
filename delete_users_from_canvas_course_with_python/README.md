* Date: 2022-11-25
* License: [GPLv3](https://www.gnu.org/licenses/gpl-3.0.en.html)
* Author: Tim Visser of the Vrije Universiteit Amsterdam
* Use at your own risk :)
* Version: 2022-11-25T09:57
* Download here the newest version: https://edu.nl/yaggu

This uses:

* [Canvas LMS](https://www.instructure.com/canvas)
* [CanvasAPI](https://canvasapi.readthedocs.io/en/stable/getting-started.html)
* Jupyter Notebook. [Project Jupyter | Home](https://jupyter.org/)

# Working

In this code you can provide a list with studentnumbers, so they will be automatically removed from a Canvas Course.

As and example you can remove al 2022-2023 registered students with a certain programme code from SAP (or from another source). 

Put all those student numbers into the Python list (in the code called called `listOfStudents`).

If the code runs, it takes all students out of Canvas course that are NOT in the list (and thus are not registered for 2022-2023) from de canvas course.
