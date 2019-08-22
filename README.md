# AFinePairStats
A userscript that shows A Fine Pair cache stats on geocaching.com. It adds the A Fine Pair banner in the following places:

* the Stats Bar area of your account dashboard (old UI);
* the sidebar of your account dashboard (new UI)
* your public profile, if it doesn't already exist there (old and new UIs);
* other users' profiles, if it doesn't already exist there (old and new UIs);
* A Fine Pair cache pages.

On cache pages it adds the C. O.'s banner as well.

This script was inspired by, and is based on, James Inge's [Church Micro Stats](https://greasyfork.org/en/scripts/9641-church-micro-stats) and works in concert with it, as you can see from the screen shots. Thanks and credit should go to James for his efforts.

__Please note:__ in order for the banner to be added to your public profile, you need to have some content in the "Bio" area (old UI) or About tab (new UI). If this area is empty, the necessary container is not generated by the site. An empty HTML comment (&#60;!-- --&#62;) is sufficient and prevents the need for unwanted output in your profile. This is also true for James' Church Micro Stats. This may be fixed in a later version.

__Update:__ This should no longer be true in the new UI.

## Version History

### Version 0.0.1

* Initial release.
