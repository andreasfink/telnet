# telnet

While Apple thinks, nobody needs telnet these days and everybody should use the way more secure ssh, there are many applications
and diagnostic patterns where the telnet client application tool is vital to have. For example to set up an embedded system or
router from scratch which doesn't support ssh before enabling it or where ssh options are incompatible by default. telnet comes
handy there. telnetd can be useful as backend for a front end encryption processor who doesnt want to deal with all the mumbo 
jumbo of presentin login screens and authentication. Another application is to test a SMTP server if its alive simply by doing 
a telnet to its port 25 to see if it answers.

Now since Apple removed telnet as a tool in the latest MacOS highSierra, a replacement has become mandatory for me.
After trying to compile the apple implementation of telnet and getting stuck in too many dependencies, I tried to 
compile the telnet client used in Linux and with very few modification and a Xcode build file, this telnet version
works more or less out of the box.

To make it easier for others, I have uploaded the sources wiht a Xcode project file. A PKG will follow.
