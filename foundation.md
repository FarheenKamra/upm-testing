Prepare the foundation

Here are a few rules and resources you'll need to get started.

Naming your module

UPM attempts to follow a clear naming pattern.

Modules should be sensibly named and then placed in ${libdir}/upm and
headers in ${includedir}/upm.

All modules should be prefixed with libupm-. The upm\_module\_init will
automatically name python UPM modules as pyupm\_ and javascript modules
as jsupm\_.For example for src/grove/ the library built will be
libupm-grove. so, the python module pyupm\_grove and the js module
jsupm\_grove.

• Pick a name. Typically picking the name of the chip of your sensor or
actuator makes the most sense. Try to pick a generic name so people with
a similar sensor can inherit your class if they only have minor changes.

• Use the name and stick to it.

• Your lib must belong to the UPM namespace.

• Avoid brand names. Often your module can be very generic with little
effort.

• Use only lowercase characters in your file names and folder names.

Include a license (preferably MIT)

You must license your module under a FOSS license. The recommended
license is MIT but any permissive license is fine. Please consider that
people using UPM may want to write proprietary programs with your
sensors so we like to avoid GPL. If your license is not MIT please
include a LICENSE file in src/mymodule/

The top of each source file must contain a comment block containing the
license information.

Choosing the MIT license is preferred for the UPM repository. Below is
the comment block needed at the top each source file. For your
convenience, it’s here for you to cut and paste.
