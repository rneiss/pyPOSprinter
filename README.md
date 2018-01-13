You need pySerial and PIL (Python Image Library) for pyPOSprinter to work. On Debian/Ubuntu:  
`apt-get install python-serial python-imaging`

See example.py for an example of how to use pyPOSprinter. For more information simply import pyPOSprinter and see the help:
```
from pyPOSprinter import pyPOSprinter
help(pyPOSprinter)
```

The code is tested to work with the following printers (but may very well work on many others):
NCR RealPOS 7197
Epson TM-T88IIIP/M129C

pyqrnative (SVN revision 3) is included in order for you to get quickly started with pyPOSprinter and QR-codes. You may download the newest version from the main website: http://code.google.com/p/pyqrnative/
