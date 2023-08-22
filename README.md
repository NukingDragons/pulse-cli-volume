# pulse-cli-volume
A simple bash script to control the volume of pulse audio sinks

# Usage
```
Usage: volume [client] [options]
 Client:
  client		This can be either the ID or the case-sensitive name of the sink, or the below option
  --default,-D		Automatically determine the default sink and use it as the client
 Options:
  --help,-h		print this usage and exit
  --list,-l		Lists all of the clients available to control
  --setdefault,-sd	Assign the client to be the default sink
  --set,-s		Sets the volume percentage for a given client
  --get,-g		Gets the volume percentage for a given client
  --mute,-m		Sets the mute flag for a given client
  --unmute,-um		Unsets the mute flag for a given client
  --togglemute,-tm	Toggles the mute flag for a given client
  --checkmute,-cm	Gets the status of the mute flag for a given client
  --setraw,-sr		Sets the raw volume number for a given client
  --getraw,-gr		Gets the raw volume number for a given client
  --increment,-i	Increments the volume for a given client by a given percentage
  --decrement,-d	Decrements the volume for a given client by a given phercentage
```
