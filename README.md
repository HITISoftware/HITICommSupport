# HITICommSupport
Arduino support library for HITIComm library.
<br>

Optimized for working with HITISoftware products (https://hitisoftware.com, Tahiti Robotics SARL):
* HITIPanel: GUI for Arduino projects, serial plotting and logging, GUI for Eeprom, control with keyboard
* HITIBrain: Arduino control from Emotiv EEG headsets
<br>

# Support library
HITIComm is an open-source library but it requires a large amount of Arduino program memory (15kB).
To speed up compilation, it is supplied pre-compiled to users.
However, the compiled file called "libHITIComm.a" is processor architecture-dependant (atmega328p, cortex-m0plus,...) and not board dependant.
And HITIComm uses many board-dependant macros that can only be resolved at compile time.
The job of HITICommSupport is to resolve those macros before they are used by HITIComm.
<br>

# Documentation
You can the reference documentation of HITIComm library at https://hitisoftware.freshdesk.com/support/home
<br>

# Contributing
Here is the info on how you can contribute in various ways to the project: TO DO
<br>

# Licenses
Copyright © 2021 Christophe LANDRET

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
<br><br>
You may obtain a copy of the License at http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.

See attached LICENSE file.