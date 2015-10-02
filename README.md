# Calconnect Testing Data Repository
This repository contains various bits of testing data valuable to client and server vendors.

## iCalendar data files
The files in the [`badics`](badics/) directory can be used to verify that an
[iCalendar](http://tools.ietf.org/html/rfc5545) library is gracefully handling
broken ics found on the web or generated through a broken library implementation.

Similarly, the [`goodics`](goodics/) directory files contain valid
[rfc5545 iCalendar](http://tools.ietf.org/html/rfc5545) data that can be used
to verify correct implementation of your parser.

If you would like to contribute to this collection, please send us a pull
request after you have checked if a similar case isn't already in the
repository. Give the file a name that gives a good summary of what case the
file describes and use the commit message for a more verbose description.
