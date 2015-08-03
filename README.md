**8 June 2015: GoogleCL is currently broken due to the OAuth1 turndown, and likely to remain so. Thanks for your support over the years, and apologies for the lack of prior notice.**

GoogleCL brings Google services to the command line.

We currently support the following Google services:

-   **Blogger**

-   **Calendar**

<!-- -->

-   **Contacts**

<!-- -->

-   **Docs**

<!-- -->

-   **Finance**

<!-- -->

-   **Picasa**

<!-- -->

-   **Youtube**

Check out the [Manual](/p/googlecl/wiki/Manual) and [ExampleScripts](/p/googlecl/wiki/ExampleScripts) for many more examples of what you can do, or the [Install](/p/googlecl/wiki/Install) page for simple install instructions.

### News[](#News)

**3/31/11:** I just realized I should've waited for April 1st, and released version 1.0. Missed opportunities. The good news is, 0.9.13 contains some much needed improvements on 0.9.12, namely:

-   Appropriate intermediate directories are created for authentication tokens.b
-   Deletion of recurring Calendar events actually deletes events, rather than crashing.
-   File extensions for Picasa do not have to be lowercase.

**1/21/11:** Keeping with the theme of inappropriate version numbers, 0.9.12 is finally out! Are the following features worth the wait?

-   Google Finance support (thanks, bartosh!)
-   Expanded usage of --date
-   --access option for privacy settings
-   Reading options and arguments from stdin

If not, you should read the changelog for the rest of the updates. And if the answer is still no... then I apologize. You may have noticed that development has slowed drastically. Unfortunately, GoogleCL is now a 100% free-time project for everyone involved. We're still working on it, though, so keep those bug reports and feature requests coming!

**10/10/10:** .deb file is up, sorry for the delay. The Windows machine I used to make the executable was apparently 64-bit, and so it play nice on 32-bit systems. I've marked it as such in the downloads page, and a 32-bit version will be up tomorrow with any luck. Thanks for your patience!

**10/8/10:** 0.9.11 makes its appearance. Don't miss our wonderful new features:

-   Much better unicode support.
-   More natural specification of command line arguments.

And Windows users, rejoice: this version reintroduces the .zip file containing an executable. A .deb file should be forthcoming this weekend. In that vein, maybe someday soon I'll get GoogleCL properly situated into the various software repositories.

**9/3/10:** 0.9.10 is out! Projecting off Gmail and the current rate of releases, we'll be out of "beta" with 0.9.65 or so. Be sure to check out

-   v2/v3 support for Docs and Contacts. Manipulate arbitrary uploads, list many more details of your contacts.
-   Support for non-latin alphabets
-   Adheres to XDG base directory specification

This release may be more unstable than past ones. Be sure to (responsibly) flood the issue tracker with any oddities you encounter.

**7/28/10:** Uploaded 0.9.9 tar and deb. Windows exe will be up once the Windows machine is found and unpacked.

Highlights for this release include

-   Download and edit of new-version Google Docs
-   Video upload and download for Picasa
-   --owner option, allowing use of Picasa collaborative albums, listing other user's YouTube uploads, etc.
-   Reminders for added calendar events

**6/30/10:** Uploaded 0.9.8 tar, deb, and zip with Windows exe. In the most inappropriately numbered version release to date, this release includes:

-   Proper login procedure for Apps users
-   setuptools support
-   Uploading directory trees to Docs
-   Multiple-calendar tasks

and a whole lot of other stuff. Huge, huge thanks to our growing list of contributors!

**6/20/10:** Uploaded 0.9.7 .tar.gz and .deb packages. Keeping fingers crossed for inclusion into debian and then ubuntu. 0.9.7 adds command history to interactive mode, changes the --date semantics for calendar, and adds list-groups, add-groups and delete-groups features to contacts. Plus some miscellaneous bugfixes. Thanks in particular to ericvw and aripollak who contributed patches!

**6/19/10:** Wow! What an announcement! Thanks to everyone who's been checking out GoogleCL, and special thanks for the dozens upon dozens of new issues in the tracker.

**Older** You can now grab a Debian/Ubuntu/etc. package or gzipped tar archive of GoogleCL! Check the Downloads tab.

### Development / Contributing[](#Development_/_Contributing)

The more the merrier. Check out the wiki page on [contributing](/p/googlecl/wiki/Contributing).

### Dependencies[](#Dependencies)

The [gdata-python-client library](http://code.google.com/p/gdata-python-client/).
