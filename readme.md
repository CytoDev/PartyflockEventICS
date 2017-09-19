# PartyflockEventICS
This script is meant to be used in combination with a userscript in order to
correctly function. If you don't have a userscriptt plug-in installed now would
be a good time to look for one you like.

## Usage:
Link to this file (either from the master branche, or a version tag) inside your
userscript in order to use the functionality provided. To start parsing the
event page you will first need to pass the "#party-header" element to the
`parseHeader` function in order to get the event's title. After getting the
title, the next logical step would be to get the start and end times of the
event. The location can be found in ".party-info", and the line-up/timetable can
be found in "#lineup".

### License:
This project is licensed under the MIT License. You can find a copy of the
license [here](https://github.com/CytoDev/PartyflockEventICS/license.md).

### Contributions:
You are more than welcome to submit issues as well as feature requests or just a
'how-ya-doin' in the [issue tracker](https://github.com/CytoDev/PartyflockEventICS/issues/new).
Contributing to the project can be done by forking it and submitting a pull
request once it's all tested and tidy.
