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


IMPORTANT!!!

I want to thank everyone who actively uses the program and helps improve it!

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

# SVN_Searcher

Installation Requirements:
During the installation of any version of TortoiseSVN (there is no need to update Tortoise itself; simply use the Modify option), ensure that the "Command Line Tools" checkbox is selected, then complete the installation. The program itself is part of the Portable series (download and run).














