This wiki helps the developer to know more about the project SABARI

# Introduction #

Project SABARI is an initiative by the staff and students of Anna University to develop software tools for the differently abled. The main intention behind SABARI is to help individuals with extreme motor disabilities to operate computers. This idea was inspired from [elocutor](http://sourceforge.net/projects/hawking/), the software used by Prof.Stephen Hawking for his communication.

This document gives an overview of the development of these tools. While some of these are being used by [Vidyasagar](http://www.vidyasagar.co.in/index.html), others are in progress.

# Basic Requirement #
The main requirement is that all operations which are done via keyboard and mouse should be converted to a single mouse click. This conversion can then be translated to a touch-sensor based device (eg., ADITI used by Vidyasagar), wherein the user can operate computer with the help of his finger.

SABARI concentrates on the conversion of keyboard and mouse operations to a single mouse click and customizing thereafter,
based on the feedback from [Vidyasagar](http://www.vidyasagar.co.in/index.html)

Here are some common requirements that should be kept in mind while developing the software.

# Scan Design #

As per the requirement of Software, decide the key-board/ mouse operations (we'll call them keys), which should be included in the interface. Regardless of any software you develop or customize, these requirements are mandatory.

# Modes of Scanning #
**Sequential Scanning**: In sequential scanning, all the keys should be scanned one after the other in a continuous loop. <br />
**Row-wise Scanning**: In row-wise scanning, the keys should be grouped into rows and each row should be scanned in a continuous loop. As the user selects a row, the keys in that row are scanned sequentially. <br />
**Indexed scanning**: In indexed scanning, keys by default should be scanned sequentially. This mode should allow the user to move the mouse and select the required key.

# Color #
The tool you develop may be used by a child with visual impairment. So, do not use grey or light color. Instead, choose some bright colors- Example, yellow with black background.

# Size #
Provide the option for varying the font size. As per [Vidyasagar's](http://www.vidyasagar.co.in/index.html) requirement, font size range can be from 27 - 36 and the style preferably, Times New Roman/ Callibri Body font.

# Time and Speed #
Provide an option to change the speed of the scan with the time range  2 seconds - 10 seconds.

# Sound #
If you are asked to add TTS (text to speech) in your software, as far as possible include Indian accent.

# Programming tools #
Java or Python is recommended. The end product should be a complete executable in both windows and linux platforms.

# Tools with Vidyasagar #

# Math Assistance #

This tool is presently used by Vidyasagar Students, where they learn fundamental mathematics using computer. Three versions are complete and fourth version is in progress.

Developers:
Version 1.0 - Venkatanathan, Venkatakrishnan and Sanath Kumar (B.E. 2010),
Version 2.0 - Muralikumar (MCA 2009),
Version 2.1 - Sarath Kumar (MCA 2010),
Version 2.2 - Vaidyanathan (MCA 2011) - To be used by Vidyasagar.

# Generic Mouse Scan #
The user can open and close files using this interface. The revised version is also available

Developers : Balamaruthu, Mohan P and Naveen Kumar V (B.E 2009)

# Paint your mind #
This is used by Vidyasagar, but more modifications are needed. This tool was adjudged as the best open source project in Software Freedom Day Celebrations 2010.

Source code is available at [http://code.google.com/p/paint-your-mind/](http://code.google.com/p/paint-your-mind).

Developers: Dinakaran and Rajkumar (B.E CSE 2012)

# Chess #
Source code is available at  [http://code.google.com/p/chesschamps/](http://code.google.com/p/chesschamps/).

Developer: Vandana (B.E.CSE 2012)

# Aksharam #

This is an on-screen generic keyboard that works with all applications.

Developers: Abinaya, Krishnapriya and Monisha Nikitha (B.Tech IT 2011)

# Mindmap #

Using this tool, the student will be able to create a mind-map of concepts. This project received a good feedback from Vidyasagar and they might use this tool for writing reports and thesis.

Developer: Sakthivel (MCA 2011)

# Mindtrainer - English and Math #

In a game set up, the student will be able to learn simple arithmetic and english synonyms and antonyms.

Developer: P.Saranya (MCA 2011)

# Eye-Gaze #
This tool is aimed at tracking the eyeball movement, enabling the user to communicate through eyes.

Developers: Sumesh (ME 2009), Tasneem Sultana (ME 2010), Vijay Kumar, Varun Joshi and Taroon (B.E CS2011).