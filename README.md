# SunXP
Windows XP Luna theme clone for ReactOS

https://jira.reactos.org/browse/CORE-14639

# Building
You can build this by creating a new directory in your [ReactOS](https://github.com/reactos/reactos) source. Navigate to reactos/Resources/Themes and create a new directory called "SunXP" (caps matter). Copy the contents of this repository there, reconfigure your ROSBE (flush all CMake cache). Next up [follow these steps](https://www.reactos.org/forum/viewtopic.php?f=4&t=16999&sid=f91aa6dcaad9d7e9de00bd21f1164a27), once you're done with it, try to build it using `ninja SunXp.msstyles`
