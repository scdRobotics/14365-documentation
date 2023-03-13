Downloads
=========

.. _androidstudio:

Android Studio
--------------
Android Studio is the IDE (Integrated Development Environment) that you will do a vast majority of your standard programming in. It is a very powerful tool that checks syntax as you code and allows you to connect with the Control Hub on the robot, which then runs the programs.

The latest installation executable (with a guide built in) can be found `here <https://developer.android.com/studio>`_.

.. _githubdesktop:

GitHub Desktop
---------------
GitHub Desktop is a Git application which makes managing version control much easier. While Android Studio has a built in Git application, I prefer GitHub Desktop for its simplicity, which tends to help avoid breaking workflows.

The latest installation executable (with a guide built in) can be found `here <https://desktop.github.com/>`_. You will need to create a GitHub account before proceeding!

.. _ftcsdk:

FTC SDK
-------
The FTC SDK is the Android App that runs on the Control Hub that interacts with your code to transform it into executable robot functions.

You can download a ZIP file of the current version `here <https://github.com/FIRST-Tech-Challenge/FtcRobotController>`_ under the Releases tab to the right. It is important to keep this updated whenever a new major version is released in order to pass field inspection.

.. _outsidelibraries:

Outside Libraries
-----------------
We utilize several outside libraries which build on the capabilities of the base SDK. Currently, we utilize the following libraries, each of which has a setup guide on the listed link:

- `EasyOpenCV <https://github.com/OpenFTC/EasyOpenCV>`_ for greatly enhanced webcam functionality and customizability. 
- `EOCV AprilTag Plugin <https://github.com/OpenFTC/EOCV-AprilTag-Plugin>`_ to allow detection of `AprilTags <https://april.eecs.umich.edu/software/apriltag>`_.
- `Roadrunner <https://github.com/acmerobotics/road-runner>`_ for vastly improved control of drivetrain movements. I would stay away from the 1.0 beta release and stick with whatever the most current 0.x.x version is, as these are more widely used and tested as stable (with the added bonus of not breaking our current functions). I also would reccomend following `this <https://learnroadrunner.com/installing.html#method-2-installing-rr-on-your-project>`_ install guide, as it is overall much simpler and more clear.

There are, of course, many additional libraries beyond these that you may find usage in, the primary one being `OpMode Tuner <https://github.com/OpenFTC/FTC-OpMode-Tuner>`_. I have strayed away from this due to build stability concerns and the fact that I prefer the more widely tested FTC Dashboard (a library built within the Roadrunner install which allows changing variables and outputting graphs) interface, even though admittedly, FTC dashboard is slower to make changes with. All this apart from the fact that inputs like these can be handled just as well by the gamepads. However, it is certainly a resource that you are free to explore, just at your own risk.

.. _revhardwareclient:

REV Hardware Client
-------------------
REV Hardware Client is the easiest way to make sure your Control Hub, Expansion Hub, and Driver Station firmwares are up to date. Simply plug each of these into your computer while the software is running, and you can ensure you are running the most recent and competition legal versions in order to pass field inspection.

The latest installation executable (with a guide built in) can be found `here <https://docs.revrobotics.com/rev-hardware-client/getting-started/installation-instructions>`_.
