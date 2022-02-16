# portlock, find an unsed tcp port and 'lock' it

'portlock' finds an unused tcp port and save it to a user-specified file. It also avoids conflict with any other users/processes as long as they use 'portlock' too. The lock is implemented as /tmp/portlock.PORT.

## Installation
```
wget https://raw.githubusercontent.com/daimh/portlock/master/portlock
chmod +x portlock
mv portlock ~/bin/ # or any directory in PATH
```

## Examples
```
portlock myport		#find a port
portlock -r myport	#release the port
```

## Help
```
portlock -h
```

## Contribute

Contributions are always welcome!

## Copyright

Developed by [Manhong Dai](mailto:manhongdai@gmail.com)

Copyright © 2022 KLA Corporatio

License [GPLv3+](https://gnu.org/licenses/gpl.html): GNU GPL version 3 or later 

This is free software: you are free to change and redistribute it.

There is NO WARRANTY, to the extent permitted by law.

## Acknowledgment

Sohail Nadimi, Senior Engineer, KLA

Raghuram Bondalapati, Manager, KLA

Vijay Ramachandran, Director, KLA
