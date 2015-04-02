# Update Site #
http://plaidannotations.googlecode.com/svn/trunk/PlaidAnnotationsUpdateSite/

# Introduction #
In order to make the PLAID annotations as easy to use as possible, we have packaged the PLAID annotations as an Eclipse plugin. This makes it so that you can easily add the PLAID annotations as a "Library" to your Java project (similar to how JUnit4 annotations work). It also enables us to provide Eclipse QuickFix suggestions if you attempt to use any of the PLAID annotations.

However, most plugins that actually use the PLAID annotations will already depend on the PLAID annotation project either directly or indirectly, and so you won't normally have to download the PLAID annotations plugin manually. Nonetheless, here are the three ways you can install the PLAID annotations, in order from most to least preferable:

# Details #
  * **Install from Update Site:** You can manually install the PLAID annotations plugin from its Eclipse update site: http://plaidannotations.googlecode.com/svn/trunk/PlaidAnnotationsUpdateSite/
  * **Use the Jar:** If you don't want to use the PLAID annotations as a plugin, you can just stick the Jar file itself somewhere in your program's build/class path. Download it [here](http://code.google.com/p/plaidannotations/downloads/list).