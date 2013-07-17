#Installation:

1. **Copy** mongo.so to /Applications/MAMP/bin/php/php5.x.x/lib/php/extensions/no-debug-non-zts-200xxxxx (Channge 5.x.x to your PHP version)
2. Add **extension="mongo.so"** to the end of php.ini (Open MAMP click on File → Edit Template → PHP → PHP 5.x.x php.ini) (Channge 5.x.x to your PHP version)
3. **Restart** MAMP.

##Dependencies:
mongodb (brew install mongodb)

##Change Log:
* 0.1 - Initial Release