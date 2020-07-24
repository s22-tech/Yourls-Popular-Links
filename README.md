# Yourls Popular Links

This version:
* is compatible with Yourls 1.7 or higher
* fixes the deprecated function and removes the warning
* formats the code to make it more consistent and prettier

The plugin shows an admin page with the most popular links created in 1, 30, 365, and 1000 days on a YOURLS site.

Download plugin.php, save as plugin.php, and upload to YOURLS_DIRECTORY/user/plugins/popular-links/

IMPORTANT:  Make sure to remove/overwrite any older version of Popular Links, if you've installed it on your server.

Advanced:

At the bottom of the plugin, you can edit the values:

> show_top(1000,5);

1000 means the number of days you are selecting from the database
5 means the number of links you are selecting

** Bonus! Want to show it as a public page?

Save popularlinks.php to the /pages directory of your YOURLS installation
and access it like YOURLS-SITE/popularlinks

As with the plugin, you can customize it by editing it's values.

Please let me know if there's anything else that needs to be fixed, changed, or updated.
