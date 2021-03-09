# INFORMATION #

Limit number of Threads (1.1) for MyBB 1.8
Created by: Starpaul20
Copyright: ©2009
License: GPL

Allows Administrators to limit the number of threads that users in a specific usergroup can post in a day. If a user reaches the limit (set as a usergroup permission) they will receive an error telling them they've reached their daily thread limit.

The usergroup permission are located under the 'Posting/Rating Options?' section of the 'Forums and Posts' tab when editing a usergroup.

This plugin offers full language support.

The 'oldrelease' branch contains the 1.6 version of the plugin.


# INSTALLATION #

1. Upload all files above, keeping the file structure intact.
2. Go to Configuration > Plugins
3. Click "Activate"
4. Enjoy!

# UPDATING #

If you're updating from any previous version, you must first deactivate the plugin, upload all new files and reactivate.

# Changelogs

1.1 (February 22nd, 2015)
- Added PostgreSQL and SQLite support
- Using generate_numeric_field function
- Changed (int)$mybb->input to $mybb->get_input

1.0 (September 2nd, 2014)
- Updated plugin to work with MyBB 1.8

## Version number reset for MyBB 1.8 ##

2.0.3 (October 22nd, 2013)
- Bug: Fixed language error for 1.6.11

2.0.2 (November 25th, 2011)
- Dropped MyBB 1.4 support
- Updated plugin with 1.6.5 plugin system updates
- Optimization and general plugin updating

2.0.1 (August 30th, 2010)
- Bug: Fixed bug causing 'Max Threads allowed Per Day' field to appear in several other sections of the Admin CP

2.0 (August 4th, 2010)
- Updated plugin to work with MyBB 1.6

1.0.1 (January 14th, 2010)
- Updated location of Usergroup setting

1.0 (November 9th, 2009)
- Initial release
