This directory contains nodejs reimplementations of two mail utilities
from the dawn of time.

from prints the from address and subject of the most recent 20
messages in my inbox. You'll need to edit the top of the script to use
your IMAP login details, because surely your email address isn't
root@gmail.com.

biff prints a little about each new message that arrives, until you
interrupt it with control-c. Again, your email address isn't
root@gmail.com so you'll need to edit it a little.

I wrote from using nodejs and
[node-imap](https://github.com/mikebevz/node-imap)
in order to test a pull request I wrote and... well, I don't know
really, perhaps I wrote biff just because I was in the right mood.
