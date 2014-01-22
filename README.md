<<<<<<< HEAD
Gabencoin integration/staging tree
================================

http://www.gabencoin.org

Copyright (c) 2009-2013 Bitcoin Developers
Copyright (c) 2011-2013 Gabencoin Developers

What is Gabencoin?
----------------

Gabencoin is a lite version of Bitcoin using scrypt as a proof-of-work algorithm.
 - 2.5 minute block targets
 - subsidy halves in 840k blocks (~4 years)
 - ~84 million total coins
=======
Greetings brothers and sisters,

I write this message under a new anonymous account, as the words I am about to speak may have a great affect on all of us and the public at large.  

Recently I have returned from the kingdom of Valve.  Seven days ago, I joined in the holy festivities known as Steam Dev Days in the land of Seattle.  On the morn of the first day of this cataclysmic event, the great lord Gaben descended from the heavens and addressed the multitude.  He said “Let there be Steam Controllers” and then as if by magic, Steam Controllers appeared in our hands.  

On the second day of these divine activities, the great lord Gaben said “Let there be Steam Machines” and every person in attendance received Steam Machines to play with.  He awarded all of us ceremonious gifts of Steam Machines and Steam Controllers, that we might go forth and experiment.  

The great lord even awarded me and seventy-six others the chance to experience his glorious virtual reality prototype, a device of such splendor and magic that not even the holiest of holies were allowed within the sacred walls of the demo room to witness it.  Praise be to Gaben!
>>>>>>> 16031942d3d9369bc02280dfaf1fc2c5e272b933

But none of these moments are what brings me to write this letter. 

<<<<<<< HEAD
For more information, as well as an immediately useable, binary version of
the Gabencoin client sofware, see http://www.gabencoin.org.

License
-------

Gabencoin is released under the terms of the MIT license. See `COPYING` for more
information or see http://opensource.org/licenses/MIT.

Development process
-------------------

Developers work in their own trees, then submit pull requests when they think
their feature or bug fix is ready.

If it is a simple/trivial/non-controversial change, then one of the Gabencoin
development team members simply pulls it.

If it is a *more complicated or potentially controversial* change, then the patch
submitter will be asked to start a discussion (if they haven't already) on the
[mailing list](http://sourceforge.net/mailarchive/forum.php?forum_name=bitcoin-development).

The patch will be accepted if there is broad consensus that it is a good thing.
Developers should expect to rework and resubmit patches if the code doesn't
match the project's coding conventions (see `doc/coding.txt`) or are
controversial.

The `master` branch is regularly built and tested, but is not guaranteed to be
completely stable. [Tags](https://github.com/bitcoin/bitcoin/tags) are created
regularly to indicate new official, stable release versions of Gabencoin.

Testing
-------

Testing and code review is the bottleneck for development; we get more pull
requests than we can review and test. Please be patient and help out, and
remember this is a security-critical project where any mistake might cost people
lots of money.

### Automated Testing

Developers are strongly encouraged to write unit tests for new code, and to
submit new unit tests for old code.

Unit tests for the core code are in `src/test/`. To compile and run them:

    cd src; make -f makefile.unix test

Unit tests for the GUI code are in `src/qt/test/`. To compile and run them:

    qmake BITCOIN_QT_TEST=1 -o Makefile.test bitcoin-qt.pro
    make -f Makefile.test
    ./gabencoin-qt_test
=======
Something far greater took place at the holy Steam Dev Days.  Something no one else witnessed, something no one else experienced.  

On the first day, as our holy father Gaben addressed the multitude, something strange and incredible occurred.  I was in very close proximity to the great lord, and as he was speaking, all of the sudden he made direct eye contact with me from his mighty throne! The vast auditorium of people disappeared as I was engulfed in a pattern of glorious light and bright clouds.  The lord Gaben’s voice boomed out over the blinding void and spoke directly into my soul:
>>>>>>> 16031942d3d9369bc02280dfaf1fc2c5e272b933

“Let there be a new world currency, that we may bring goodness and righteousness unto the Earth and eliminate console peasantry once and for all.  This currency shall henceforth be known as Gabencoin.  Now go forth, child, spread this divine word to all our people.  In my name it shall be done.”
