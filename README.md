# SunXP
Windows XP Luna theme clone for ReactOS

https://jira.reactos.org/browse/CORE-14639

# Building
You can build this by creating a new directory in your [ReactOS](https://github.com/reactos/reactos) source. Navigate to reactos/Resources/Themes and create a new directory called "SunXP" (caps matter). Copy the contents of this repository there, reconfigure your ROSBE (flush all CMake cache), and build it using `ninja sunxp.msstyles`. And do not forget to add that path to `boot/bootdata/packages/reactos.dff.in`. Then also add it to the `dir_to_num macro` in `sdk/cmake/CMakeMacros.cmake` (using the number you assigned).
