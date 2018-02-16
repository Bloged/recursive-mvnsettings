recursive-mvnsettings
=====================

Alias `mvn` to use closest `settings.xml` file in parents directory instead of default one.
Allow to use several 'mvn settings' files without the need to combine them all.

Use case:
---------

Install:
--------

  * Get script file: https://raw.githubusercontent.com/Bloged/recursive-mvnsettings/master/recursive-mvnsettings
  * Copy file somewhere (example ~/.recursive-mvnsettings).
  * Add it to your .bashrc (or other depending on your shell):
    ```echo "source ~/.recursive-mvnsettings" >> ~/.bashrc```
  * Source it for the first run: ```source ~/.recursive-mvnsettings```.

Credits:
--------
Based on [recursive-gitconfig](https://github.com/arount/recursive-gitconfig) by arount
