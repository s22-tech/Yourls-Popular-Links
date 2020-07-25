# Yourls Popular Links

This version:
* is compatible with Yourls 1.7 or higher
* fixes and removes the deprecated function warning
* formats the code to make it more consistent and prettier
* compatible with PHP 7.4

The plugin shows an admin page with the most popular links created in the last 1, 30, 365, and 1000 days on a YOURLS site.

Download plugin.php, save it as plugin.php, and upload it to YOURLS/user/plugins/popular-links/

*IMPORTANT:  Make sure to remove/overwrite any older version of Popular Links, if you've installed it on your server.*

Advanced:

At the bottom of the plugin, you can edit the values, e.g.:

> show_top(1000, 5);

* 1000 means the number of days you are selecting from the database
* 5 means the number of links it will show

**Bonus! Want to show it as a public page?**

Save popularlinks.php to the YOURLS/pages directory of your Yourls installation
and access it like: www.YOURLS-SITE/popularlinks

As with the plugin, you can customize it by editing it's values.

Please let me know if there's anything else that needs to be fixed, changed, or updated.

###### Definitions
* YOURLS (in all caps) means the directory where you installed Yourls.
* YOURLS-SITE means the URL to access your Yourls install in a browser.
