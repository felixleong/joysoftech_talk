#######################################################
Joys of Tech: Discovering Your Calling in a Tech Career
#######################################################

This repository contains the slide deck and speaker notes for my talk,
presented to UTAR students on 13 July 2015.

This talk is licensed under a `Creative Commons Attribution-ShareAlike 4.0
International License`_.

######################
Reusing the Slide Deck
######################

As per the license of the talk, feel free to remix the slide deck and use it as
your own, only condition being that:

1. My work is attributed
2. Share your remixed work for the benefit of others :)

Instruction
===========
To generate your slide deck and speaker notes, perform the following:

1. The primary file to edit is the `index.rst` file in this folder, which
   would be used to generate both the slide deck and the speaker notes.
2. To create the slide generation, first create a Python virtual environment

   .. code-block:: bash

       $ virtualenv .env
       $ source .env/bin/activate  # perform this in subsequent modifications

3. Install the dependencies

   .. code-block:: bash

       $ pip install requirements.txt

4. Use the following to generate all the stuff :)

   .. code-block:: bash

       $ make html
       $ make slides

.. _Creative Commons Attribution-ShareAlike 4.0 International License: http://creativecommons.org/licenses/by-sa/4.0/
