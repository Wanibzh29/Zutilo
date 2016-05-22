* In version 2.0.1:

    + Fix bug that made Zutilo not work at all in Zotero Standalone

* In version 2.0.0:

	1. New function: copy attachment paths to clipboard
	2. Many compatibility fixes for Zotero 5.0

* In version 1.4.0:

    1. Shortcuts for attaching stored files and URI links
    2. Sort shortcuts by category
    3. Hide most item menu functions by default

* In version 1.3.0:

  - New features

	1. New shortcuts/menu items:
		- Copy Zotero select link
		- Copy Zotero URI
	2. New shortcuts:
		- Focus collections, items pane, and various item pane tabs
		- Attachments: recognize PDF, create parent item, and rename from parent
		- Toggle visiblity of collections and item pane
	3. New remove tags function
	4. Create book item from book section item and vice versa
	5. Move notes/attachments from one item to another

  - Bugfixes

	1. Fix bug in relating items 
	2. Fix item saving toolbar menu items and keyboard shortcuts 
	3. Minor fix for handling different attachment types correctly. 
	4. Preferences window bug fix
	5. Update the Save to Zotero menupopup items to work with the new Zotero / Save to Zotero combo button.
	6. Allow the duplicate item shortcut to work in Zotero Standalone.

* In version 1.2.5: 

    1. keyboard shortcuts were added to Zutilo and a QuickCopy menu item was added.
    2. A bug that prevented Zutilo from loading into Zotero's Firefox tab was fixed.
    3. A partial zh-CN locale was added.

* In version 1.2.4, fr, es, and de locales were added (please report any translation errors (along with better translations)!).

* In version 1.2.3, functions were added to attach pages and links in Firefox to the currently selected Zotero item and to save the current page to Zotero with attachments if the default setting is to save without attachments (or to save without attachments if the default setting is to save with them).

* As of version 1.2.1, Zutilo can be installed and uninstalled without restarting Firefox.

* As of version 1.1.17, changes made with modifyAttachments should always persist after restarting Firefox.

* As of version 1.1.16, modifyAttachments can now replace elements of the path other than the beginning.

* As of version 1.1.15, modifyAttachments should actually work with Windows paths.

* As of version 1.1.11, the main JavaScript object that Zutilo creates to add functionality to Zotero has been renamed from "Zotero.Zutilo" to "ZutiloChrome.zoteroOverlay".
Any keyboard shortcuts calling methods of this object need to switch names in order to keep working.
