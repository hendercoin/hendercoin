Hendercoin (HDC) - a better version of Litecoin which also uses scrypt as a proof of work scheme and is intended for microtransactions.
 - 1 minute block targets
 - 1,041,379,200,000 total coins (Number of milliseconds since Cal's birth, from Jan 17, 2014)
 - 579,000,000 coin reward per block (number of pets Cal has collected in World of Warcraft * 1 million), halves every 888 blocks
 - difficulty updates every 4 hours
 - currently peers are looked up over IRC only
 - currently no block checkpoints are in the code (but could be easily
   added)

This coin has not had a genesis block created, and will not work yet!

Development process
===================

Developers work in their own trees, then submit pull requests when
they think their feature or bug fix is ready.

The patch will be accepted if there is broad consensus that it is a
good thing.  Developers should expect to rework and resubmit patches
if they don't match the project's coding conventions (see coding.txt)
or are controversial.

The master branch is regularly built and tested, but is not guaranteed
to be completely stable. Tags are regularly created to indicate new
official, stable release versions of Litecoin.

Feature branches are created when there are major new features being
worked on by several people.

From time to time a pull request will become outdated. If this occurs, and
the pull is no longer automatically mergeable; a comment on the pull will
be used to issue a warning of closure. The pull will be closed 15 days
after the warning if action is not taken by the author. Pull requests closed
in this manner will have their corresponding issue labeled 'stagnant'.

Issues with no commits will be given a similar warning, and closed after
15 days from their last activity. Issues closed in this manner will be 
labeled 'stale'.
