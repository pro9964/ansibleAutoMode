# AutoMode

An app that Automates certain things in set intervals. Though dead simple, quite popular with more than 40 000 downloads 2009-2015.


# Build and run

To build from source with ant, type:

    ant run

This will compile the source files, make an executable jar file and run that.

You can of course import into Eclipse and run from there as well without ant.

# Usage

From a standalone jar file, simply run:

    java -jar pmd-test.jar

If you want to run without a gui:

    java -jar pmd-test.jar -nogui

If you want to set an interval from the command line, e.g. 10 seconds:

    java -jar pmd-test.jar -interval 0:0:10

