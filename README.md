# root-style
CSS typography style guide to help configure initial css styles when referencing external libraries

# What i'm trying to accomplish:
Whenever I start a web project that includes 3rd party libraries containing their own css files, I wanted a guide/file formatted with classless HTML root tags used in common scenarios. 
I use this to view how libraries effect general typography. Then as I'm building the project I refer back to this whenever I make adjustments effecting typography. 
A file that provides reference to not only size, color and line-spacing, but spacing between subsequent and nested tags.    

Additionally I use it to store my projects color palette and font based iconography references/nomenclature (e.g. fontawesome).

# You can help:
My only wish is to keep this project under one roof with users submitting suggestions for enhancement instead of creating your own repo. If you find value in the "concept of what I am trying to accomplish" please support its enhancement. This is a work in progress and I am open to suggestions. :D
When submitting an enhancement(issues), please articulate your reasoning. 

# How do I use it:
There is no one way but I copy the root-style directory to the root of my project. Then within the index.html file reference all the same css/js library files as my project being carefully to mirror their ordering. I create a lib-overrides.css file where I duplicate a libraries css and only modify the specific attribute that needs changing. 

A note about referencing. An externally referenced library may offer URLs that always serve the latest version. In my practice I prefer to not go this route so as to mitigate potential issues of a library releasing an update that (unbeknownst to me) contains conflicting or unaccounted styling updates that may effect layout.
Instead I either use a URL reference that is version specific(if available) or download and serve my own copy. My goal is to establish a fixed 'known' version of a library and only update on my watch.

# Into the future:
Eventually I would like create files that include HTML configuration (AND classes) specific to a framework. (e.g. bootstrap's panels, modals, etc.)
e.g.
  index.html
  bootstrap_4.1.html
  foundation_5.html
  angular_6.html


Thanks for your suppport
