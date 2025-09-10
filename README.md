# SVN_Searcher

Installation Requirements:

During the installation of any version of TortoiseSVN (there is no need to update Tortoise itself; simply use the Modify option), ensure that the "Command Line Tools" checkbox is selected, then complete the installation. The program itself is part of the Portable series (download and run).

IMPORTANT!!!

I want to thank everyone who actively uses the program and helps improve it!

# **Major Update — v2.2.0**

**New**

- **Completely redesigned interface**
  
The visual part of the application has been reworked: the interface is now more attractive, structured, and intuitive.

- **Login and About forms**
  
They are now located under the application title: to open them, simply click on the title once.

- **Enhanced data encryption system**
  
A stronger and more secure data encryption mechanism has been implemented to improve overall security.

- **Three color themes**
  
Added theme options:
1. Light blue;
2. Dark orange;
3. Dark emerald.

To switch themes, click on the hedgehog icon: a menu will appear where you can select the theme.

- **Address history for _Enter SVN Repository Path_ textbox**
  
The last entered paths are now saved (up to 5 entries). To open the list, use the arrow on the right side of the text field.
Initially the history is empty (a popup will notify you). Duplicate addresses are not saved.
When the limit of 5 is reached, the oldest entry is replaced with the newest one. You can clear the history with the _Delete History_ button in the saved paths window.

- **Updated search logic**
  
The system now helps you understand which search modes are available:
Clicking on _Enter File Name_ textbox opens a dropdown menu to choose a "Search type". Default mode is _Contains_. Entering a single dot automatically switches to _Show all files_. Entering a dot "." followed by text switches to _Ends with_. 
This behavior applies until you manually select a different option.

- **_Case Sensitive_ option**
  
Now located on the right side of the related text fields. Behavior remains the same as before.

- **Start and stop search with _Enter_**
  
Pressing Enter now starts or stops the search.

- **_About_ window**
  
Now includes service icons and a PayPal donation button, so you can support the development.

- **New file download system**
  
Previously, downloads used the default browser. Now the process is fully localized inside the app:
Double-click a file or right-click → _Download Selected Items_.
A dialog will let you choose a save folder.
_Save path history_ is available via the arrow on the right of the text field. The last used path is selected automatically. You can save with or without folder hierarchy - controlled by a _checkbox_. The download progress is shown in a dedicated process window.

- **Audio and video support**
  
You can now open and play media files (most popular formats supported): click a file, and a built-in player will appear on the right.
Controls:
- LMB — play/pause,
- mouse wheel — volume,
- speaker icon near the timeline — quick mute/unmute.

- **New context menu features in the file list**
  
Added the ability to copy the selected file name.

- **Filters**
  
_The sort button_ has been moved to the bottom-right corner of the file list and replaced with a _Filters_ button.
Available options:
1. sort by extension;
2. sort by file name;
3. show/hide full file path;
4. hide files without extension.

- **Font scaling**
  
You can now increase or decrease the font size in the file list. Controlled via _+_ and _-_ buttons next to the percentage display.

- **_Enter Filter Text_**
  
Works as before, but now also includes a dropdown _Filter type_ (similar to _Enter File Name_).

- **Statistics**
  
The bottom-right corner now shows the total number of found files and the number of files matching the current query.

- **Tooltips**
  
Helpful _tooltips_ have been added to key interface elements.

**Fixed**

- Images not showing on first launch - fixed.
- Placeholder issues: they now always disappear correctly and no longer affect text color.
- Context menu could be triggered on an empty file list - fixed.
- Overall optimization and performance improvements.
- Minor bugs have also been fixed.

**Notes**

The application file size has almost doubled due to the large number of new features and visual improvements!

# v2.1.6

Fixed:

- There was an issue where the search process couldn't start if your password contained special characters (like "*&^%$#@"). This problem has now been fixed, and you can use any password without issues.

Added error pop-ups:

- If the login or password is not entered, you will see a pop-up asking you to fill them in;
- If the search process fails to start, after 5 seconds, you will receive Error 22, indicating that the search couldn't be initiated and further investigation is required;

# v2.1.5 (fix)

- There was a problem: if the SVN URL contained spaces, the search wouldn’t work for that query. It’s now fixed.

# v2.1.4 (Small Bugfix Patch)

Fixed:

- launching some .GIF image caused a critical error, after which it was impossible to view any other images. Now everything works correctly;

- an issue where the loading icon for the first image appeared in the top-left corner instead of the center.

# v2.1.3 (hotfix)

Added:

- You can now use the "*" wildcard both before and after the desired word when searching for files. Additionally, you can specify a particular file format at the end of your search query. This method also works with the filter.

- A new option, "Download Selected Items," has been added to the context menu, which can be accessed by right-clicking.

- You can download multiple files by selecting the desired files either using "Shift" for consecutive selection or "Ctrl" for non-consecutive selection. After selecting, right-click and choose "Download Selected Items."

Fixed:

- Empty folders are no longer displayed in the search results.


# v2.1.2 (hotfix)

Fixed:

- Images with spaces in their file paths couldn't be loaded in the preview window due to an issue. The issue has been fixed.

Added:

- .PSD file formats can now be viewed in the preview window.


# v2.1.1 (hotfix)

Added:

- The update download process is now visible and can be tracked.
- TGA format images are now displayed in the preview.
- The image preview window now includes a download progress icon.
- Icons have been added to all windows.
- Some window names have been changed.

# v2.1

Removed:

Authentication fields have been removed from the main workspace window. They are now located in the top menu under the "Login" tab.

Added:

- A top menu with two tabs - "Login" and "About". Entering the username and password is now done in a window that opens after clicking on the "Login" tab. The procedure itself remains unchanged. This was done to hide the constantly visible unnecessary fields from your view or others'.

- In the "About" tab, you can check which version of the program you currently have and whether a new update is available. If an update is available, you will be prompted to download it. Additionally, the notification about a new version now appears when the program starts.

- Case sensitivity toggle checkboxes:

	- To the right of the main search field, there is a toggleable checkbox that allows you to consider or ignore case in the query.
	- To the right of the filter text field, there is a toggleable checkbox that allows you to consider or ignore case in the refined text.

- Image preview functionality has been added. This feature is located to the right of the list of items. Simply click once on the desired file to preview it. Currently, the .PSD and .TGA formats are not supported, but this issue will be resolved in the upcoming update.

- Clicking on an image allows you to zoom in. You can close the preview window by clicking again or by clicking the close button in the upper right corner.

- In the "About" tab, there are links to GitHub, where you can review all updates, as well as my email for suggestions on improving the software.


# v2.0.1 (hotfix)

Fixed:

- There was an issue with sorting based on the information entered in the "Enter File Name" field. The entered data was not considered during the search; the search process was initiated across the entire specified path "Enter SVN Repository Path."

- At the bottom, in the "Last File" line, only the last file added to the list was displayed, whereas the file iteration process should be shown.

- The filter has been adjusted (there was an error when it considered letters and parts of words that are in the file extension).

- A horizontal scrollbar has been added to the window displaying the found items.

# v2.0.0 

How to Use and Available Features:

Authentication:

In the "Authentication" section of the program, enter your SVN resource login credentials in the "Enter Login" and "Enter Password" fields.

Initial Setup: These credentials need to be entered only once during the first launch of the program. They are then automatically saved in the program's memory. Don’t worry about entering incorrect information; you can always edit it later. Every three months, when the password is reset, simply update it, and you can continue working seamlessly.

Show Password: The checkbox to the right of the password field allows you to display the password to verify its accuracy (hidden by default).

Search Settings:

In the "Search Settings" section of the program:

Enter SVN Repository Path: Input the URL of the repository where you want to perform the search. You can specify either a general root path or a specific folder within the resource.

Enter File Name: Enter the name of the file you are searching for, the file format, or simply a dot "." (without quotes) to display all files located in the specified path.

After filling in these fields, click the "Search" button. If all the above steps are completed correctly and you have access to the repository, you will see the process of files being added in the program window. To stop the search at any stage, click the "Stop" button.

Working with the File List:

Once a list of files is generated, you can:

- Sort Files: Sort the files alphabetically and by format by clicking the "Name+Type" button next to the "Sort by" label.

- Refine Search: Perform a more precise search among the already found files. Next to the "Filter" label, enter words or parts of words to find specific files within the current list.

- Download Files: Start downloading a file directly by double-clicking on the desired file. This action will open the file link in your default browser.

- Copy Paths:

	- Copy Full Path: Right-click on the desired file and select "Copy Full Path" to copy the direct link to the file.
	- Copy Directory Path: Right-click on the desired file and select "Copy Directory Path" to copy the direct link to the folder containing the file.

- Next to the "Last File" label, you can monitor the search progress.

# v1.0.0

Added:

- Authentication fields have been added.
- The ability to enter the SVN address and search for files by name.
















