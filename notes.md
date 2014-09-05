## Stories we can tell

* all tests pass - how boooring.
* JMB "I want to build this!"
* Tomek "More tests are coming"
* KR "Lets have fun. Lets build software"

##References

* Nick Barnes. Publish your computer code: it is good enough. Nature 467, 2010, 753.
* Rother, Rother, Puton, Potrzebowski, Wywial, Bujnicki.
* Alyssa Goodman. Ten Simple Rules for the Care and Feeding of Scientific Data. PLOS CompBiol, 2014.
* How science goes wrong, The Economist, 2013.

## packages
After experimenting on several branches, some conclusions:
1. separate test packages with __main__.py, so you can do python test_modifications/
2. import functions/classes a package exports in __init__.py
3. if the number of inter-package dependencies shrinks, the package was thought up well.
4. try to have less lines than before withouth playing golf :-)

## Test Data


    Set an environment variable for your data directory

    Write a small module that you always import that has the sole purpose of having a fixed position relative to your data directory, then call __file__ from there

    Generate the data at runtime

    Store your data in a database rather than a file

    Store your data in a fixed location in the file system rather than a location relative to the package

    Don't run your test code directly



## citable
Making Your Code Citable: https://guides.github.com/activities/citable-code/
http://zenodo.org/